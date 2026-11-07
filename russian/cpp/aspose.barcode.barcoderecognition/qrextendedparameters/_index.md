---
title: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters класс"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters класс. Сохраняет информацию о QR Structured Append распознанного штрихкода в C++."
type: docs
weight: 2900
url: /ru/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


Сохраняет информацию о [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append распознанного штрихкода

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Описание |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | Уровень коррекции ошибок Reed-Solomon распознанного штрихкода. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** проверяет, имеют ли все параметры только значения по умолчанию |
| [get_MicroQRVersion](./get_microqrversion/)() const | Версия распознанного MicroQR Code. От M1 до M4. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | Версия распознанного RectMicroQR Code. От R7x43 до R17x139. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | Получает индекс [QR](../../aspose.barcode.barcoderecognition.qr/) штрихкода в режиме structured append. Индекс начинается с 0. Значение по умолчанию — -1. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | Получает количество [QR](../../aspose.barcode.barcoderecognition.qr/) штрихкодов в режиме structured append. Значение по умолчанию — -1. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | Получает данные четности [QR](../../aspose.barcode.barcoderecognition.qr/) в режиме structured append. Значение по умолчанию — -1. |
| [get_Version](./get_version/)() const | Версия распознанного [QR](../../aspose.barcode.barcoderecognition.qr/) кода. От Version1 до Version40. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [QRExtendedParameters](./). |
## Примечания


Этот пример показывает, как получить данные [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append.
```cpp
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

## См. также

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
