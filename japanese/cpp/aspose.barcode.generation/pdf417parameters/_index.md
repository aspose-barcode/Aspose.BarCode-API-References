---
title: "Aspose::BarCode::Generation::Pdf417Parameters クラス"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::Pdf417Parameters クラス。PDF417 パラメータ。PDF417、MacroPDF417、MicroPDF417、GS1MicroPdf417 のパラメータを含みます。MacroPDF417 には 2 つのフィールド、Pdf417MacroFileID と Pdf417MacroSegmentID が必要です。その他のフィールドはすべてオプションです。Structured Append モードの MicroPDF417（MacroPDF417 モードと同じ）にも 2 つのフィールド、Pdf417MacroFileID と Pdf417MacroSegmentID が必要です。C++ ではその他のフィールドはすべてオプションです。"
type: docs
weight: 4000
url: /ja/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


PDF417 パラメータ。PDF417、MacroPDF417、MicroPDF417、そして GS1MicroPdf417 のパラメータを含みます。MacroPDF417 には 2 つのフィールド、Pdf417MacroFileID と Pdf417MacroSegmentID が必要です。他のすべてのフィールドはオプションです。Structured Append モードの MicroPDF417（MacroPDF417 モードと同じ）には 2 つのフィールド、Pdf417MacroFileID と Pdf417MacroSegmentID が必要です。他のすべてのフィールドはオプションです。

