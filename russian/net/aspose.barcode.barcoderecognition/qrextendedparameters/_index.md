---
title: QRExtendedParameters
second_title: Справочник по API Aspose.BarCode для .NET
description: Сохраняет структурированное добавление QR-информации о распознанном штрих-коде
type: docs
weight: 230
url: /ru/net/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class

Сохраняет структурированное добавление QR-информации о распознанном штрих-коде

```csharp
public sealed class QRExtendedParameters : BaseExtendedParameters
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Проверяет, имеют ли все параметры только значения по умолчанию |
| [QRStructuredAppendModeBarCodeIndex](../../aspose.barcode.barcoderecognition/qrextendedparameters/qrstructuredappendmodebarcodeindex) { get; } | Получает индекс штрих-кода режима структурированного добавления QR. Индекс начинается с 0. Значение по умолчанию равно -1. |
| [QRStructuredAppendModeBarCodesQuantity](../../aspose.barcode.barcoderecognition/qrextendedparameters/qrstructuredappendmodebarcodesquantity) { get; } | Получает количество штрих-кодов режима структурированного добавления QR. Значение по умолчанию: -1. |
| [QRStructuredAppendModeParityData](../../aspose.barcode.barcoderecognition/qrextendedparameters/qrstructuredappendmodeparitydata) { get; } | Получает данные о четности в режиме добавления со структурой QR. Значение по умолчанию: -1. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/qrextendedparameters/equals)(object) | Возвращает значение, указывающее, равен ли этот экземпляр заданному[`QRExtendedParameters`](../qrextendedparameters) значение. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/qrextendedparameters/gethashcode)() | Возвращает хэш-код для этого экземпляра. |
| override [ToString](../../aspose.barcode.barcoderecognition/qrextendedparameters/tostring)() | Возвращает удобочитаемое строковое представление этого[`QRExtendedParameters`](../qrextendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_equality) | Возвращает значение, указывающее, является ли первый[`QRExtendedParameters`](../qrextendedparameters) значение равно секунде. |
| [operator !=](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_inequality) | Возвращает значение, указывающее, был ли первый[`QRExtendedParameters`](../qrextendedparameters) значение отличается от второго. |

### Примеры

В этом примере показано, как получить структурированное добавление QR data

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

### Смотрите также

* class [BaseExtendedParameters](../baseextendedparameters)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
