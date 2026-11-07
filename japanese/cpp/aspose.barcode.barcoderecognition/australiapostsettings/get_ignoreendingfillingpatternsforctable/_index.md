---
title: "メソッド"
linktitle: "get_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。CTable メソッドとしてデコード中に、Customer Information Field の最後のフィリングパターンを無視するよう AustraliaPost デコーダに強制するフラグです。CTable エンコーディングメソッドではエンコーディングテーブルにギャップがなく、フィリングパターンのシーケンス \"333\" は文字 \"z\" としてデコードされます。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode.barcoderecognition/australiapostsettings/get_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable method


デコード時に CTable 方法として顧客情報フィールドの最後のフィリングパターンを無視するよう AustraliaPost デコーダに強制するフラグです。CTable エンコーディング方式はエンコードテーブルにギャップがなく、フィリングパターンのシーケンス "333" は文字 "z" としてデコードされます。

```cpp
bool Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable() const
```

## 備考


CTable メソッドでのデコード中に、AustraliaPost デコーダが最後のフィリングパターンを無視するように強制するフラグです。

このサンプルは、CTable 解釈タイプを使用し、フィリングパターンを無視して Australia Post バーコードを生成および認識する方法を示します。
```cpp
    [C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = True
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

## 関連項目

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
