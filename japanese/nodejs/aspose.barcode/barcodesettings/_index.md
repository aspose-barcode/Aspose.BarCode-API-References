---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "メインの BarCode デコードパラメータです。"
type: docs
weight: 150
url: /ja/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

主な BarCode デコードパラメータです。認識されたデータに影響を与えるパラメータが含まれます。

```js
new BarcodeSettings(settings)
```

BarcodeSettings コピーコンストラクタ

| パラメータ | 説明 |
| --- | --- |
| 設定 | データのソース |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | AustraliaPost のデコードパラメータを取得します |
| [getChecksumValidation()](#getchecksumvalidation) | 1D および郵便バーコードの認識時にチェックサム検証を有効にします。デフォルトでは該当シンボルは Yes とみなされます。 |
| [getDetectEncoding()](#getdetectencoding) | Unicode コードセットのコードテキストエンコーディングをエンジンが検出するよう強制するフラグです。デフォルト値は true です。 |
| [getStripFNC()](#getstripfnc) | コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。 |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | 認識用に明示的に指定されたバーコードタイプのみを返します。有効にすると、他の互換性のあるバーコードは除外されます。 |
| [setChecksumValidation(value)](#setchecksumvalidation) | 1D および郵便バーコードの認識時にチェックサム検証を有効にします。デフォルトでは該当シンボルは Yes とみなされます。 |
| [setDetectEncoding()](#setdetectencoding) | Unicode コードセットのコードテキストエンコーディングをエンジンが検出するよう強制するフラグです。デフォルト値は true です。 |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | 認識用に明示的に指定されたバーコードタイプのみを返します。有効にすると、他の互換性のあるバーコードは除外されます。 |
| [setStripFNC(value)](#setstripfnc) | コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。 |

### getAustraliaPost() {#getaustraliapost}

AustraliaPost のデコードパラメータを取得します

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

1D および郵便バーコードの認識時にチェックサム検証を有効にします。デフォルトでは、チェックサムが必須のシンボルは Yes とみなされ、チェックサムが可能なだけのシンボルは No とみなされます。チェックサムが使用されないシンボル: Codabar、PatchCode、Pharmacode、DataLogic2of5。チェックサムが可能なシンボル: Code39 Standard/Extended、Standard2of5、Interleaved2of5、ItalianPost25、Matrix2of5、MSI、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN。チェックサムが常に使用されるシンボル: その他のシンボル。

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

Unicode コードセットのコードテキストエンコーディングをエンジンが検出するよう強制するフラグです。デフォルト値は true です。

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

認識用に明示的に指定されたバーコードタイプのみを返します。有効にすると、他の互換または同等のタイプの認識されたバーコードは除外されます。デフォルト値は false です。Example: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

1D および郵便バーコードの認識時にチェックサム検証を有効にします。デフォルトでは、チェックサムが必須のシンボルは Yes とみなされ、チェックサムが可能なだけのシンボルは No とみなされます。チェックサムが使用されないシンボル: Codabar、PatchCode、Pharmacode、DataLogic2of5。チェックサムが可能なシンボル: Code39 Standard/Extended、Standard2of5、Interleaved2of5、ItalianPost25、Matrix2of5、MSI、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN。チェックサムが常に使用されるシンボル: その他のシンボル。

| パラメータ | 説明 |
| --- | --- |
| 値 | 1D および郵便バーコードの認識時にチェックサム検証を有効にします。 |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

Unicode コードセットのコードテキストエンコーディングをエンジンが検出するよう強制するフラグです。デフォルト値は true です。

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

認識用に明示的に指定されたバーコードタイプのみを返します。有効にすると、他の互換または同等のタイプの認識されたバーコードは除外されます。デフォルト値は false です。Example: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。

| パラメータ | 説明 |
| --- | --- |
| 値 | コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。 |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
