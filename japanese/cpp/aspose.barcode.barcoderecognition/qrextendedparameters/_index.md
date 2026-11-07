---
title: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters クラス"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters クラス。認識されたバーコードの QR Structured Append 情報を C++ で保存します。"
type: docs
weight: 2900
url: /ja/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


認識されたバーコードの [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append 情報を保存します

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | 認識されたバーコードの Reed-Solomon エラー訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。 |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** すべてのパラメーターがデフォルト値のみであるかどうかをテストします。 |
| [get_MicroQRVersion](./get_microqrversion/)() const | 認識された MicroQR コードのバージョン。M1 から M4 まで。 |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | 認識された RectMicroQR コードのバージョン。R7x43 から R17x139 まで。 |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | [QR](../../aspose.barcode.barcoderecognition.qr/) 構造付加モードバーコードのインデックスを取得します。インデックスは 0 から開始します。デフォルト値は -1 です。 |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | [QR](../../aspose.barcode.barcoderecognition.qr/) 構造付加モードバーコードの数量を取得します。デフォルト値は -1 です。 |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | [QR](../../aspose.barcode.barcoderecognition.qr/) 構造付加モードのパリティデータを取得します。デフォルト値は -1 です。 |
| [get_Version](./get_version/)() const | 認識された [QR](../../aspose.barcode.barcoderecognition.qr/) コードのバージョン。Version1 から Version40 まで。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ToString](./tostring/)() const override | この [QRExtendedParameters](./) の人間が読みやすい文字列表現を返します。 |
## 備考


このサンプルは、[QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append データの取得方法を示しています
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

## 関連項目

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
