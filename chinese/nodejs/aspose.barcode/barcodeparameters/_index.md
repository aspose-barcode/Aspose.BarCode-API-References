---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "条形码生成参数。"
type: docs
weight: 140
url: /zh/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

条形码生成参数。

```js
new BarcodeParameters()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | AustralianPost 条码参数。 |
| [getAztec()](#getaztec) | Aztec 参数。 |
| [getBarColor()](#getbarcolor) | 条形颜色。 |
| [getBarHeight()](#getbarheight) | 1D 条码条的高度（单位值）。如果 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMo，则忽略。 |
| [getBarWidthReduction()](#getbarwidthreduction) | 获取用于在打印时补偿墨水扩散的条形减小值。 |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | 始终在 Code128 和 GS1Code128 条码的可读文本中显示校验位数字。 |
| [getCodabar()](#getcodabar) | Codabar 参数。 |
| [getCodablock()](#getcodablock) | Codablock 参数。 |
| [getCode16K()](#getcode16k) | Code16K 参数。 |
| [getCode128()](#getcode128) | Code128 参数。 |
| [getCodeTextParameters()](#getcodetextparameters) | Codetext 参数。 |
| [getCoupon()](#getcoupon) | 优惠券参数。用于 UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon。 |
| [getDataBar()](#getdatabar) | Databar 参数。 |
| [getDataMatrix()](#getdatamatrix) | DataMatrix 参数。 |
| [getDotCode()](#getdotcode) | DotCode 参数。 |
| [getEnableEscape()](#getenableescape) | 指示在 CodeText 属性中是否将字符 "\\" 解释为转义字符。用于 Pdf417、DataMatrix、C |
| [getFilledBars()](#getfilledbars) | 获取指示条形是否填充的值。仅适用于 1D 条码。默认值：true。 |
| [getGS1CompositeBar()](#getgs1compositebar) | GS1 复合条参数。此示例展示如何创建并保存 GS1 复合条图像。注意 1D 编码文本 |
| [getHanXin()](#gethanxin) | HanXin 参数。 |
| [getITF()](#getitf) | ITF 参数。 |
| [getMaxiCode()](#getmaxicode) | MaxiCode 参数。 |
| [getPadding()](#getpadding) | 条码填充。默认值：5pt 5pt 5pt 5pt。 |
| [getPatchCode()](#getpatchcode) | PatchCode 参数。 |
| [getPdf417()](#getpdf417) | PDF417 参数。 |
| [getPostal()](#getpostal) | 邮政参数。用于 Postnet、Planet。 |
| [getQR()](#getqr) | QR 参数。 |
| [getSupplement()](#getsupplement) | 补充参数。用于 Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN。 |
| [getWideNarrowRatio()](#getwidenarrowratio) | 宽条与窄条的比例。默认值：3，即宽条是窄条的 3 倍。用于 ITF， |
| [getXDimension()](#getxdimension) | x 维度是 BarCode 条或空格单元的最小宽度。增大此值将增大整个条码 |
| [isChecksumEnabled()](#ischecksumenabled) | 在生成 1D 条码时启用校验和。对于必须包含校验和的符号，默认视为 Yes，作为 N |
| [setBarColor(value)](#setbarcolor) | 条形颜色。 |
| [setBarHeight()](#setbarheight) | 1D 条码条的高度（单位值）。如果 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMo，则忽略。 |
| [setBarWidthReduction()](#setbarwidthreduction) | 设置用于在打印时补偿墨水扩散的条形减小值。 |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | 始终在 Code128 和 GS1Code128 条码的可读文本中显示校验位数字。 |
| [setChecksumEnabled()](#setchecksumenabled) | 在生成 1D 条码时启用校验和。对于必须包含校验和的符号，默认视为 Yes，作为 N |
| [setEnableEscape()](#setenableescape) | 指示在 CodeText 属性中是否将字符 "\\" 解释为转义字符。用于 Pdf417、DataMatrix、C |
| [setFilledBars()](#setfilledbars) | 设置指示条形是否填充的值。仅适用于 1D 条码。默认值：true。 |
| [setGS1CompositeBar()](#setgs1compositebar) | GS1 复合条参数。此示例展示如何创建并保存 GS1 复合条图像。注意 1D 编码文本 |
| [setPadding()](#setpadding) | 条码填充。默认值：5pt 5pt 5pt 5pt。 |
| [setWideNarrowRatio()](#setwidenarrowratio) | 宽条与窄条的比例。默认值：3，即宽条是窄条的 3 倍。用于 ITF，P |
| [setXDimension()](#setxdimension) | x 维度是 BarCode 条或空格单元的最小宽度。增大此值将增大整个条码 |

### getAustralianPost() {#getaustralianpost}

AustralianPost 条码参数。

### getAztec() {#getaztec}

Aztec 参数。

### getBarColor() {#getbarcolor}

条形颜色。

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

1D 条码条的高度（单位值）。如果 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION，则忽略。

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

获取用于在打印时补偿墨水扩散的条形减小值。

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

始终在 Code128 和 GS1Code128 条码的可读文本中显示校验位数字。

### getCodabar() {#getcodabar}

Codabar 参数。

### getCodablock() {#getcodablock}

Codablock 参数。

### getCode16K() {#getcode16k}

Code16K 参数。

### getCode128() {#getcode128}

Code128 参数。

### getCodeTextParameters() {#getcodetextparameters}

Codetext 参数。

### getCoupon() {#getcoupon}

优惠券参数。用于 UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon。

### getDataBar() {#getdatabar}

Databar 参数。

### getDataMatrix() {#getdatamatrix}

DataMatrix 参数。

### getDotCode() {#getdotcode}

DotCode 参数。

### getEnableEscape() {#getenableescape}

指示在 CodeText 属性中是否将字符 "\\" 解释为转义字符。用于 Pdf417、DataMatrix、Code128。仅当 EnableEscape 为 true 时，"\\" 将被解释为特殊转义字符。否则，"\\" 作为普通字符。Aspose.BarCode 支持输入十进制 ASCII 码和 ASCII 控制码字符的助记符。例如，\\013 和 \\\\CR 代表 CR。

### getFilledBars() {#getfilledbars}

获取指示条形是否填充的值。仅适用于 1D 条码。默认值：true。

### getGS1CompositeBar() {#getgs1compositebar}

GS1 复合条参数。此示例展示如何创建并保存 GS1 复合条图像。注意 1D 编码文本和 2D 编码文本由符号 '/' 分隔。

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

HanXin 参数。

### getITF() {#getitf}

ITF 参数。

### getMaxiCode() {#getmaxicode}

MaxiCode 参数。

### getPadding() {#getpadding}

条码填充。默认值：5pt 5pt 5pt 5pt。

### getPatchCode() {#getpatchcode}

PatchCode 参数。

### getPdf417() {#getpdf417}

PDF417 参数。

### getPostal() {#getpostal}

邮政参数。用于 Postnet、Planet。

### getQR() {#getqr}

QR 参数。

### getSupplement() {#getsupplement}

补充参数。用于 Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN。

### getWideNarrowRatio() {#getwidenarrowratio}

宽条与窄条的比例。默认值：3，即宽条是窄条的 3 倍。用于 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39Extended、Code39Standard。WideNarrowRatio 参数值小于或等于 0。

### getXDimension() {#getxdimension}

x 维度是 BarCode 条或空格单元的最小宽度。增大此值将增大整个条码图像宽度。如果 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION，则忽略。

### isChecksumEnabled() {#ischecksumenabled}

在生成一维条码时启用校验和。默认情况下，对于必须包含校验和的符号体系视为是，对于仅可能使用校验和的视为否。可以使用校验和的符号有：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN、Codabar。始终使用校验和的符号：其余符号体系。

### setBarColor(value) {#setbarcolor}

条形颜色。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 字符串 | 条形颜色的默认值：#000000。 |

### setBarHeight() {#setbarheight}

1D 条码条的高度（单位值）。如果 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION，则忽略。

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

设置用于在打印时补偿墨水扩散的条形减小值。

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

始终在 Code128 和 GS1Code128 条码的可读文本中显示校验位数字。

### setChecksumEnabled() {#setchecksumenabled}

在生成一维条码时启用校验和。默认情况下，对于必须包含校验和的符号体系视为是，对于仅可能使用校验和的视为否。可以使用校验和的符号有：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN、Codabar。始终使用校验和的符号：其余符号体系。

### setEnableEscape() {#setenableescape}

指示是否将字符 \"\\\" 解释为 CodeText 属性中的转义字符。仅用于 Pdf417、DataMatrix、Code128。如果 EnableEscape 为 true，\"\\\" 将被解释为特殊转义字符。否则，\"\\\" 作为普通字符。Aspose.BarCode 支持十进制 ASCII 码和 ASCII 控制码字符的助记符。例如，\\013 和 \\CR 代表 CR。

### setFilledBars() {#setfilledbars}

设置指示条形是否填充的值。仅适用于 1D 条码。默认值：true。

### setGS1CompositeBar() {#setgs1compositebar}

GS1 复合条参数。此示例展示如何创建并保存 GS1 复合条图像。注意 1D 编码文本和 2D 编码文本由符号 '/' 分隔。

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

条码填充。默认值：5pt 5pt 5pt 5pt。

### setWideNarrowRatio() {#setwidenarrowratio}

宽条与窄条的比例。默认值：3，即宽条是窄条的 3 倍。用于 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39Extended、Code39Standard。WideNarrowRatio 参数值小于或等于 0。

### setXDimension() {#setxdimension}

x 维度是 BarCode 条或空格单元的最小宽度。增大此值将增大整个条码图像宽度。如果 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION，则忽略。

**Throws:** BarcodeException