```cpp
class Pdf417Parameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [get_Columns](./get_columns/)() const | 列数。 |
| [get_ECIEncoding](./get_eciencoding/)() const | 拡張チャネル解釈識別子。シンボル内のデータをエンコードする際に使用された参照情報をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装は、すべての既知の文字セットエンコーディングを含んでいます。 |
| [get_EncodeMode](./get_encodemode/)() const | Pdf417 のエンコードモードを識別します。デフォルト値: Auto。 |
| [get_ErrorLevel](./get_errorlevel/)() const | [BarCode](../../aspose.barcode/) のエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを取得します。level0 はエラー訂正情報がなく、level8 は最高のエラー訂正であり、より大きな画像になります。 |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | MicroPdf417 のみで使用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、さらに 910 と 911 をエンコードできますが、これは認識された MicroPdf417 が Code 128 として解釈できることを示すだけです。 |
| [get_IsLinked](./get_islinked/)() const | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 の「リンク」UCC/EAN-128 モードをエンコードします。MicroPdf417 および Pdf417 シンボルでは、EAN.UCC 以外の関連線形コンポーネントへのリンクフラグ 918 をエンコードします。 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | リーダーにシンボル内のデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。 |
| [get_MacroCharacters](./get_macrocharacters/)() const | マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを取得するために使用されます。MicroPdf417 のみで使用でき、916 と 917 の MicroPdf417 モードをエンコードします。デフォルト値: [MacroCharacters.None](../barcodeclassifications/)。 |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | MacroPdf417 バーコードの宛先名（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードの宛先名（オプションフィールド） |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | MacroPdf417 バーコードのチェックサム（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードのチェックサム（オプションフィールド）。チェックサムフィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | 拡張チャネル解釈識別子。Macro PDF417 のテキストフィールドに適用されます。 |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417 バーコードのファイル ID（必須フィールド）。Structured Append モード用の MicroPDF417 バーコードのファイル ID（必須フィールド） |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | MacroPdf417 バーコードのファイル名（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードのファイル名（オプションフィールド） |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | MacroPdf417 のファイルサイズ（オプションフィールド）。Structured Append モード用の MicroPDF417 のファイルサイズ（オプションフィールド）。ファイルサイズフィールドは、元のソースファイル全体のバイト数を示します。 |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417 バーコードのセグメント ID（必須フィールド）。0 から MacroSegmentsCount - 1 までです。Structured Append モード用の MicroPDF417 バーコードのセグメント ID（必須フィールド） |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | MacroPdf417 バーコードのセグメント数（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードのセグメント数（オプションフィールド） |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | MacroPdf417 バーコードの送信者名（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードの送信者名（オプションフィールド） |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | エンコーダにセグメントへ Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用します。Macro PDF417 にのみ適用されます。 |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードのタイムスタンプ（オプションフィールド） |
| [get_Rows](./get_rows/)() const | 行数。 |
| [get_Truncate](./get_truncate/)() const | [BarCode](../../aspose.barcode/) の Pdf417 シンボルタイプが省略（スペース削減）されているかどうか。CompactPDF417 とも呼ばれます。このモードでは右側の行インジケータと右側のストップパターンが削除されます。 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [set_Columns](./set_columns/)(int32_t) | 列数。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 拡張チャネル解釈識別子。シンボル内のデータをエンコードする際に使用された参照情報をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装は、すべての既知の文字セットエンコーディングを含んでいます。 |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Pdf417 のエンコードモードを識別します。デフォルト値: Auto。 |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | この [BarCode](../../aspose.barcode/) のエラー訂正レベルの Pdf417 シンボルタイプを設定します。レベルは level0 から level8 まであり、level0 はエラー訂正情報なし、level8 は最高のエラー訂正で、画像が大きくなります。 |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | MicroPdf417 のみで使用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、さらに 910 と 911 をエンコードできますが、これは認識された MicroPdf417 が Code 128 として解釈できることを示すだけです。 |
| [set_IsLinked](./set_islinked/)(bool) | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 の「リンク」UCC/EAN-128 モードをエンコードします。MicroPdf417 および Pdf417 シンボルでは、EAN.UCC 以外の関連線形コンポーネントへのリンクフラグ 918 をエンコードします。 |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | リーダーにシンボル内のデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。 |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを取得するために使用されます。MicroPdf417 のみで使用でき、916 と 917 の MicroPdf417 モードをエンコードします。デフォルト値: [MacroCharacters.None](../barcodeclassifications/)。 |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | MacroPdf417 バーコードの宛先名（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードの宛先名（オプションフィールド） |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | MacroPdf417 バーコードのチェックサム（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードのチェックサム（オプションフィールド）。チェックサムフィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | 拡張チャネル解釈識別子。Macro PDF417 のテキストフィールドに適用されます。 |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | MacroPdf417 バーコードのファイル ID（必須フィールド）。Structured Append モード用の MicroPDF417 バーコードのファイル ID（必須フィールド） |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | MacroPdf417 バーコードのファイル名（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードのファイル名（オプションフィールド） |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | MacroPdf417 のファイルサイズ（オプションフィールド）。Structured Append モード用の MicroPDF417 のファイルサイズ（オプションフィールド）。ファイルサイズフィールドは、元のソースファイル全体のバイト数を示します。 |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | MacroPdf417 バーコードのセグメント ID（必須フィールド）。0 から MacroSegmentsCount - 1 までです。Structured Append モード用の MicroPDF417 バーコードのセグメント ID（必須フィールド） |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | MacroPdf417 バーコードのセグメント数（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードのセグメント数（オプションフィールド） |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | MacroPdf417 バーコードの送信者名（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードの送信者名（オプションフィールド） |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | エンコーダにセグメントへ Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用します。Macro PDF417 にのみ適用されます。 |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。Structured Append モード用の MicroPDF417 バーコードのタイムスタンプ（オプションフィールド） |
| [set_Rows](./set_rows/)(int32_t) | 行数。 |
| [set_Truncate](./set_truncate/)(bool) | [BarCode](../../aspose.barcode/) の Pdf417 シンボルタイプが省略（スペース削減）されているかどうか。CompactPDF417 とも呼ばれます。このモードでは右側の行インジケータと右側のストップパターンが削除されます。 |
| [ToString](./tostring/)() const override | この [Pdf417Parameters](./) の人間が読みやすい文字列表現を返します。 |
## 備考


これらのサンプルは、GS1MicroPdf417 で UCC/EAN-128 の非リンクモードをエンコードする方法を示しています。
```cpp
[C#]
//AI 01 (GTIN) を使用して、GS1 UCC/EAN-128 の非リンクモード 905 をエンコードします。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//任意の AI を使用して、GS1 UCC/EAN-128 の非リンクモード 903、904 をエンコードします。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
