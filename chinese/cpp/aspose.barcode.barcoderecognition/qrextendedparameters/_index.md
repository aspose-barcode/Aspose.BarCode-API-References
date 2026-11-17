---
title: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters 类"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters 类。存储在 C++ 中识别的条码的 QR 结构化追加信息。"
type: docs
weight: 2900
url: /zh/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


存储已识别条码的 [QR](../../aspose.barcode.barcoderecognition.qr/) 结构化追加信息。

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | 已识别条码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。 |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 是否所有参数仅具有默认值 |
| [get_MicroQRVersion](./get_microqrversion/)() const | 已识别 MicroQR 码的版本。从 M1 到 M4。 |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | 已识别 RectMicroQR 码的版本。从 R7x43 到 R17x139。 |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | 获取 [QR](../../aspose.barcode.barcoderecognition.qr/) 结构化追加模式条码的索引。索引从 0 开始。默认值为 -1。 |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | 获取 [QR](../../aspose.barcode.barcoderecognition.qr/) 结构化追加模式条码的数量。默认值为 -1。 |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | 获取 [QR](../../aspose.barcode.barcoderecognition.qr/) 结构化追加模式的奇偶校验数据。默认值为 -1。 |
| [get_Version](./get_version/)() const | 已识别的 [QR](../../aspose.barcode.barcoderecognition.qr/) 码的版本。从 Version1 到 Version40。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ToString](./tostring/)() const override | 返回此 [QRExtendedParameters](./) 的人类可读字符串表示。 |
## 备注


此示例展示如何获取 [QR](../../aspose.barcode.barcoderecognition.qr/) 结构化追加数据。
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

## 另见

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
