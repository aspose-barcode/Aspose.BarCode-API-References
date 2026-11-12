---
title: "PdfParameters"
linktitle: "PdfParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "PDF 매개변수 래퍼."
type: docs
weight: 780
url: /ko/nodejs/aspose.barcode/pdfparameters/
---

## PdfParameters class

PDF 매개변수 래퍼. 기본 `mwObject` 인스턴스를 기대하며, 해당 getter/setter 메서드를 제공하여 "30_100_0_30"와 같은 CMYK 문자열을 반환/수락하거나 `null`을 반환합니다.

```js
new PdfParameters(mwObject)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mwObject | 객체 | – Java PdfParameters 클래스의 인스턴스 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [_initializeWrapperMembers()](#-initializewrappermembers) | no-op 초기화자 |
| [getCMYKBackColor()](#getcmykbackcolor) | CMYK 배경 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다. |
| [getCMYKBarColor()](#getcmykbarcolor) | 바코드의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다. |
| [getCMYKCaptionAboveColor()](#getcmykcaptionabovecolor) | 위 캡션의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다. |
| [getCMYKCaptionBelowColor()](#getcmykcaptionbelowcolor) | 아래 캡션의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다. |
| [getCMYKCodetextColor()](#getcmykcodetextcolor) | 코드텍스트의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다. |
| [isTextAsPath()](#istextaspath) | 텍스트 대신 경로를 사용합니까 (Unicode 문자가 표시되지 않을 경우 사용) 기본값: false. |
| [setCMYKBackColor(value)](#setcmykbackcolor) | CMYK 배경 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다. |
| [setCMYKBarColor(value)](#setcmykbarcolor) | 바코드의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다. |
| [setCMYKCaptionAboveColor(value)](#setcmykcaptionabovecolor) | 위 캡션의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다. |
| [setCMYKCaptionBelowColor(value)](#setcmykcaptionbelowcolor) | 아래 캡션의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다. |
| [setCMYKCodetextColor(value)](#setcmykcodetextcolor) | 코드텍스트의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다. |
| [setTextAsPath()](#settextaspath) | 텍스트 대신 경로를 사용합니까 (Unicode 문자가 표시되지 않을 경우 사용) 기본값: false. |

### _initializeWrapperMembers() {#-initializewrappermembers}

no-op 초기화자

### getCMYKBackColor() {#getcmykbackcolor}

CMYK 배경 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다.

**Returns:** CMYKColor\|null

### getCMYKBarColor() {#getcmykbarcolor}

바코드의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다.

**Returns:** CMYKColor\|null

### getCMYKCaptionAboveColor() {#getcmykcaptionabovecolor}

위 캡션의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다.

**Returns:** CMYKColor\|null

### getCMYKCaptionBelowColor() {#getcmykcaptionbelowcolor}

아래 캡션의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다.

**Returns:** CMYKColor\|null

### getCMYKCodetextColor() {#getcmykcodetextcolor}

코드텍스트의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다.

**Returns:** CMYKColor\|null

### isTextAsPath() {#istextaspath}

텍스트 대신 경로를 사용합니까 (Unicode 문자가 표시되지 않을 경우 사용) 기본값: false.

### setCMYKBackColor(value) {#setcmykbackcolor}

CMYK 배경 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | CMYKColor\ | null |  |

### setCMYKBarColor(value) {#setcmykbarcolor}

바코드의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | CMYKColor\ | null |  |

### setCMYKCaptionAboveColor(value) {#setcmykcaptionabovecolor}

위 캡션의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | CMYKColor\ | null |  |

### setCMYKCaptionBelowColor(value) {#setcmykcaptionbelowcolor}

아래 캡션의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | CMYKColor\ | null |  |

### setCMYKCodetextColor(value) {#setcmykcodetextcolor}

코드텍스트의 CMYK 색상 값. Null은 CMYK 색상이 사용되지 않고 대신 일반 RGB 색상이 사용됨을 의미합니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | CMYKColor\ | null |  |

### setTextAsPath() {#settextaspath}

텍스트 대신 경로를 사용합니까 (Unicode 문자가 표시되지 않을 경우 사용) 기본값: false.
