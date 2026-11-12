---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "BarCodeReader は、1つまたは複数のバーコードを含む可能性のある画像をカプセル化し、バーコードを検出するために ReadBarCodes 操作を実行できます。"
type: docs
weight: 90
url: /ja/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader は、1つまたは複数のバーコードを含む可能性のある画像をカプセル化し、バーコードを検出するために ReadBarCodes 操作を実行できます。

```js
new BarCodeReader(image, areas, decodeTypes)
```

BarCodeReader の新しいインスタンスを初期化します

| パラメータ | 説明 |
| --- | --- |
| 画像 | Base64 文字列または画像へのパスとしてエンコードされます |
| 領域 | Rectangle 型のオブジェクトの配列 |
| デコードタイプ | DecodeType によるオブジェクトの配列 |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | 指定された xml ファイルに BarCode プロパティをエクスポートします |
| [containsAny()](#containsany) | 指定されたデコードタイプのいずれかが含まれているかどうかを判定します |
| [exportToXml(xmlFile)](#exporttoxml) | 指定された xml ファイルに BarCode プロパティをエクスポートします |
| [getBarCodeReadType()](#getbarcodereadtype) | 入力バーコードデコードのデコードタイプを取得します |
| [getBarcodeSettings()](#getbarcodesettings) | 主な BarCode デコードパラメータです。認識されたデータに影響を与えるパラメータが含まれます。 |
| [getFoundBarCodes()](#getfoundbarcodes) | 認識された BarCodeResult 配列を取得します |
| [getFoundCount()](#getfoundcount) | 認識されたバーコードの数を取得します |
| [getQualitySettings()](#getqualitysettings) | QualitySettings は認識品質と速度を手動で構成できるようにします。QualitySettings をすぐに設定するには、em を使用します。 |
| [getTimeout()](#gettimeout) | 認識プロセスのタイムアウト（ミリ秒）を取得します。 |
| [readBarCodes()](#readbarcodes) | 画像から BarCodeResult を読み取ります。 |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | 認識用のビットマップ画像と領域を設定します。ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | 認識用に SingleDecodeType 型配列を設定します。readBarCodes() メソッドの前に呼び出す必要があります。 |
| [setQualitySettings()](#setqualitysettings) | QualitySettings は認識品質と速度を手動で構成できるようにします。QualitySettings をすぐに設定するには、em を使用します。 |
| [setTimeout(value)](#settimeout) | 認識プロセスのタイムアウト（ミリ秒）を設定します。 |

### importFromXml(xmlFile) (static) {#importfromxml}

指定された xml ファイルに BarCode プロパティをエクスポートします

| パラメータ | 説明 |
| --- | --- |
| xmlFile | ファイル名 |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

指定されたデコードタイプのいずれかが含まれているかどうかを判定します

| パラメータ | 説明 |
| --- | --- |
| ...decodeTypes | 検証するタイプ。 |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

指定された xml ファイルに BarCode プロパティをエクスポートします

| パラメータ | 説明 |
| --- | --- |
| xmlFile | ファイル名 |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

入力バーコードデコードのデコードタイプを取得します

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

主な BarCode デコードパラメータです。認識されたデータに影響を与えるパラメータが含まれます。

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

認識された BarCodeResult 配列を取得します

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

認識されたバーコードの数を取得します

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

QualitySettings は認識品質と速度を手動で構成できるようにします。組み込みプリセット（HighPerformance、NormalQuality、HighQuality、MaxBarCodes）を使用してすばやく設定することも、個別のオプションを手動で構成することもできます。QualitySettings のデフォルト値は NormalQuality です。

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

認識プロセスのタイムアウト（ミリ秒）を取得します。

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

画像から BarCodeResult を読み取ります。

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

認識用のビットマップ画像と領域を設定します。ReadBarCodes() メソッドの前に呼び出す必要があります。

| パラメータ | 説明 |
| --- | --- |
| imageResource | 認識用の画像。 |
| 領域 | 認識用の領域リスト |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

認識用に SingleDecodeType 型配列を設定します。readBarCodes() メソッドの前に呼び出す必要があります。

| パラメータ | 説明 |
| --- | --- |
| types | 読み取るための SingleDecodeType 型配列。 |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

QualitySettings は認識品質と速度を手動で構成できるようにします。組み込みプリセット（HighPerformance、NormalQuality、HighQuality、MaxBarCodes）を使用してすばやく設定することも、個別のオプションを手動で構成することもできます。QualitySettings のデフォルト値は NormalQuality です。

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setTimeout(value) {#settimeout}

認識プロセスのタイムアウト（ミリ秒）を設定します。

| パラメータ | 説明 |
| --- | --- |
| 値 | タイムアウト。 |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```
