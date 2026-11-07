---
title: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters クラス"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters クラス。C++ で認識された 1D バーコードのコードテキストとチェックサムを別々に保持するなど、特別なデータを格納します。"
type: docs
weight: 2700
url: /ja/cpp/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class


認識された 1D バーコードの、個別のコードテキストやチェックサムなどの特殊データを保存します。

```cpp
class OneDExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_CheckSum](./get_checksum/)() const | 1D バーコードのチェックサムを取得します。 |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** すべてのパラメーターがデフォルト値のみであるかどうかをテストします。 |
| [get_Value](./get_value/)() const | チェックサムなしで 1D バーコードのコードテキストを取得します。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ToString](./tostring/)() const override | この [OneDExtendedParameters](./) の人間が読みやすい文字列表現を返します。 |
## 備考


このサンプルは 1D バーコードの値とチェックサムの取得方法を示しています。
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## 関連項目

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
