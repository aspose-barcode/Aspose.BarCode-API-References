---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "バーコード画像生成パラメータ。"
type: docs
weight: 160
url: /ja/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

バーコード画像生成パラメータ。

```js
new BaseGenerationParameters()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | 自動サイズモードのさまざまなタイプを指定します。デフォルト値: AutoSizeMode.NONE。 |
| [getBackColor()](#getbackcolor) | バーコード画像の背景色。デフォルト値: #FFFFFF |
| [getBarcode()](#getbarcode) | すべてのバーコードプロパティを含む BarcodeParameters を取得します。 |
| [getBorder()](#getborder) | バーコード境界のすべての構成プロパティを含む BorderParameters を取得します。 |
| [getCaptionAbove()](#getcaptionabove) | BarCode 画像の上部のキャプション。CaptionParameters を参照してください。 |
| [getCaptionBelow()](#getcaptionbelow) | BarCode 画像の下部のキャプション。CaptionParameters を参照してください。 |
| [getImage()](#getimage) | 画像パラメータ。ImageParameters を参照してください。 |
| [getImageHeight()](#getimageheight) | AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合の BarCode 画像の高さ。 |
| [getImageWidth()](#getimagewidth) | AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合の BarCode 画像の幅。 |
| [getResolution()](#getresolution) | BarCode 画像の解像度を取得します。両方の次元に対して 1 つの値です。デフォルト値: 96 dpi。Resolution パラメータ |
| [getRotationAngle()](#getrotationangle) | BarCode 画像の回転角度（度単位）。例: RotationAngle = 0 または RotationAngle = 360 は回転なしを意味します。If Ro |
| [getUseAntiAlias()](#getuseantialias) | 画像をレンダリングする際にアンチエイリアスモードが使用されているかどうかを示す値を取得します |
| [setAutoSizeMode()](#setautosizemode) | 自動サイズモードのさまざまなタイプを指定します。デフォルト値: AutoSizeMode.NONE。 |
| [setBackColor()](#setbackcolor) | バーコード画像の背景色。デフォルト値: #FFFFFF |
| [setImageHeight()](#setimageheight) | AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合の BarCode 画像の高さ。 |
| [setImageWidth()](#setimagewidth) | AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合の BarCode 画像の幅。 |
| [setResolution()](#setresolution) | BarCode 画像の解像度を設定します。両方の次元に対して 1 つの値です。デフォルト値: 96 dpi。Resolution パラメータ |
| [setRotationAngle()](#setrotationangle) | BarCode 画像の回転角度（度単位）。例: RotationAngle = 0 または RotationAngle = 360 は回転なしを意味します。If Ro |
| [setUseAntiAlias()](#setuseantialias) | 画像をレンダリングする際にアンチエイリアスモードが使用されているかどうかを示す値を設定します。 |

### getAutoSizeMode() {#getautosizemode}

自動サイズモードのさまざまなタイプを指定します。デフォルト値: AutoSizeMode.NONE。

### getBackColor() {#getbackcolor}

バーコード画像の背景色。デフォルト値: #FFFFFF

### getBarcode() {#getbarcode}

すべてのバーコードプロパティを含む BarcodeParameters を取得します。

### getBorder() {#getborder}

バーコード境界のすべての構成プロパティを含む BorderParameters を取得します。

### getCaptionAbove() {#getcaptionabove}

BarCode 画像の上部のキャプション。CaptionParameters を参照してください。

### getCaptionBelow() {#getcaptionbelow}

BarCode 画像の下部のキャプション。CaptionParameters を参照してください。

### getImage() {#getimage}

画像パラメータ。ImageParameters を参照してください。

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合の BarCode 画像の高さ。

### getImageWidth() {#getimagewidth}

AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合の BarCode 画像の幅。

### getResolution() {#getresolution}

BarCode 画像の解像度を取得します。両方の次元に対して同じ値です。デフォルト値: 96 dpi。Resolution パラメーターの値は 0 以下です。

### getRotationAngle() {#getrotationangle}

BarCode 画像の回転角度を度単位で指定します。例: RotationAngle = 0 または RotationAngle = 360 は回転なしを意味します。RotationAngle が 90、180、270、または 0 でない場合、スキャナーが画像を読み取る難易度が上がる可能性があります。デフォルト値: 0。

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

画像をレンダリングする際にアンチエイリアスモードが使用されているかどうかを示す値を取得します

### setAutoSizeMode() {#setautosizemode}

自動サイズモードのさまざまなタイプを指定します。デフォルト値: AutoSizeMode.NONE。

### setBackColor() {#setbackcolor}

バーコード画像の背景色。デフォルト値: #FFFFFF

### setImageHeight() {#setimageheight}

AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合の BarCode 画像の高さ。

### setImageWidth() {#setimagewidth}

AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合の BarCode 画像の幅。

### setResolution() {#setresolution}

BarCode 画像の解像度を設定します。両方の次元に対して同じ値です。デフォルト値: 96 dpi。Resolution パラメーターの値は 0 以下です。

### setRotationAngle() {#setrotationangle}

BarCode 画像の回転角度を度単位で指定します。例: RotationAngle = 0 または RotationAngle = 360 は回転なしを意味します。RotationAngle が 90、180、270、または 0 でない場合、スキャナーが画像を読み取る難易度が上がる可能性があります。デフォルト値: 0。

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

画像をレンダリングする際にアンチエイリアスモードが使用されているかどうかを示す値を設定します。
