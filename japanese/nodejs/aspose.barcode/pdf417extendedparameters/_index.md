---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "認識されたバーコードの MacroPdf417 メタデータ情報を保存します。"
type: docs
weight: 760
url: /ja/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

認識されたバーコードの MacroPdf417 メタデータ情報を保存します。

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された Pdf417ExtendedParameters 値と等しいかどうかを示す値を返します。 |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Macro PDF417 の受取人名（オプション）。 |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Macro PDF417 のチェックサム（オプション）。 |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | バーコードのファイル ID を取得します。MacroPdf417 でのみ利用可能です。値: MacroPdf417 のファイル ID です。 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Macro PDF417 ファイル名 (オプション)。 |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Macro PDF417 ファイルサイズ (オプション)。 |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | バーコードのセグメント ID を取得します。MacroPdf417 でのみ利用可能です。Value: バーコードのセグメント ID。 |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | macro pdf417 バーコードのセグメント数を取得します。デフォルト値は -1 です。Value: セグメント数。 |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Macro PDF417 送信者名 (オプション)。 |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | リーダーにシンボル内に含まれるデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。 |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Macro PDF417 タイムスタンプ (オプション)。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [isCode128Emulation()](#iscode128emulation) | MicroPdf417 バーコードが 908、909、910、または 911 の Code 128 エミュレーションコードワードでエンコードされていることを示すフラグ。 |
| [isLinked()](#islinked) | バーコードが 1D バーコードにリンクされる必要があることを示すフラグ。Value: Linkage flag |
| [isReaderInitialization()](#isreaderinitialization) | リーダーにシンボル内に含まれるデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。 |
| [toString()](#tostring) | この Pdf417ExtendedParameters の人間が読みやすい文字列表現を返します。 |

### equals(obj) {#equals}

このインスタンスが指定された Pdf417ExtendedParameters 値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するための System.Object の値です。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Macro PDF417 の受取人名（オプション）。

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Macro PDF417 のチェックサム（オプション）。

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

バーコードのファイル ID を取得します。MacroPdf417 でのみ利用可能です。値: MacroPdf417 のファイル ID です。

### getMacroPdf417FileName() {#getmacropdf417filename}

Macro PDF417 ファイル名 (オプション)。

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Macro PDF417 ファイルサイズ (オプション)。

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

バーコードのセグメント ID を取得します。MacroPdf417 でのみ利用可能です。Value: バーコードのセグメント ID。

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

macro pdf417 バーコードのセグメント数を取得します。デフォルト値は -1 です。Value: セグメント数。

### getMacroPdf417Sender() {#getmacropdf417sender}

Macro PDF417 送信者名 (オプション)。

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

リーダーにシンボル内に含まれるデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Macro PDF417 タイムスタンプ (オプション)。

**Returns:** Time stamp.

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

MicroPdf417 バーコードが 908、909、910、または 911 の Code 128 エミュレーションコードワードでエンコードされていることを示すフラグ。

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

バーコードが 1D バーコードにリンクされる必要があることを示すフラグ。Value: Linkage flag

### isReaderInitialization() {#isreaderinitialization}

リーダーにシンボル内に含まれるデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。

**Returns:** Reader initialization flag

### toString() {#tostring}

この Pdf417ExtendedParameters の人間が読みやすい文字列表現を返します。

**Returns:** A string that represents this Pdf417ExtendedParameters.
