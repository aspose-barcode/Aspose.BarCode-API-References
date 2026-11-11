---
title: "Класс MaxiCodeCodetext"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeCodetext класс. Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode"
type: docs
weight: 680
url: /ru/net/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class

Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode.

```csharp
public abstract class MaxiCodeCodetext : IComplexCodetext
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | Получает или задает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | Получает или задает режим кодирования MaxiCode. Значение по умолчанию: Auto. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Получает тип штрихкода. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodecodetext/getconstructedcodetext/)() | Создаёт текст кода |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | Получает режим MaxiCode. |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/maxicodecodetext/initfromstring/)(string) | Инициализирует экземпляр из построенного текста кода. |

## Примеры

Этот пример показывает, как декодировать необработанный текст MaxiCode в экземпляр MaxiCodeCodetext.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### См. также

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


