---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "모드 4, 5 및 6에 대한 MaxiCode 코드텍스트를 인코딩 및 디코딩하기 위한 클래스."
type: docs
weight: 670
url: /ko/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

모드 4, 5 및 6에 대한 MaxiCode 코드텍스트를 인코딩 및 디코딩하기 위한 클래스.

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스가 지정된 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getConstructedCodetext()](#getconstructedcodetext) | 코드텍스트를 구성합니다 |
| [getHashCode()](#gethashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [getMessage()](#getmessage) | 메시지를 가져옵니다. |
| [getMode()](#getmode) | MaxiCode 모드를 가져옵니다. |
| [initFromString(constructedCodetext)](#initfromstring) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |
| [setMessage()](#setmessage) | 메시지를 설정합니다. |
| [setMode()](#setmode) | MaxiCode 모드를 설정합니다. 표준 코덱스트는 모드 4, 5 및 6에서만 사용할 수 있습니다. |

### equals(obj) {#equals}

이 인스턴스가 지정된 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 값. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

코드텍스트를 구성합니다

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

메시지를 가져옵니다.

### getMode() {#getmode}

MaxiCode 모드를 가져옵니다.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

구성된 코드텍스트에서 인스턴스를 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| constructedCodetext | 구성된 코드텍스트. |

### setMessage() {#setmessage}

메시지를 설정합니다.

### setMode() {#setmode}

MaxiCode 모드를 설정합니다. 표준 코덱스트는 모드 4, 5 및 6에서만 사용할 수 있습니다.
