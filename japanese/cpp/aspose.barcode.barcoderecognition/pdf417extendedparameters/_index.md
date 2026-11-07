---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters クラス"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters クラス。C++ で認識されたバーコードの MacroPdf417 メタデータ情報を格納します。"
type: docs
weight: 2800
url: /ja/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


認識されたバーコードの MacroPdf417 メタデータ情報を保存します。

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | 908、909、910、または 911 の Code 128 エミュレーションコードワードでエンコードされた MicroPdf417 バーコードであることを示すフラグ。 |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** すべてのパラメーターがデフォルト値のみであるかどうかをテストします。 |
| [get_IsLinked](./get_islinked/)() const | バーコードが 1D バーコードにリンクされている必要があることを示すフラグ。 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | リーダーにシンボル内のデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。 |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Macro PDF417 受取人名（オプション）。 |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Macro PDF417 チェックサム（オプション）。 |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417 のみで利用可能なバーコードのファイル ID を取得します。 |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Macro PDF417 ファイル名（オプション）。 |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Macro PDF417 ファイルサイズ（オプション）。 |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417 のみで利用可能なバーコードのセグメント ID を取得します。 |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Macro PDF417 バーコードのセグメント数を取得します。デフォルト値は -1 です。 |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Macro PDF417 送信者名（オプション）。 |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | セグメントが Macro PDF417 ファイルの最後のセグメントかどうかを示します。 |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Macro PDF417 タイムスタンプ（オプション）。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ToString](./tostring/)() const override | この [Pdf417ExtendedParameters](./) の人間が読みやすい文字列表現を返します。 |
## 備考


このサンプルは Macro Pdf417 メタデータの取得方法を示しています。
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

## 関連項目

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
