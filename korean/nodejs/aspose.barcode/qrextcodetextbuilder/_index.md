---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "QREncodeMode의 ExtendedCodetext 모드용 2D QR 바코드 확장 코드텍스트 생성기. BarCodeBuilder의 Display2DText 속성을 사용하여 표시 텍스트를 rem으로 설정합니다."
type: docs
weight: 820
url: /ko/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

QREncodeMode의 ExtendedCodetext 모드용 2D QR 바코드 확장 코드텍스트 생성기. BarCodeBuilder의 Display2DText 속성을 사용하여 표시 텍스트를 관리 문자 제거로 설정합니다.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | 지정된 QR 압축 모드를 사용하여 코덱스트를 확장된 코덱스트 항목에 추가합니다. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | FNC1을 첫 번째 위치에 확장된 코덱스트 항목에 추가합니다. |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | 그룹 구분자(GS - '\\u001D')를 확장된 코덱스트 항목에 추가합니다. |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | FNC1을 두 번째 위치에 확장된 코덱스트 항목에 추가합니다. |
| [clear()](#clear) | 확장 코드 텍스트 항목을 지웁니다 |
| [getExtendedCodetext()](#getextendedcodetext) | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

지정된 QR 압축 모드를 사용하여 코덱스트를 확장된 코덱스트 항목에 추가합니다.

| 매개변수 | 설명 |
| --- | --- |
| 모드 | 코덱스트에 대한 QR 압축 모드. |
| codetext | 확장된 코덱스트 항목으로 추가할 Unicode 코덱스트. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

FNC1을 첫 번째 위치에 확장된 코덱스트 항목에 추가합니다.

### addFNC1GroupSeparator() {#addfnc1groupseparator}

그룹 구분자(GS - '\\u001D')를 확장된 코덱스트 항목에 추가합니다.

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

FNC1을 두 번째 위치에 확장된 코덱스트 항목에 추가합니다.

| 매개변수 | 설명 |
| --- | --- |
| codetext | 두 번째 위치에 있는 FNC1의 값 |

### clear() {#clear}

확장 코드 텍스트 항목을 지웁니다

### getExtendedCodetext() {#getextendedcodetext}

확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다.

**Returns:** Extended codetext as string
