---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "코드텍스트 매개변수."
type: docs
weight: 270
url: /ko/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

코드텍스트 매개변수.

```js
new CodetextParameters()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAlignment()](#getalignment) | 코드 텍스트의 정렬을 가져옵니다. 기본값: TextAlignment.CENTER. |
| [getColor()](#getcolor) | 표시되는 CodeText의 색상을 지정합니다. 기본값: BLACK. |
| [getFont()](#getfont) | 표시되는 CodeText의 글꼴을 지정합니다. 기본값: Arial 5pt regular. FontMode가 FontMode.AUTO로 설정된 경우 무시됩니다. |
| [getFontMode()](#getfontmode) | FontMode를 지정합니다. FontMode가 Auto로 설정된 경우, 글꼴 크기는 xDimension 값에 따라 자동으로 계산됩니다. It i |
| [getLocation()](#getlocation) | 표시되는 CodeText 위치를 지정합니다. CodeText를 숨기려면 CodeLocation.NONE으로 설정하십시오. 기본값: CodeLocation.BELOW. |
| [getNoWrap()](#getnowrap) | 텍스트 내에서 단어 줄바꿈(줄 바꿈)을 지정합니다. 기본값: false. |
| [getSpace()](#getspace) | CodeText와 바코드 사이의 간격(단위 값). 기본값: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN에 대해서는 무시됩니다. |
| [getTwoDDisplayText()](#gettwoddisplaytext) | 2D 바코드에서 코드텍스트 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [setAlignment()](#setalignment) | 코드 텍스트의 정렬을 설정합니다. 기본값: TextAlignment.CENTER. |
| [setColor()](#setcolor) | 표시되는 CodeText의 색상을 지정합니다. 기본값: BLACK. |
| [setFont()](#setfont) | 표시되는 CodeText의 글꼴을 지정합니다. 기본값: Arial 5pt regular. FontMode가 FontMode.AUTO로 설정된 경우 무시됩니다. |
| [setFontMode()](#setfontmode) | FontMode를 지정합니다. FontMode가 Auto로 설정된 경우, 글꼴 크기는 xDimension 값에 따라 자동으로 계산됩니다. It i |
| [setLocation()](#setlocation) | 표시되는 CodeText 위치를 지정합니다. CodeText를 숨기려면 CodeLocation.NONE으로 설정하십시오. 기본값: CodeLocation.NONE. |
| [setNoWrap()](#setnowrap) | 텍스트 내에서 단어 줄바꿈(줄 바꿈)을 지정합니다. 기본값: false. |
| [setSpace()](#setspace) | CodeText와 바코드 사이의 간격(단위 값). 기본값: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN에 대해서는 무시됩니다. |
| [setTwoDDisplayText()](#settwoddisplaytext) | 2D 바코드에서 코드텍스트 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [toString()](#tostring) | 이 CodetextParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### getAlignment() {#getalignment}

코드 텍스트의 정렬을 가져옵니다. 기본값: TextAlignment.CENTER.

### getColor() {#getcolor}

표시되는 CodeText의 색상을 지정합니다. 기본값: BLACK.

### getFont() {#getfont}

표시되는 CodeText의 글꼴을 지정합니다. 기본값: Arial 5pt regular. FontMode가 FontMode.AUTO로 설정된 경우 무시됩니다.

### getFontMode() {#getfontmode}

FontMode를 지정합니다. FontMode가 Auto로 설정된 경우, 글꼴 크기는 xDimension 값에 따라 자동으로 계산됩니다. AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION에서 특히 FontMode.AUTO를 사용하는 것이 권장됩니다. 기본값: FontMode.AUTO.

### getLocation() {#getlocation}

표시되는 CodeText 위치를 지정합니다. CodeText를 숨기려면 CodeLocation.NONE으로 설정하십시오. 기본값: CodeLocation.BELOW.

### getNoWrap() {#getnowrap}

텍스트 내에서 단어 줄바꿈(줄 바꿈)을 지정합니다. 기본값: false.

### getSpace() {#getspace}

CodeText와 바코드 사이의 간격(단위 값). 기본값: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon에 대해서는 무시됩니다.

### getTwoDDisplayText() {#gettwoddisplaytext}

2D 바코드에서 코드텍스트 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### setAlignment() {#setalignment}

코드 텍스트의 정렬을 설정합니다. 기본값: TextAlignment.CENTER.

### setColor() {#setcolor}

표시되는 CodeText의 색상을 지정합니다. 기본값: BLACK.

### setFont() {#setfont}

표시되는 CodeText의 글꼴을 지정합니다. 기본값: Arial 5pt regular. FontMode가 FontMode.AUTO로 설정된 경우 무시됩니다.

### setFontMode() {#setfontmode}

FontMode를 지정합니다. FontMode가 Auto로 설정된 경우, 글꼴 크기는 xDimension 값에 따라 자동으로 계산됩니다. AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION에서 특히 FontMode.AUTO를 사용하는 것이 권장됩니다. 기본값: FontMode.AUTO.

### setLocation() {#setlocation}

표시되는 CodeText 위치를 지정합니다. CodeText를 숨기려면 CodeLocation.NONE으로 설정하십시오. 기본값: CodeLocation.NONE.

### setNoWrap() {#setnowrap}

텍스트 내에서 단어 줄바꿈(줄 바꿈)을 지정합니다. 기본값: false.

### setSpace() {#setspace}

CodeText와 바코드 사이의 간격(단위 값). 기본값: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon에 대해서는 무시됩니다.

### setTwoDDisplayText() {#settwoddisplaytext}

2D 바코드에서 코드텍스트 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### toString() {#tostring}

이 CodetextParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this CodetextParameters.
