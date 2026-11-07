---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters クラス"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters クラス。C++ で認識されたバーコードの領域とバーコードの角度を表します。"
type: docs
weight: 600
url: /ja/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


認識されたバーコードの領域とバーコードの角度を表します

```cpp
class BarCodeRegionParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Angle](./get_angle/)() const | バーコードの角度 (0-360) を取得します。 |
| [get_Points](./get_points/)() const | [Point](../) の配列でバーコード領域を囲むものを取得します。 |
| [get_Quadrangle](./get_quadrangle/)() const | [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) でバーコード領域を囲むものを取得します。 |
| [get_Rectangle](./get_rectangle/)() const | **System::Drawing::Rectangle** でバーコード領域を囲むものを取得します。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ToString](./tostring/)() const override | この [BarCodeRegionParameters](./) の人間が読みやすい文字列表現を返します。 |
## 備考


このサンプルは、バーコードの角度と囲む四角形の値を取得する方法を示しています。
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
