---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext класс"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext класс. Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 2 и 3 в C++."
type: docs
weight: 2200
url: /ru/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 2 и 3.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [MaxiCodeStructuredCodetext](./). |
| [get_CountryCode](./get_countrycode/)() const | Определяет 3-значный код страны. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Получает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Получает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [get_PostalCode](./get_postalcode/)() const | Определяет почтовый индекс. Должен быть 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3. |
| [get_SecondMessage](./get_secondmessage/)() const | Определяет второе сообщение штрихкода. |
| [get_ServiceCategory](./get_servicecategory/)() const | Определяет 3-значную категорию сервиса. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Получает тип штрихкода. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Создаёт текст кода |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | Получает режим MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | Инициализирует экземпляр из построенного текста кода. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | Определяет 3-значный код страны. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Устанавливает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [set_PostalCode](./set_postalcode/)(System::String) | Определяет почтовый индекс. Должен быть 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Определяет второе сообщение штрихкода. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | Определяет 3-значную категорию сервиса. |
## Примечания


Этот пример показывает, как декодировать необработанный текст кода MaxiCode в экземпляр [MaxiCodeStructuredCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

## См. также

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
