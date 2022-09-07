---
title: Pdf417ExtendedParameters
second_title: Справочник по API Aspose.BarCode для .NET
description: Сохраняет метаданные MacroPdf417 распознанного штрих-кода
type: docs
weight: 220
url: /ru/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

Сохраняет метаданные MacroPdf417 распознанного штрих-кода

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Проверяет, имеют ли все параметры только значения по умолчанию |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee) { get; } | Имя адресата макроса PDF417 (необязательно). |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum) { get; } | Контрольная сумма макроса PDF417 (необязательно). |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid) { get; } | Получает идентификатор файла штрих-кода, доступный только с MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename) { get; } | Имя файла макроса PDF417 (необязательно). |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize) { get; } | Размер файла макроса PDF417 (необязательно). |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid) { get; } | Получает идентификатор сегмента штрих-кода, доступный только с MacroPdf417. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount) { get; } | Получает количество сегментов штрих-кода макроса pdf417. Значение по умолчанию: -1. |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender) { get; } | Имя отправителя макроса PDF417 (необязательно). |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp) { get; } | Отметка времени макроса PDF417 (необязательно). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals)(object) | Возвращает значение, указывающее, равен ли этот экземпляр заданному[`Pdf417ExtendedParameters`](../pdf417extendedparameters) значение. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode)() | Возвращает хэш-код для этого экземпляра. |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring)() | Возвращает удобочитаемое строковое представление этого[`Pdf417ExtendedParameters`](../pdf417extendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality) | Возвращает значение, указывающее, является ли первый[`Pdf417ExtendedParameters`](../pdf417extendedparameters) значение равно секунде. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality) | Возвращает значение, указывающее, был ли первый[`Pdf417ExtendedParameters`](../pdf417extendedparameters) значение отличается от второго. |

### Примеры

В этом примере показано, как получить метаданные Macro Pdf417

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

### Смотрите также

* class [BaseExtendedParameters](../baseextendedparameters)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
