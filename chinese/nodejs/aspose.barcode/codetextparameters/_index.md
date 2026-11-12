---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "Codetext 参数。"
type: docs
weight: 270
url: /zh/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

Codetext 参数。

```js
new CodetextParameters()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAlignment()](#getalignment) | 获取码文本的对齐方式。默认值：TextAlignment.CENTER。 |
| [getColor()](#getcolor) | 指定显示的 CodeText 颜色。默认值 BLACK。 |
| [getFont()](#getfont) | 指定显示的 CodeText 字体。默认值：Arial 5pt regular。如果 FontMode 设置为 FontMode.AUTO，则忽略此设置。 |
| [getFontMode()](#getfontmode) | 指定 FontMode。如果 FontMode 设置为 Auto，字体大小将根据 xDimension 值自动计算。It i |
| [getLocation()](#getlocation) | 指定显示的 CodeText 位置，设置为 CodeLocation.NONE 可隐藏 CodeText。默认值：CodeLocation.BELOW。 |
| [getNoWrap()](#getnowrap) | 指定文本内的自动换行（换行符）。默认值：false。 |
| [getSpace()](#getspace) | CodeText 与条形码之间的间距（单位值）。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN 等忽略。 |
| [getTwoDDisplayText()](#gettwoddisplaytext) | 在 2D 条码中将显示的文本，代替码文本。用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCo |
| [setAlignment()](#setalignment) | 设置码文本的对齐方式。默认值：TextAlignment.CENTER。 |
| [setColor()](#setcolor) | 指定显示的 CodeText 颜色。默认值 BLACK。 |
| [setFont()](#setfont) | 指定显示的 CodeText 字体。默认值：Arial 5pt regular。如果 FontMode 设置为 FontMode.AUTO，则忽略此设置。 |
| [setFontMode()](#setfontmode) | 指定 FontMode。如果 FontMode 设置为 Auto，字体大小将根据 xDimension 值自动计算。It i |
| [setLocation()](#setlocation) | 指定显示的 CodeText 位置，设置为 CodeLocation.NONE 可隐藏 CodeText。默认值：CodeLocation.NONE。 |
| [setNoWrap()](#setnowrap) | 指定文本内的自动换行（换行符）。默认值：false。 |
| [setSpace()](#setspace) | CodeText 与条形码之间的间距（单位值）。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN 等忽略。 |
| [setTwoDDisplayText()](#settwoddisplaytext) | 在 2D 条码中将显示的文本，代替码文本。用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCo |
| [toString()](#tostring) | 返回此 CodetextParameters 的可读字符串表示。 |

### getAlignment() {#getalignment}

获取码文本的对齐方式。默认值：TextAlignment.CENTER。

### getColor() {#getcolor}

指定显示的 CodeText 颜色。默认值 BLACK。

### getFont() {#getfont}

指定显示的 CodeText 字体。默认值：Arial 5pt regular。如果 FontMode 设置为 FontMode.AUTO，则忽略此设置。

### getFontMode() {#getfontmode}

指定 FontMode。如果 FontMode 设置为 Auto，字体大小将根据 xDimension 值自动计算。建议在 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 中使用 FontMode.AUTO。默认值：FontMode.AUTO。

### getLocation() {#getlocation}

指定显示的 CodeText 位置，设置为 CodeLocation.NONE 可隐藏 CodeText。默认值：CodeLocation.BELOW。

### getNoWrap() {#getnowrap}

指定文本内的自动换行（换行符）。默认值：false。

### getSpace() {#getspace}

CodeText 与条形码之间的间距（单位值）。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon 等忽略。

### getTwoDDisplayText() {#gettwoddisplaytext}

将在 2D 条形码中显示的文本，以替代代码文本。适用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode

### setAlignment() {#setalignment}

设置码文本的对齐方式。默认值：TextAlignment.CENTER。

### setColor() {#setcolor}

指定显示的 CodeText 颜色。默认值 BLACK。

### setFont() {#setfont}

指定显示的 CodeText 字体。默认值：Arial 5pt regular。如果 FontMode 设置为 FontMode.AUTO，则忽略此设置。

### setFontMode() {#setfontmode}

指定 FontMode。如果 FontMode 设置为 Auto，字体大小将根据 xDimension 值自动计算。建议在 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 中使用 FontMode.AUTO。默认值：FontMode.AUTO。

### setLocation() {#setlocation}

指定显示的 CodeText 位置，设置为 CodeLocation.NONE 可隐藏 CodeText。默认值：CodeLocation.NONE。

### setNoWrap() {#setnowrap}

指定文本内的自动换行（换行符）。默认值：false。

### setSpace() {#setspace}

CodeText 与条形码之间的间距（单位值）。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon 等忽略。

### setTwoDDisplayText() {#settwoddisplaytext}

将在 2D 条形码中显示的文本，以替代代码文本。适用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode

### toString() {#tostring}

返回此 CodetextParameters 的可读字符串表示。

**Returns:** A string that represents this CodetextParameters.
