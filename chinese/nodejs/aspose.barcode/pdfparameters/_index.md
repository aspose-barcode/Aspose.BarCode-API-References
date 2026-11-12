---
title: "PdfParameters"
linktitle: "PdfParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "PDF 参数包装器。"
type: docs
weight: 780
url: /zh/nodejs/aspose.barcode/pdfparameters/
---

## PdfParameters class

PDF 参数包装器。期望底层 `mwObject` 实例提供相应的 getter/setter 方法，返回/接受类似 "30_100_0_30" 的 CMYK 字符串或 `null`。

```js
new PdfParameters(mwObject)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mwObject | 对象 | – Java PdfParameters 类的实例 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [_initializeWrapperMembers()](#-initializewrappermembers) | 无操作初始化器 |
| [getCMYKBackColor()](#getcmykbackcolor) | CMYK 背景颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。 |
| [getCMYKBarColor()](#getcmykbarcolor) | 条形码的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。 |
| [getCMYKCaptionAboveColor()](#getcmykcaptionabovecolor) | 上方标题的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。 |
| [getCMYKCaptionBelowColor()](#getcmykcaptionbelowcolor) | 下方标题的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。 |
| [getCMYKCodetextColor()](#getcmykcodetextcolor) | 代码文本的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。 |
| [isTextAsPath()](#istextaspath) | 是否使用路径代替文本（如果 Unicode 字符未显示，请使用）默认值：false。 |
| [setCMYKBackColor(value)](#setcmykbackcolor) | CMYK 背景颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。 |
| [setCMYKBarColor(value)](#setcmykbarcolor) | 条形码的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。 |
| [setCMYKCaptionAboveColor(value)](#setcmykcaptionabovecolor) | 上方标题的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。 |
| [setCMYKCaptionBelowColor(value)](#setcmykcaptionbelowcolor) | 下方标题的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。 |
| [setCMYKCodetextColor(value)](#setcmykcodetextcolor) | 代码文本的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。 |
| [setTextAsPath()](#settextaspath) | 是否使用路径代替文本（如果 Unicode 字符未显示，请使用）默认值：false。 |

### _initializeWrapperMembers() {#-initializewrappermembers}

无操作初始化器

### getCMYKBackColor() {#getcmykbackcolor}

CMYK 背景颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。

**Returns:** CMYKColor\|null

### getCMYKBarColor() {#getcmykbarcolor}

条形码的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。

**Returns:** CMYKColor\|null

### getCMYKCaptionAboveColor() {#getcmykcaptionabovecolor}

上方标题的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。

**Returns:** CMYKColor\|null

### getCMYKCaptionBelowColor() {#getcmykcaptionbelowcolor}

下方标题的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。

**Returns:** CMYKColor\|null

### getCMYKCodetextColor() {#getcmykcodetextcolor}

代码文本的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。

**Returns:** CMYKColor\|null

### isTextAsPath() {#istextaspath}

是否使用路径代替文本（如果 Unicode 字符未显示，请使用）默认值：false。

### setCMYKBackColor(value) {#setcmykbackcolor}

CMYK 背景颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | CMYKColor\ | null |  |

### setCMYKBarColor(value) {#setcmykbarcolor}

条形码的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | CMYKColor\ | null |  |

### setCMYKCaptionAboveColor(value) {#setcmykcaptionabovecolor}

上方标题的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | CMYKColor\ | null |  |

### setCMYKCaptionBelowColor(value) {#setcmykcaptionbelowcolor}

下方标题的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | CMYKColor\ | null |  |

### setCMYKCodetextColor(value) {#setcmykcodetextcolor}

代码文本的 CMYK 颜色值。Null 表示未使用 CMYK 颜色，而是使用普通的 RGB 颜色。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | CMYKColor\ | null |  |

### setTextAsPath() {#settextaspath}

是否使用路径代替文本（如果 Unicode 字符未显示，请使用）默认值：false。
