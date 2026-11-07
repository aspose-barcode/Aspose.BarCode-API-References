---
title: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters クラス。C++ で認識された Code128 バーコードの特別なデータを格納します。"
type: docs
weight: 1300
url: /ja/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


Code128 認識バーコードの特殊データを格納します

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | 認識された Code128 バーコードの [Code128DataPortion](../code128dataportion/) 配列を取得します |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** すべてのパラメーターがデフォルト値のみであるかどうかをテストします。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ToString](./tostring/)() const override | この [Code128ExtendedParameters](./) の人間が読みやすい文字列表現を返します |
## 備考


認識されたバーコードの領域とバーコードの角度を表します

このサンプルは code128 の生データ値の取得方法を示しています
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

## 関連項目

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
