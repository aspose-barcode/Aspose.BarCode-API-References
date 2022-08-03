---
title: BarCodeResult
second_title: Справочник по API Aspose.BarCode для .NET
description: Сохраняет распознанные данные штрих-кода такие какSingleDecodeType./singledecodetype типString кодовый текст BarCodeRegionParameters./barcoderegionparameters регион и другие параметры
type: docs
weight: 90
url: /ru/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Сохраняет распознанные данные штрих-кода, такие как[`SingleDecodeType`](../singledecodetype) тип,String кодовый текст, [`BarCodeRegionParameters`](../barcoderegionparameters) регион и другие параметры

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BarCodeResult](barcoderesult)(BarCodeResult) | Создает копию[`BarCodeResult`](../barcoderesult) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes) { get; } | Получает закодированные байты кода |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext) { get; } | Получает текст кода |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype) { get; } | Получает тип штрих-кода |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename) { get; } | Получает имя типа штрих-кода |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence) { get; } | Получает уровень достоверности распознавания распознанного штрих-кода |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended) { get; } | Получает расширенные параметры распознанного штрих-кода |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality) { get; } | Получает качество чтения. Работает для 1D и почтовых штрих-кодов. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region) { get; } | Получает область штрих-кода |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone)() | Создает копию[`BarCodeResult`](../barcoderesult) класс. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals)(BarCodeResult) | Возвращает значение, указывающее, равен ли этот экземпляр заданному[`BarCodeResult`](../barcoderesult) значение. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals_1)(object) | Возвращает значение, указывающее, равен ли этот экземпляр заданному[`BarCodeResult`](../barcoderesult) значение. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext)(Encoding) | Получает текст кода с кодировкой. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode)() | Возвращает хэш-код для этого экземпляра. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring)() | Возвращает удобочитаемое строковое представление этого[`BarCodeResult`](../barcoderesult) . |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality) | Возвращает значение, указывающее, является ли первый[`BarCodeResult`](../barcoderesult) значение равно секунде. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality) | Возвращает значение, указывающее, был ли первый[`BarCodeResult`](../barcoderesult) значение отличается от второго. |

### Примеры

В этом примере показано, как получить BarCodeResult.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### Смотрите также

* пространство имен [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
