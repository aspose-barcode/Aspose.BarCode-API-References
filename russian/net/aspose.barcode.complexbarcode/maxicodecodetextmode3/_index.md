---
title: "Класс MaxiCodeCodetextMode3"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.ComplexBarcode.MaxiCodeCodetextMode3. Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 3"
type: docs
weight: 700
url: /ru/net/aspose.barcode.complexbarcode/maxicodecodetextmode3/
---
## MaxiCodeCodetextMode3 class

Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 3.

```csharp
public class MaxiCodeCodetextMode3 : MaxiCodeStructuredCodetext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MaxiCodeCodetextMode3](maxicodecodetextmode3/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CountryCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/countrycode/) { get; set; } | Определяет 3-значный код страны. |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | Получает или задает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | Получает или задает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [PostalCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/postalcode/) { get; set; } | Определяет почтовый индекс. Должен быть 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3. |
| [SecondMessage](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/secondmessage/) { get; set; } | Определяет второе сообщение штрихкода. |
| [ServiceCategory](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/servicecategory/) { get; set; } | Определяет 3-значную категорию услуги. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/equals/)(object) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению [`MaxiCodeStructuredCodetext`](../maxicodestructuredcodetext/). |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Получает тип штрихкода. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/getconstructedcodetext/)() | Создаёт текст кода |
| override [GetHashCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| override [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetextmode3/getmode/)() | Получает режим MaxiCode. |
| override [InitFromString](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/initfromstring/)(string) | Инициализирует экземпляр из построенного текста кода. |

## Примеры

Этот пример показывает, как кодировать и декодировать MaxiCode кодтекст для режима 3.

```csharp
[C#]
//Режим 3 со стандартным вторым сообщением
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Режим 3 со структурированным вторым сообщением
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
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
//Декодирование необработанного кодтекста со стандартным вторым сообщением
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode3){
            MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
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
//Декодирование необработанного кодтекста со структурированным вторым сообщением
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode3){
            MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
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

### См. также

* class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


