---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "QualitySettings は認識品質と速度を手動で構成できるようにします。"
type: docs
weight: 860
url: /ja/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings は認識品質と速度を手動で構成できるようにします。組み込みプリセット（HighPerformance、NormalQuality、HighQuality、MaxBarCodes）を使用してすばやく設定することも、個別のオプションを手動で構成することもできます。QualitySettings のデフォルト値は NormalQuality です。

```js
new QualitySettings()
```

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

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | HighPerformance 認識品質プリセット。このモードでは高品質のバーコードがうまく認識されます。 |
| [getHighQuality()](#gethighquality) *(static)* | HighQuality 認識品質プリセット。このプリセットは低品質のバーコード用に開発されています。 |
| [getMaxQuality()](#getmaxquality) *(static)* | MaxQuality 認識品質プリセット。このプリセットは、たとえ不正確なバーコードであっても、可能な限りすべてのバーコードを認識できるように開発されています。 |
| [getNormalQuality()](#getnormalquality) *(static)* | NormalQuality 認識品質プリセット。ほとんどのバーコードに適しています。 |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | エンジンがチェックサムや値が正しくないバーコードを認識できるようにします。このモードは破損したバーコードの認識に使用できます。 |
| [getBarcodeQuality()](#getbarcodequality) | 選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低いバーコード要素 r |
| [getComplexBackground()](#getcomplexbackground) | カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。 |
| [getDeconvolution()](#getdeconvolution) | 画像劣化のレベルを定義するデコンボリューション（画像復元）モードです。もともとデコンボリューションは機能です。 |
| [getInverseImage()](#getinverseimage) | 反転色（輝度）の画像上でバーコードの追加認識を有効または無効にするモード。 |
| [getMinimalXDimension()](#getminimalxdimension) | UseMinimalXDimension と併用される XDimension の最小サイズ（ピクセル単位）。 |
| [getXDimension()](#getxdimension) | バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大）を設定する認識モード。 |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | エンジンがチェックサムや値が正しくないバーコードを認識できるようにします。このモードは破損したバーコードの認識に使用できます。 |
| [setBarcodeQuality(value)](#setbarcodequality) | 選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低いバーコード要素 r |
| [setComplexBackground(value)](#setcomplexbackground) | カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。 |
| [setDeconvolution(value)](#setdeconvolution) | 画像劣化のレベルを定義するデコンボリューション（画像復元）モードです。もともとデコンボリューションは機能です。 |
| [setInverseImage(value)](#setinverseimage) | 反転色（輝度）の画像上でバーコードの追加認識を有効または無効にするモード。 |
| [setMinimalXDimension(value)](#setminimalxdimension) | UseMinimalXDimension と併用される XDimension の最小サイズ（ピクセル単位）。 |
| [setXDimension(value)](#setxdimension) | バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大）を設定する認識モード。 |

### getHighPerformance() (static) {#gethighperformance}

HighPerformance 認識品質プリセット。このモードでは高品質のバーコードがうまく認識されます。

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

HighQuality 認識品質プリセット。このプリセットは低品質のバーコード用に開発されています。

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

MaxQuality 認識品質プリセット。 このプリセットは、誤ったバーコードを含むすべての可能なバーコードを認識できるように開発されています。 このサンプルは MaxQuality モードの使用方法を示しています。 reader = new BarCodeReader(\"test.png\"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } 値: MaxQuality 認識品質プリセット。

### getNormalQuality() (static) {#getnormalquality}

NormalQuality 認識品質プリセット。ほとんどのバーコードに適しています。

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

エンジンがチェックサムまたは値が正しくないバーコードを認識できるようにします。このモードは、テキストが正しくない損傷したバーコードの認識にも使用できます。

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低いバーコード要素は、より多くの高度なメソッドを必要とし、認識速度が遅くなります。

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

デコンボリューション（画像復元）モードは、画像の劣化レベルを定義します。デコンボリューションはもともと、カメラで画像を取得する際にぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を損なう関数を検出できないため、シャープや数学的形態学など、よく知られた関数をチェックする必要があります。

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

反転色（輝度）の画像上でバーコードの追加認識を有効または無効にするモード。

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

UseMinimalXDimension と併用される XDimension の最小サイズ（ピクセル単位）。

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大）を設定する認識モード。

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

エンジンがチェックサムまたは値が正しくないバーコードを認識できるようにします。このモードは、テキストが正しくない損傷したバーコードの認識にも使用できます。

| パラメータ | 説明 |
| --- | --- |
| 値 | エンジンが不正確なバーコードを認識できるようにします。 |

### setBarcodeQuality(value) {#setbarcodequality}

選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低いバーコード要素は、より多くの高度なメソッドを必要とし、認識速度が遅くなります。

| パラメータ | 説明 |
| --- | --- |
| 値 | 選択された品質でバーコード要素を認識するメソッドを有効にするモード。 |

### setComplexBackground(value) {#setcomplexbackground}

カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。

| パラメータ | 説明 |
| --- | --- |
| 値 | カラー画像上のカラーバーコードの追加認識。 |

### setDeconvolution(value) {#setdeconvolution}

デコンボリューション（画像復元）モードは、画像の劣化レベルを定義します。デコンボリューションはもともと、カメラで画像を取得する際にぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を損なう関数を検出できないため、シャープや数学的形態学など、よく知られた関数をチェックする必要があります。

| パラメータ | 説明 |
| --- | --- |
| 値 | 画像の劣化レベルを定義するデコンボリューションモード。 |

### setInverseImage(value) {#setinverseimage}

反転色（輝度）の画像上でバーコードの追加認識を有効または無効にするモード。

| パラメータ | 説明 |
| --- | --- |
| 値 | 逆色画像上のバーコードの追加認識 |

### setMinimalXDimension(value) {#setminimalxdimension}

UseMinimalXDimension と併用される XDimension の最小サイズ（ピクセル単位）。

| パラメータ | 説明 |
| --- | --- |
| 値 | UseMinimalXDimension と併用される XDimension の最小サイズ（ピクセル単位）。 |

### setXDimension(value) {#setxdimension}

バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大）を設定する認識モード。

| パラメータ | 説明 |
| --- | --- |
| 値 | （1 から無限大）バーコードの最小要素：マトリックスセルまたはバー。 |
