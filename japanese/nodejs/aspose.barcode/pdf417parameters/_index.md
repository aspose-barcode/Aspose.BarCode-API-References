---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "PDF417 パラメータ。"
type: docs
weight: 770
url: /ja/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

PDF417 パラメータ。PDF417、MacroPDF417、MicroPDF417、GS1MicroPdf417 のパラメータを含みます。MacroPDF417 には 2 つのフィールド、Pdf417MacroFileID と Pdf417MacroSegmentID が必要です。他のすべてのフィールドはオプションです。構造化付加モードの MicroPDF417（MacroPDF417 モードと同じ）にも 2 つのフィールド、Pdf417MacroFileID と Pdf417MacroSegmentID が必要です。他のすべてのフィールドはオプションです。これらのサンプルは GS1MicroPdf417 で UCC/EAN-128 の非リンクモードをエンコードする方法を示しています。

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D バーコードモジュールの高さ/幅比率 |
| [getColumns()](#getcolumns) | 列数。 |
| [getECIEncoding()](#geteciencoding) | 拡張チャンネル解釈識別子です。使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。 |
| [getEncodeMode()](#getencodemode) | Pdf417 エンコードモードを識別します。デフォルト値: Auto。 |
| [getErrorLevel()](#geterrorlevel) | BarCode のエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを取得します。level0 はエラー訂正なしを意味します。 |
| [getMacroCharacters()](#getmacrocharacters) | Macro Characters 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを取得するために使用されます。Micro とだけ併用できます。 |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | MacroPdf417 バーコードの宛先名（オプション フィールド）。MicroPDF417 バーコードの宛先名（構造化 A 用のオプション フィールド） |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | MacroPdf417 バーコードのチェックサム（オプション フィールド）。MicroPDF417 バーコードのチェックサム（構造化アペンド モード用のオプション フィールド） |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | 拡張チャネル解釈識別子。Macro PDF417 のテキスト フィールドに適用されます。 |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | MacroPdf417 バーコードのファイル ID（必須フィールド）。MicroPDF417 バーコードのファイル ID（構造化アペンド モード用の必須フィールド） |
| [getMacroPdf417FileName()](#getmacropdf417filename) | MacroPdf417 バーコードのファイル名（オプション フィールド）。MicroPDF417 バーコードのファイル名（構造化アペンド モード用のオプション フィールド） |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | MacroPdf417 のファイルサイズ（オプション フィールド）。MicroPDF417 のファイルサイズ（構造化アペンド モード用のオプション フィールド）。ファイルサイズ |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | MacroPdf417 バーコードのセグメント ID（必須フィールド）。0 から MacroSegmentsCount - 1 までです。MicroPDF417 バーコードの |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | MacroPdf417 バーコードのセグメント数（オプション フィールド）。MicroPDF417 バーコードのセグメント数（構造化 A 用のオプション フィールド） |
| [getMacroPdf417Sender()](#getmacropdf417sender) | MacroPdf417 バーコードの送信者名（オプション フィールド）。MicroPDF417 バーコードの送信者名（構造化アペンド 用のオプション フィールド） |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | エンコーダにセグメントへ Macro PDF417 Terminator（コードワード 922）を追加するかどうかを指示するために使用します。Macro PD にのみ適用されます。 |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | MacroPdf417 バーコードのタイムスタンプ（オプション フィールド）。MicroPDF417 バーコードのタイムスタンプ（構造化アペンド 用のオプション フィールド） |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | BarCode のコンパクション モードにおける Pdf417 シンボロジー タイプ。デフォルト値: Pdf417CompactionMode.AUTO。 |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | 拡張チャンネル解釈識別子です。使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。 |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Pdf417 エンコードモードを識別します。デフォルト値: Auto。 |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | BarCode のエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを取得します。level0 はエラー訂正なしを意味します。 |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | マクロ Pdf417 バーコードの宛先名を取得します。 |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | マクロ Pdf417 バーコードのチェックサムを取得します。 |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | 拡張チャネル解釈識別子。Macro PDF417 のテキスト フィールドに適用されます。 |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Getsmacro Pdf417 バーコードのファイル ID を取得します。MacroPdf417 用に使用されます。 |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | マクロ Pdf417 バーコードのファイル名を取得します。 |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | マクロ Pdf417 のファイルサイズを取得します。 |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | マクロ Pdf417 バーコードのセグメント ID を取得します。0 から MacroSegmentsCount - 1 までです。 |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | マクロ Pdf417 バーコードのセグメント数を取得します。 |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | マクロ Pdf417 バーコードの送信者名を取得します。 |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | エンコーダにセグメントへ Macro PDF417 Terminator（コードワード 922）を追加するかどうかを指示するために使用します。Macro PD にのみ適用されます。 |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | マクロ Pdf417 バーコードのタイムスタンプを取得します。 |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | BarCode の Pdf417 シンボロジー タイプが省略されているかどうか（スペース削減のため）。 |
| [getRows()](#getrows) | 行数。 |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | DotCode 構造化アペンド モードのバーコード ID を識別します。ID は 1 から始まり、バーコード数以下である必要があります。 |
| [getTruncate()](#gettruncate) | BarCode の Pdf417 シンボロジー タイプが省略されているかどうか（スペース削減のため）。CompactPDF417 とも呼ばれます。右側の指示子 |
| [isCode128Emulation()](#iscode128emulation) | MicroPdf417 とだけ併用でき、Code 128 エミュレーション モードをエンコードします。第2位置で FNC1 をエンコードできるモード 908 など |
| [isLinked()](#islinked) | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードでリンクモードを定義します。GS1MicroPdf417 シンボルは 906、907 をエンコードします。 |
| [isReaderInitialization()](#isreaderinitialization) | シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するよう、リーダーに指示するために使用されます。 |
| [setAspectRatio()](#setaspectratio) | 2D バーコードモジュールの高さ/幅比率 |
| [setCode128Emulation()](#setcode128emulation) | MicroPdf417 とだけ併用でき、Code 128 エミュレーション モードをエンコードします。第2位置で FNC1 をエンコードできるモード 908 など |
| [setColumns()](#setcolumns) | 列数。 |
| [setECIEncoding()](#seteciencoding) | 拡張チャンネル解釈識別子です。使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。 |
| [setEncodeMode()](#setencodemode) | Pdf417 エンコードモードを識別します。デフォルト値: Auto。 |
| [setErrorLevel(value)](#seterrorlevel) | Pdf417 シンボルタイプの BarCode のエラー訂正レベルを level0 から level8 の範囲で設定します。level0 はエラー訂正なしを意味します。 |
| [setLinked()](#setlinked) | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードでリンクモードを定義します。GS1MicroPdf417 シンボルは 906、907 をエンコードします。 |
| [setMacroCharacters()](#setmacrocharacters) | Macro Characters 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを取得するために使用されます。Micro とだけ併用できます。 |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | MacroPdf417 バーコードの宛先名（オプション フィールド）。MicroPDF417 バーコードの宛先名（構造化 A 用のオプション フィールド） |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | MacroPdf417 バーコードのチェックサム（オプション フィールド）。MicroPDF417 バーコードのチェックサム（構造化アペンド モード用のオプション フィールド） |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | 拡張チャネル解釈識別子。Macro PDF417 のテキスト フィールドに適用されます。 |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | MacroPdf417 バーコードのファイル ID（必須フィールド）。MicroPDF417 バーコードのファイル ID（構造化アペンド モード用の必須フィールド） |
| [setMacroPdf417FileName()](#setmacropdf417filename) | MacroPdf417 バーコードのファイル名（オプション フィールド）。MicroPDF417 バーコードのファイル名（構造化アペンド モード用のオプション フィールド） |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | MacroPdf417 のファイルサイズ（オプション フィールド）。MicroPDF417 のファイルサイズ（構造化アペンド モード用のオプション フィールド）。ファイルサイズ |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | MacroPdf417 バーコードのセグメント ID（必須フィールド）。0 から MacroSegmentsCount - 1 までです。MicroPDF417 バーコードの |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | MacroPdf417 バーコードのセグメント数（オプション フィールド）。MicroPDF417 バーコードのセグメント数（構造化 A 用のオプション フィールド） |
| [setMacroPdf417Sender()](#setmacropdf417sender) | MacroPdf417 バーコードの送信者名（オプション フィールド）。MicroPDF417 バーコードの送信者名（構造化アペンド 用のオプション フィールド） |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | エンコーダにセグメントへ Macro PDF417 Terminator（コードワード 922）を追加するかどうかを指示するために使用します。Macro PD にのみ適用されます。 |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | MacroPdf417 バーコードのタイムスタンプ（オプション フィールド）。MicroPDF417 バーコードのタイムスタンプ（構造化アペンド 用のオプション フィールド） |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | BarCode のコンパクション モードにおける Pdf417 シンボロジー タイプ。デフォルト値: Pdf417CompactionMode.AUTO。 |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | 拡張チャンネル解釈識別子です。使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。 |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Pdf417 エンコードモードを識別します。デフォルト値: Auto。 |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Pdf417 シンボルタイプの BarCode のエラー訂正レベルを level0 から level8 の範囲で設定します。level0 はエラー訂正なしを意味します。 |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | マクロ Pdf417 バーコードの受取人名を設定します。 |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | マクロ Pdf417 バーコードのチェックサムを設定します。 |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | 拡張チャネル解釈識別子。Macro PDF417 のテキスト フィールドに適用されます。 |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | マクロ Pdf417 バーコードのファイル ID を設定します。MacroPdf417 用です。 |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | マクロ Pdf417 バーコードのファイル名を設定します。 |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | マクロ Pdf417 のファイルサイズを設定します。 |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | マクロ Pdf417 バーコードのセグメント ID を設定します。0 から始まり、MacroSegmentsCount - 1 までです。 |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | マクロ Pdf417 バーコードのセグメント数を設定します。 |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | マクロ Pdf417 バーコードの送信者名を設定します。 |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | エンコーダにセグメントへ Macro PDF417 Terminator（コードワード 922）を追加するかどうかを指示するために使用します。Macro PD にのみ適用されます。 |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | マクロ Pdf417 バーコードのタイムスタンプを設定します。 |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | BarCode の Pdf417 シンボロジー タイプが省略されているかどうか（スペース削減のため）。 |
| [setReaderInitialization(value)](#setreaderinitialization) | シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するよう、リーダーに指示するために使用されます。 |
| [setRows()](#setrows) | 行数。 |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | DotCode 構造化アペンド モードのバーコード ID を識別します。ID は 1 から始まり、バーコード数以下である必要があります。 |
| [setTruncate()](#settruncate) | BarCode の Pdf417 シンボロジー タイプが省略されているかどうか（スペース削減のため）。CompactPDF417 とも呼ばれます。右側の指示子 |
| [toString()](#tostring) | この Pdf417Parameters の人間が読みやすい文字列表現を返します。 |

### getAspectRatio() {#getaspectratio}

2D バーコードモジュールの高さ/幅比率

### getColumns() {#getcolumns}

列数。

### getECIEncoding() {#geteciencoding}

拡張チャネル解釈識別子です。シンボル内のデータをエンコードする際に使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装はすべての既知の文字セットエンコーディングで構成されています。

### getEncodeMode() {#getencodemode}

Pdf417 エンコードモードを識別します。デフォルト値: Auto。

### getErrorLevel() {#geterrorlevel}

BarCode のエラー訂正レベル（level0 から level8）を取得します。level0 はエラー訂正情報がなく、level8 は最高のエラー訂正で、より大きな画像になります。

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを取得するために使用されます。MicroPdf417 のみで使用でき、916 と 917 をエンコードします。MicroPdf417 モードのデフォルト値: MacroCharacters.None。これらのサンプルは、MicroPdf417 でマクロ文字をエンコードする方法を示しています。

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

MacroPdf417 バーコードの受取人名（オプションフィールド）。MicroPDF417 バーコードの受取人名（Structured Append モード用のオプションフィールド）

### getMacroPdf417Checksum() {#getmacropdf417checksum}

MacroPdf417 バーコードのチェックサム（オプションフィールド）。MicroPDF417 バーコードのチェックサム（Structured Append モード用のオプションフィールド）。チェックサムフィールドは、CCITT-16 多項式 x^16 + x^12 + x^5 + 1 を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

拡張チャネル解釈識別子。Macro PDF417 のテキスト フィールドに適用されます。

### getMacroPdf417FileID() {#getmacropdf417fileid}

MacroPdf417 バーコードのファイル ID（必須フィールド）。MicroPDF417 バーコードのファイル ID（Structured Append モード用の必須フィールド）

### getMacroPdf417FileName() {#getmacropdf417filename}

MacroPdf417 バーコードのファイル名（オプションフィールド）。MicroPDF417 バーコードのファイル名（Structured Append モード用のオプションフィールド）

### getMacroPdf417FileSize() {#getmacropdf417filesize}

MacroPdf417 ファイルサイズ（オプションフィールド）。MicroPDF417 ファイルサイズ（Structured Append モード用のオプションフィールド）。ファイルサイズフィールドは、元のソースファイル全体のバイト数を示します。

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

MacroPdf417 バーコードのセグメント ID（必須フィールド）。0 から始まり、MacroSegmentsCount - 1 までです。MicroPDF417 バーコードのセグメント ID（Structured Append モード用の必須フィールド）

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

MacroPdf417 バーコードのセグメント数（オプションフィールド）。MicroPDF417 バーコードのセグメント数（Structured Append モード用のオプションフィールド）

### getMacroPdf417Sender() {#getmacropdf417sender}

MacroPdf417 バーコードの送信者名（オプションフィールド）。MicroPDF417 バーコードの送信者名（Structured Append モード用のオプションフィールド）

### getMacroPdf417Terminator() {#getmacropdf417terminator}

エンコーダーに、セグメントに Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用されます。Macro PDF417 にのみ適用されます。

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。MicroPDF417 バーコードのタイムスタンプ（構造化付加モード用のオプションフィールド）

### getPdf417CompactionMode() {#getpdf417compactionmode}

BarCode のコンパクション モードにおける Pdf417 シンボロジー タイプ。デフォルト値: Pdf417CompactionMode.AUTO。

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

拡張チャネル解釈識別子。シンボル内のデータをエンコードする際に使用される参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装はすべての既知の文字セットエンコーディングで構成されています。

### getPdf417EncodeMode() {#getpdf417encodemode}

Pdf417 エンコードモードを識別します。デフォルト値: Auto。

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

BarCode のエラー訂正レベル（level0 から level8）を取得します。level0 はエラー訂正情報がなく、level8 は最高のエラー訂正で、より大きな画像になります。

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードの宛先名を取得します。

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのチェックサムを取得します。

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

拡張チャネル解釈識別子。Macro PDF417 のテキスト フィールドに適用されます。

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Getsmacro Pdf417 バーコードのファイル ID を取得します。MacroPdf417 用に使用されます。

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのファイル名を取得します。

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 のファイルサイズを取得します。

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのセグメント ID を取得します。0 から MacroSegmentsCount - 1 までです。

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのセグメント数を取得します。

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードの送信者名を取得します。

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

エンコーダーに、セグメントに Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用されます。Macro PDF417 にのみ適用されます。

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのタイムスタンプを取得します。

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

BarCode の Pdf417 シンボロジー タイプが省略されているかどうか（スペース削減のため）。

### getRows() {#getrows}

行数。

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

DotCode 構造化付加モードバーコードの ID を識別します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は -1 です。

### getTruncate() {#gettruncate}

バーコードの Pdf417 シンボルタイプが切り詰められているか（スペース削減のため）。CompactPDF417 とも呼ばれます。このモードでは右側行インジケータと右側ストップパターンが削除されます。

### isCode128Emulation() {#iscode128emulation}

MicroPdf417 のみで使用でき、Code 128 エミュレーションモードをエンコードします。モード 908 と 909 では第2位置に FNC1 をエンコードでき、また 910 と 911 をエンコードでき、これらは認識された MicroPdf417 が Code 128 として解釈できることを示します。このサンプルは、第2位置に FNC1 を含む場合と含まない場合の Code 128 エミュレーションモードのエンコード方法を示しています。この方法により MicroPdf417 を Code 128 バーコードとしてデコードできます。

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 の「リンク」UCC/EAN-128 モードをエンコードします。MicroPdf417 および Pdf417 シンボルでは、EAN.UCC 以外の関連リニアコンポーネントへの 918 リンケージフラグをエンコードします。このサンプルは、GS1MicroPdf417 で\"Linked\" UCC/EAN-128 モードをエンコードし、MicroPdf417 と Pdf417 バーコードでリンケージフラグ（918）をエンコードする方法を示しています。

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するよう、リーダーに指示するために使用されます。

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

2D バーコードモジュールの高さ/幅比率

### setCode128Emulation() {#setcode128emulation}

MicroPdf417 のみで使用でき、Code 128 エミュレーションモードをエンコードします。モード 908 と 909 では第2位置に FNC1 をエンコードでき、また 910 と 911 をエンコードでき、これらは認識された MicroPdf417 が Code 128 として解釈できることを示します。このサンプルは、第2位置に FNC1 を含む場合と含まない場合の Code 128 エミュレーションモードのエンコード方法を示しています。この方法により MicroPdf417 を Code 128 バーコードとしてデコードできます。

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

列数。

### setECIEncoding() {#seteciencoding}

拡張チャネル解釈識別子です。シンボル内のデータをエンコードする際に使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装はすべての既知の文字セットエンコーディングで構成されています。

### setEncodeMode() {#setencodemode}

Pdf417 エンコードモードを識別します。デフォルト値: Auto。

### setErrorLevel(value) {#seterrorlevel}

バーコードの Pdf417 シンボルタイプのエラー訂正レベルを level0 から level8 の範囲で設定します。level0 はエラー訂正情報がないことを意味し、level8 は最高のエラー訂正で、画像が大きくなります。

| パラメータ | 説明 |
| --- | --- |
| 値 | バーコードの Pdf417 シンボルタイプのエラー訂正レベルは level0 から level8 の範囲で、level0 はエラー訂正情報がなく、level8 は最高のエラー訂正で、画像が大きくなります。 |

### setLinked() {#setlinked}

GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 の「リンク」UCC/EAN-128 モードをエンコードします。MicroPdf417 および Pdf417 シンボルでは、EAN.UCC 以外の関連リニアコンポーネントへの 918 リンケージフラグをエンコードします。このサンプルは、GS1MicroPdf417 で\"Linked\" UCC/EAN-128 モードをエンコードし、MicroPdf417 と Pdf417 バーコードでリンケージフラグ（918）をエンコードする方法を示しています。

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを取得するために使用されます。MicroPdf417 のみで使用でき、916 と 917 をエンコードします。MicroPdf417 モードのデフォルト値: MacroCharacters.None。これらのサンプルは、MicroPdf417 でマクロ文字をエンコードする方法を示しています。

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

MacroPdf417 バーコードの受取人名（オプションフィールド）。MicroPDF417 バーコードの受取人名（Structured Append モード用のオプションフィールド）

### setMacroPdf417Checksum() {#setmacropdf417checksum}

MacroPdf417 バーコードのチェックサム（オプションフィールド）。MicroPDF417 バーコードのチェックサム（Structured Append モード用のオプションフィールド）。チェックサムフィールドは、CCITT-16 多項式 x^16 + x^12 + x^5 + 1 を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

拡張チャネル解釈識別子。Macro PDF417 のテキスト フィールドに適用されます。

### setMacroPdf417FileID() {#setmacropdf417fileid}

MacroPdf417 バーコードのファイル ID（必須フィールド）。MicroPDF417 バーコードのファイル ID（Structured Append モード用の必須フィールド）

### setMacroPdf417FileName() {#setmacropdf417filename}

MacroPdf417 バーコードのファイル名（オプションフィールド）。MicroPDF417 バーコードのファイル名（Structured Append モード用のオプションフィールド）

### setMacroPdf417FileSize() {#setmacropdf417filesize}

MacroPdf417 ファイルサイズ（オプションフィールド）。MicroPDF417 ファイルサイズ（Structured Append モード用のオプションフィールド）。ファイルサイズフィールドは、元のソースファイル全体のバイト数を示します。

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

MacroPdf417 バーコードのセグメント ID（必須フィールド）。0 から始まり、MacroSegmentsCount - 1 までです。MicroPDF417 バーコードのセグメント ID（Structured Append モード用の必須フィールド）

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

MacroPdf417 バーコードのセグメント数（オプションフィールド）。MicroPDF417 バーコードのセグメント数（Structured Append モード用のオプションフィールド）

### setMacroPdf417Sender() {#setmacropdf417sender}

MacroPdf417 バーコードの送信者名（オプションフィールド）。MicroPDF417 バーコードの送信者名（Structured Append モード用のオプションフィールド）

### setMacroPdf417Terminator() {#setmacropdf417terminator}

エンコーダーに、セグメントに Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用されます。Macro PDF417 にのみ適用されます。

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。MicroPDF417 バーコードのタイムスタンプ（構造化付加モード用のオプションフィールド）

### setPdf417CompactionMode() {#setpdf417compactionmode}

BarCode のコンパクション モードにおける Pdf417 シンボロジー タイプ。デフォルト値: Pdf417CompactionMode.AUTO。

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

拡張チャネル解釈識別子。シンボル内のデータをエンコードする際に使用される参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装はすべての既知の文字セットエンコーディングで構成されています。

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Pdf417 エンコードモードを識別します。デフォルト値: Auto。

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

バーコードの Pdf417 シンボルタイプのエラー訂正レベルを level0 から level8 の範囲で設定します。level0 はエラー訂正情報がないことを意味し、level8 は最高のエラー訂正で、画像が大きくなります。

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードの受取人名を設定します。

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのチェックサムを設定します。

| パラメータ | 説明 |
| --- | --- |
| 値 | チェックサムフィールドには、CCITT-16 多項式を使用した 16 ビット（2 バイト）CRC チェックサムの値が含まれます。 |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

拡張チャネル解釈識別子。Macro PDF417 のテキスト フィールドに適用されます。

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのファイル ID を設定します。MacroPdf417 用です。

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのファイル名を設定します。

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 のファイルサイズを設定します。

| パラメータ | 説明 |
| --- | --- |
| 値 | ファイルサイズフィールドには、ソースファイル全体のバイト数が含まれます。 |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのセグメント ID を設定します。0 から始まり、MacroSegmentsCount - 1 までです。

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのセグメント数を設定します。

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードの送信者名を設定します。

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

エンコーダーに、セグメントに Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用されます。Macro PDF417 にのみ適用されます。

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

マクロ Pdf417 バーコードのタイムスタンプを設定します。

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

BarCode の Pdf417 シンボロジー タイプが省略されているかどうか（スペース削減のため）。

### setReaderInitialization(value) {#setreaderinitialization}

シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するよう、リーダーに指示するために使用されます。

| パラメータ | 説明 |
| --- | --- |
| 値 |  |

### setRows() {#setrows}

行数。

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

DotCode 構造化付加モードバーコードの ID を識別します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は -1 です。

### setTruncate() {#settruncate}

バーコードの Pdf417 シンボルタイプが切り詰められているか（スペース削減のため）。CompactPDF417 とも呼ばれます。このモードでは右側行インジケータと右側ストップパターンが削除されます。

### toString() {#tostring}

この Pdf417Parameters の人間が読みやすい文字列表現を返します。

**Returns:** A string that represents this Pdf417Parameters.
