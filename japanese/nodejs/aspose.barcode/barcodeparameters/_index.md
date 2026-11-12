---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "バーコード生成パラメータ。"
type: docs
weight: 140
url: /ja/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

バーコード生成パラメータ。

```js
new BarcodeParameters()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | AustralianPost バーコードパラメータ。 |
| [getAztec()](#getaztec) | Aztec パラメータ。 |
| [getBarColor()](#getbarcolor) | バーの色。 |
| [getBarHeight()](#getbarheight) | 1D バーコードのバーの高さ（単位値）。AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMo に設定されている場合は無視されます。 |
| [getBarWidthReduction()](#getbarwidthreduction) | 印刷時のインク拡散を補正するために使用されるバーの縮小値を取得します。 |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Code128 および GS1Code128 バーコードの人間が読みやすいテキストにチェックサム桁を常に表示します。 |
| [getCodabar()](#getcodabar) | Codabar パラメータ。 |
| [getCodablock()](#getcodablock) | Codablock パラメータ。 |
| [getCode16K()](#getcode16k) | Code16K パラメータ。 |
| [getCode128()](#getcode128) | Code128 パラメータ。 |
| [getCodeTextParameters()](#getcodetextparameters) | Codetext パラメータ。 |
| [getCoupon()](#getcoupon) | クーポンパラメータ。UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon に使用されます。 |
| [getDataBar()](#getdatabar) | Databar パラメータ。 |
| [getDataMatrix()](#getdatamatrix) | DataMatrix パラメータ。 |
| [getDotCode()](#getdotcode) | DotCode パラメータ。 |
| [getEnableEscape()](#getenableescape) | CodeText プロパティで文字 "\\" をエスケープ文字として解釈するかどうかを示します。Pdf417、DataMatrix、C で使用されます。 |
| [getFilledBars()](#getfilledbars) | バーが塗りつぶされているかどうかを示す値を取得します。1D バーコードのみ対象です。デフォルト値: true。 |
| [getGS1CompositeBar()](#getgs1compositebar) | GS1 Composite Bar のパラメータ。このサンプルは GS1 Composite Bar 画像の作成と保存方法を示します。1D コードテキストに注意してください |
| [getHanXin()](#gethanxin) | HanXin パラメータ。 |
| [getITF()](#getitf) | ITF パラメータ。 |
| [getMaxiCode()](#getmaxicode) | MaxiCode パラメータ。 |
| [getPadding()](#getpadding) | バーコードの余白。デフォルト値: 5pt 5pt 5pt 5pt。 |
| [getPatchCode()](#getpatchcode) | PatchCode パラメータ。 |
| [getPdf417()](#getpdf417) | PDF417 パラメータ。 |
| [getPostal()](#getpostal) | 郵便パラメータ。Postnet、Planet に使用されます。 |
| [getQR()](#getqr) | QR パラメータ。 |
| [getSupplement()](#getsupplement) | サプリメント パラメータ。Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN に使用されます。 |
| [getWideNarrowRatio()](#getwidenarrowratio) | 太いバーと細いバーの比率。デフォルト値: 3、つまり太いバーは細いバーの 3 倍の幅です。ITF で使用されます、 |
| [getXDimension()](#getxdimension) | x-dimension はバーコードのバーまたはスペースの単位の最小幅です。これを増やすと全体のバーコードが拡大します i |
| [isChecksumEnabled()](#ischecksumenabled) | 1D バーコード生成時にチェックサムを有効にします。チェックサムが必須のシンボルではデフォルトで Yes とみなされます、N |
| [setBarColor(value)](#setbarcolor) | バーの色。 |
| [setBarHeight()](#setbarheight) | 1D バーコードのバーの高さ（単位値）。AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMo に設定されている場合は無視されます。 |
| [setBarWidthReduction()](#setbarwidthreduction) | 印刷時のインク拡散を補正するために使用されるバーの縮小値を設定します。 |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Code128 および GS1Code128 バーコードの人間が読みやすいテキストにチェックサム桁を常に表示します。 |
| [setChecksumEnabled()](#setchecksumenabled) | 1D バーコード生成時にチェックサムを有効にします。チェックサムが必須のシンボルではデフォルトで Yes とみなされます、N |
| [setEnableEscape()](#setenableescape) | CodeText プロパティで文字 "\\" をエスケープ文字として解釈するかどうかを示します。Pdf417、DataMatrix、C で使用されます。 |
| [setFilledBars()](#setfilledbars) | バーが塗りつぶされているかどうかを示す値を設定します。1D バーコードのみ対象です。デフォルト値: true。 |
| [setGS1CompositeBar()](#setgs1compositebar) | GS1 Composite Bar のパラメータ。このサンプルは GS1 Composite Bar 画像の作成と保存方法を示します。1D コードテキストに注意してください |
| [setPadding()](#setpadding) | バーコードの余白。デフォルト値: 5pt 5pt 5pt 5pt。 |
| [setWideNarrowRatio()](#setwidenarrowratio) | 太いバーと細いバーの比率。デフォルト値: 3、つまり太いバーは細いバーの 3 倍の幅です。ITF、P で使用されます。 |
| [setXDimension()](#setxdimension) | x-dimension はバーコードのバーまたはスペースの単位の最小幅です。これを増やすと全体のバーコードが拡大します i |

### getAustralianPost() {#getaustralianpost}

AustralianPost バーコードパラメータ。

### getAztec() {#getaztec}

Aztec パラメータ。

### getBarColor() {#getbarcolor}

バーの色。

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

1D バーコードのバーの高さ（単位値）。AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合は無視されます。

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

印刷時のインク拡散を補正するために使用されるバーの縮小値を取得します。

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Code128 および GS1Code128 バーコードの人間が読みやすいテキストにチェックサム桁を常に表示します。

### getCodabar() {#getcodabar}

Codabar パラメータ。

### getCodablock() {#getcodablock}

Codablock パラメータ。

### getCode16K() {#getcode16k}

Code16K パラメータ。

### getCode128() {#getcode128}

Code128 パラメータ。

### getCodeTextParameters() {#getcodetextparameters}

Codetext パラメータ。

### getCoupon() {#getcoupon}

クーポンパラメータ。UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon に使用されます。

### getDataBar() {#getdatabar}

Databar パラメータ。

### getDataMatrix() {#getdatamatrix}

DataMatrix パラメータ。

### getDotCode() {#getdotcode}

DotCode パラメータ。

### getEnableEscape() {#getenableescape}

CodeText プロパティで文字 "\\" をエスケープ文字として解釈するかどうかを示します。Pdf417、DataMatrix、Code128 でのみ使用されます。EnableEscape が true の場合、"\\" は特別なエスケープ文字として解釈されます。そうでない場合、"\\" は通常の文字として扱われます。Aspose.BarCode は ASCII 制御コード文字の十進数コードやニーモニックの入力をサポートします。例として、\\013 と \\\\CR は CR を表します。

### getFilledBars() {#getfilledbars}

バーが塗りつぶされているかどうかを示す値を取得します。1D バーコードのみ対象です。デフォルト値: true。

### getGS1CompositeBar() {#getgs1compositebar}

GS1 Composite Bar のパラメータ。このサンプルは GS1 Composite Bar 画像の作成と保存方法を示します。1D コードテキストと 2D コードテキストは '/' 記号で区切られます。

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
///
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
///
generator.save("test.png", BarcodeImageFormat.PNG);
```

