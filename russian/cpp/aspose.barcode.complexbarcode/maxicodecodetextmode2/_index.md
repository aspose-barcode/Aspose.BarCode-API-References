---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2 класс"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2 класс. Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 2 в C++."
type: docs
weight: 1700
url: /ru/cpp/aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
## MaxiCodeCodetextMode2 class


Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 2.

```cpp
class MaxiCodeCodetextMode2 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/). |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() const | Определяет 3-значный код страны. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Получает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Получает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() const | Определяет почтовый индекс. Должен быть 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3. |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | Определяет второе сообщение штрихкода. |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() const | Определяет 3-значную категорию сервиса. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Получает тип штрихкода. |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | Создаёт текст кода |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [GetMode](./getmode/)() const override | Получает режим MaxiCode. |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | Инициализирует экземпляр из построенного текста кода. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | Определяет 3-значный код страны. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Устанавливает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | Определяет почтовый индекс. Должен быть 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3. |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Определяет второе сообщение штрихкода. |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | Определяет 3-значную категорию сервиса. |
## Примечания


Этот пример показывает, как кодировать и декодировать кодетекст MaxiCode для режима 2.
```cpp
[C#]
//Режим 2 со стандартным вторым сообщением
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Режим 2 со структурированным вторым сообщением
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Декодирование необработанного текста кода со стандартным вторым сообщением
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStandardSecondMessage){
                MaxiCodeStandardSecondMessage secondMessage = (MaxiCodeStandardSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message: " + secondMessage.Message);
            }
        }
    }
}
//Декодирование необработанного текста кода со структурированным вторым сообщением
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStructuredSecondMessage){
                MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message:");
                foreach (var identifier in secondMessage.Identifiers){
                    Console.WriteLine(identifier);
                }
            }
        }
    }
}
```

## См. также

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
