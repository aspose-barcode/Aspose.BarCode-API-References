---
title: "Класс MaxiCodeStructuredCodetext"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeStructuredCodetext class. Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 2 и 3"
type: docs
weight: 740
url: /ru/net/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class

Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 2 и 3.

```csharp
public abstract class MaxiCodeStructuredCodetext : MaxiCodeCodetext
```

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
| override [Equals](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/equals/)(object) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `MaxiCodeStructuredCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Получает тип штрихкода. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/getconstructedcodetext/)() | Создаёт текст кода |
| override [GetHashCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | Получает режим MaxiCode. |
| override [InitFromString](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/initfromstring/)(string) | Инициализирует экземпляр из построенного текста кода. |

## Примеры

Этот пример показывает, как декодировать необработанный MaxiCode кодтекст в экземпляр MaxiCodeStructuredCodetext.

```csharp
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

### См. также

* class [MaxiCodeCodetext](../maxicodecodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


