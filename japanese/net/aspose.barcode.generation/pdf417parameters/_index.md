---
title: Pdf417Parameters
second_title: Aspose.BarCode for.NETAPIリファレンス
description: PDF417 パラメータ PDF417MacroPDF417および MicroPDF417 パラメータが含まれます MacroPDF417 にはPdf417MacroFileID と Pdf417MacroSegmentID の 2 つのフィールドが必要です他のすべてのフィールドはオプションです 構造化追加モード MacroPDF417 モードと同じ の MicroPDF417 にはPdf417MacroFileID と Pdf417MacroSegmentID の 2 つのフィールドが必要です他のすべてのフィールドはオプションです
type: docs
weight: 1130
url: /ja/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417 パラメータ。 PDF417、MacroPDF417、および MicroPDF417 パラメータが含まれます。 MacroPDF417 には、Pdf417MacroFileID と Pdf417MacroSegmentID の 2 つのフィールドが必要です。他のすべてのフィールドはオプションです。 構造化追加モード (MacroPDF417 モードと同じ) の MicroPDF417 には、Pdf417MacroFileID と Pdf417MacroSegmentID の 2 つのフィールドが必要です。他のすべてのフィールドはオプションです。

```csharp
public class Pdf417Parameters
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | 2D バーコード モジュールの高さ/幅の比率. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation/) { get; set; } | Code 128 エミュレーションの関数コードワード。 MicroPDF417 のみに適用されます。 PDF417 および MacroPDF417 バーコードでは無視されます。 |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding/) { get; set; } | codetext のエンコーディングを取得または設定します。 デフォルト値: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | 列数. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | symbol 内に含まれるデータをリーダー初期化のプログラミングとして解釈するようリーダーに指示するために使用されます. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode/) { get; set; } | BarCode の圧縮モードの Pdf417 シンボル タイプ. デフォルト値: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding/) { get; set; } | 拡張チャネル解釈識別子。これは、バーコード リーダー details に、シンボル内のデータをエンコードするために使用される参照について伝えるために使用されます。マクロ PDF417 テキスト フィールドには適用されません。 現在の実装は、すべての既知の文字セット エンコーディングで構成されています。 |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel/) { get; set; } | バーコードのエラー修正 level の Pdf417 シンボル タイプを取得または設定します。level0 から level8 までの範囲で、level0 はエラー修正情報がないことを意味し、 level8 は最良のエラー修正を意味し、より大きな画像を意味します。 |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee/) { get; set; } | MacroPdf417 バーコード宛先名 (オプション フィールド). MicroPDF417 バーコード宛先名 (Structured Append モードのオプション フィールド) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum/) { get; set; } | MacroPdf417 バーコード チェックサム (オプション フィールド). MicroPDF417 バーコード チェックサム (Structured Append モードのオプション フィールド) チェックサム フィールドには、CCITT-16 多項式を使用した 16 ビット (2 バイト) CRC チェックサムの値が含まれます。 x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding/) { get; set; } | 拡張チャネル解釈識別子。マクロ PDF417 テキスト フィールドに適用されます。 |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid/) { get; set; } | MacroPdf417 バーコードのファイル ID (必須フィールド). MicroPDF417 バーコードのファイル ID (Structured Append モードの必須フィールド) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename/) { get; set; } | MacroPdf417 バーコード ファイル名 (オプション フィールド). MicroPDF417 バーコード ファイル名 (Structured Append モードのオプション フィールド) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize/) { get; set; } | MacroPdf417 ファイル サイズ (オプション フィールド). MicroPDF417 ファイル サイズ (Structured Append モードのオプション フィールド) ファイル サイズ フィールドには、ソース ファイル全体のバイト単位のサイズが含まれます. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid/) { get; set; } | MacroPdf417 バーコードのセグメント ID (必須フィールド)。0 から MacroSegmentsCount - 1 まで。 MicroPDF417 バーコードのセグメント ID (構造化追加モードの必須フィールド) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount/) { get; set; } | MacroPdf417 バーコード セグメント カウント (オプション フィールド). MicroPDF417 バーコード セグメント カウント (Structured Append モードのオプション フィールド) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender/) { get; set; } | MacroPdf417 バーコード送信者名 (オプション フィールド). MicroPDF417 バーコード送信者名 (Structured Append モードのオプション フィールド) |
| [Pdf417MacroTerminator](../../aspose.barcode.generation/pdf417parameters/pdf417macroterminator/) { get; set; } | Macro PDF417 Terminator (コードワード 922) をセグメントに追加するかどうかをエンコーダーに伝えるために使用されます。 マクロ PDF417. のみに適用 |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp/) { get; set; } | MacroPdf417 バーコード タイム スタンプ (オプション フィールド). MicroPDF417 バーコード タイム スタンプ (Structured Append モードのオプション フィールド) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate/) { get; set; } | BarCode の Pdf417 シンボル タイプが切り捨てられるかどうか (スペースを減らすため)。 CompactPDF417 とも呼ばれます。このモードでは、右行インジケーターと右ストップ パターンが削除されます。 |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | 行数. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | これの人間が読める文字列表現を返します`Pdf417Parameters`. |

### 関連項目

* 名前空間 [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
