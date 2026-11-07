---
title: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters クラス"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters クラス。認識されたバーコードの DataBar 追加情報を C++ で格納します。"
type: docs
weight: 1400
url: /ja/cpp/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class


認識されたバーコードの DataBar 追加情報を格納します

```cpp
class DataBarExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Is2DCompositeComponent](./get_is2dcompositecomponent/)() const | DataBar 2D 複合コンポーネントフラグを取得します。デフォルト値は false です。 |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** すべてのパラメーターがデフォルト値のみであるかどうかをテストします。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ToString](./tostring/)() const override | この [DataBarExtendedParameters](./) の人間が読みやすい文字列表現を返します。 |
## 備考


このサンプルは DataBar の追加情報の取得方法を示します。
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

## 関連項目

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