### getHanXin() {#gethanxin}

HanXin パラメータ。

### getITF() {#getitf}

ITF パラメータ。

### getMaxiCode() {#getmaxicode}

MaxiCode パラメータ。

### getPadding() {#getpadding}

バーコードの余白。デフォルト値: 5pt 5pt 5pt 5pt。

### getPatchCode() {#getpatchcode}

PatchCode パラメータ。

### getPdf417() {#getpdf417}

PDF417 パラメータ。

### getPostal() {#getpostal}

郵便パラメータ。Postnet、Planet に使用されます。

### getQR() {#getqr}

QR パラメータ。

### getSupplement() {#getsupplement}

サプリメント パラメータ。Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN に使用されます。

### getWideNarrowRatio() {#getwidenarrowratio}

太いバーと細いバーの比率。デフォルト値: 3、つまり太いバーは細いバーの 3 倍の幅です。ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39Extended、Code39Standard で使用されます。WideNarrowRatio パラメータの値は 0 以下です。

### getXDimension() {#getxdimension}

x-dimension はバーコードのバーまたはスペースの単位の最小幅です。これを増やすと全体のバーコード画像の幅が拡大します。AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合は無視されます。

### isChecksumEnabled() {#ischecksumenabled}

1Dバーコードの生成時にチェックサムを有効にします。デフォルトは、チェックサムが必須のシンボルでは Yes とみなされ、チェックサムがオプションの場合は No とみなされます。チェックサムが使用可能なシンボル: Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN、Codabar。チェックサムが常に使用されるシンボル: その他のシンボル

### setBarColor(value) {#setbarcolor}

バーの色。

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | String | バーの色のデフォルト値: #000000。 |

### setBarHeight() {#setbarheight}

1D バーコードのバーの高さ（単位値）。AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合は無視されます。

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

印刷時のインク拡散を補正するために使用されるバーの縮小値を設定します。

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Code128 および GS1Code128 バーコードの人間が読みやすいテキストにチェックサム桁を常に表示します。

### setChecksumEnabled() {#setchecksumenabled}

1Dバーコードの生成時にチェックサムを有効にします。デフォルトは、チェックサムが必須のシンボルでは Yes とみなされ、チェックサムがオプションの場合は No とみなされます。チェックサムが使用可能なシンボル: Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN、Codabar。チェックサムが常に使用されるシンボル: その他のシンボル

### setEnableEscape() {#setenableescape}

CodeText プロパティで文字 "\" をエスケープ文字として扱うかどうかを示します。Pdf417、DataMatrix、Code128 のみで使用されます。EnableEscape が true の場合、"\" は特別なエスケープ文字として解釈されます。そうでない場合、"\" は通常の文字として扱われます。Aspose.BarCode は ASCII 制御コード文字の10進数コードとニーモニックをサポートしています。例として、\013 と \\CR は CR を表します。

### setFilledBars() {#setfilledbars}

バーが塗りつぶされているかどうかを示す値を設定します。1D バーコードのみ対象です。デフォルト値: true。

### setGS1CompositeBar() {#setgs1compositebar}

GS1 Composite Bar のパラメータ。このサンプルは GS1 Composite Bar 画像の作成と保存方法を示します。1D コードテキストと 2D コードテキストは '/' 記号で区切られます。

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);

// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);

generator.save("test.png", BarcodeImageFormat.PNG);
```

### setPadding() {#setpadding}

バーコードの余白。デフォルト値: 5pt 5pt 5pt 5pt。

### setWideNarrowRatio() {#setwidenarrowratio}

太棒と細棒の比率。デフォルト値: 3、つまり太棒は細棒の 3 倍の幅です。ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39Extended、Code39Standard で使用されます。WideNarrowRatio パラメータの値は 0 以下である必要があります。

### setXDimension() {#setxdimension}

x-dimension はバーコードのバーまたはスペースの単位の最小幅です。これを増やすと全体のバーコード画像の幅が拡大します。AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合は無視されます。

**Throws:** BarcodeException
