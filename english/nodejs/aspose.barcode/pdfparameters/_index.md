---
title: "PdfParameters"
linktitle: "PdfParameters"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "PDF parameters wrapper."
type: docs
weight: 780
url: /nodejs/aspose.barcode/pdfparameters/
---

## PdfParameters class

PDF parameters wrapper. Expects an underlying `mwObject` instance that provides the corresponding getter/setter methods returning/accepting CMYK strings like "30_100_0_30" or `null`.

```js
new PdfParameters(mwObject)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mwObject | object | – instance of the Java PdfParameters class |

## Methods

| Name | Description |
| --- | --- |
| [_initializeWrapperMembers()](#-initializewrappermembers) | no-op initializer |
| [getCMYKBackColor()](#getcmykbackcolor) | CMYK back color value. Null means CMYK color is not used, instead normal RGB color is used. |
| [getCMYKBarColor()](#getcmykbarcolor) | CMYK color value of bar code. Null means CMYK color is not used, instead normal RGB color is used. |
| [getCMYKCaptionAboveColor()](#getcmykcaptionabovecolor) | CMYK color value of caption above. Null means CMYK color is not used, instead normal RGB color is used. |
| [getCMYKCaptionBelowColor()](#getcmykcaptionbelowcolor) | CMYK color value of caption below. Null means CMYK color is not used, instead normal RGB color is used. |
| [getCMYKCodetextColor()](#getcmykcodetextcolor) | CMYK color value of Codetext. Null means CMYK color is not used, instead normal RGB color is used. |
| [isTextAsPath()](#istextaspath) | Are paths used instead of text (use if Unicode characters are not displayed) Default value: false. |
| [setCMYKBackColor(value)](#setcmykbackcolor) | CMYK back color value. Null means CMYK color is not used, instead normal RGB color is used. |
| [setCMYKBarColor(value)](#setcmykbarcolor) | CMYK color value of bar code. Null means CMYK color is not used, instead normal RGB color is used. |
| [setCMYKCaptionAboveColor(value)](#setcmykcaptionabovecolor) | CMYK color value of caption above. Null means CMYK color is not used, instead normal RGB color is used. |
| [setCMYKCaptionBelowColor(value)](#setcmykcaptionbelowcolor) | CMYK color value of caption below. Null means CMYK color is not used, instead normal RGB color is used. |
| [setCMYKCodetextColor(value)](#setcmykcodetextcolor) | CMYK color value of Codetext. Null means CMYK color is not used, instead normal RGB color is used. |
| [setTextAsPath()](#settextaspath) | Are paths used instead of text (use if Unicode characters are not displayed) Default value: false. |

### _initializeWrapperMembers() {#-initializewrappermembers}

no-op initializer

### getCMYKBackColor() {#getcmykbackcolor}

CMYK back color value. Null means CMYK color is not used, instead normal RGB color is used.

**Returns:** CMYKColor\|null

### getCMYKBarColor() {#getcmykbarcolor}

CMYK color value of bar code. Null means CMYK color is not used, instead normal RGB color is used.

**Returns:** CMYKColor\|null

### getCMYKCaptionAboveColor() {#getcmykcaptionabovecolor}

CMYK color value of caption above. Null means CMYK color is not used, instead normal RGB color is used.

**Returns:** CMYKColor\|null

### getCMYKCaptionBelowColor() {#getcmykcaptionbelowcolor}

CMYK color value of caption below. Null means CMYK color is not used, instead normal RGB color is used.

**Returns:** CMYKColor\|null

### getCMYKCodetextColor() {#getcmykcodetextcolor}

CMYK color value of Codetext. Null means CMYK color is not used, instead normal RGB color is used.

**Returns:** CMYKColor\|null

### isTextAsPath() {#istextaspath}

Are paths used instead of text (use if Unicode characters are not displayed) Default value: false.

### setCMYKBackColor(value) {#setcmykbackcolor}

CMYK back color value. Null means CMYK color is not used, instead normal RGB color is used.

| Parameter | Type | Description |
| --- | --- | --- |
| value | CMYKColor\|null |  |

### setCMYKBarColor(value) {#setcmykbarcolor}

CMYK color value of bar code. Null means CMYK color is not used, instead normal RGB color is used.

| Parameter | Type | Description |
| --- | --- | --- |
| value | CMYKColor\|null |  |

### setCMYKCaptionAboveColor(value) {#setcmykcaptionabovecolor}

CMYK color value of caption above. Null means CMYK color is not used, instead normal RGB color is used.

| Parameter | Type | Description |
| --- | --- | --- |
| value | CMYKColor\|null |  |

### setCMYKCaptionBelowColor(value) {#setcmykcaptionbelowcolor}

CMYK color value of caption below. Null means CMYK color is not used, instead normal RGB color is used.

| Parameter | Type | Description |
| --- | --- | --- |
| value | CMYKColor\|null |  |

### setCMYKCodetextColor(value) {#setcmykcodetextcolor}

CMYK color value of Codetext. Null means CMYK color is not used, instead normal RGB color is used.

| Parameter | Type | Description |
| --- | --- | --- |
| value | CMYKColor\|null |  |

### setTextAsPath() {#settextaspath}

Are paths used instead of text (use if Unicode characters are not displayed) Default value: false.
