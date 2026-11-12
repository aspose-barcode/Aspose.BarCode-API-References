---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "HIBC PAS 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다."
type: docs
weight: 480
url: /ko/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

HIBC PAS 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다.

```js
new HIBCPASCodetext()
```

**Example:**

```js
This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

 let complexCodetext = new HIBCPASComplexCodetext();
 complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
 complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
 complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
 complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
 let generator = new ComplexBarcodeGenerator(complexCodetext);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
 reader.readBarCodes();
 let codetext = reader.getFoundBarCodes()[0].getCodeText();
	let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
 print("Data location: " + readCodetext.getDataLocation());
 print("Data type: " + readCodetext.getRecords()[0].getDataType());
 print("Data: " + readCodetext.getRecords()[0].getData());
 print("Data type: " + readCodetext.getRecords()[1].getDataType());
 print("Data: " + readCodetext.getRecords()[1].getData());
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | HIBCPASRecord 생성자 |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | 새 레코드를 추가합니다 |
| [addRecord(dataType, data)](#addrecord) | 새 레코드를 추가합니다 |
| [clear()](#clear) | 레코드 목록을 지웁니다 |
| [equals(obj)](#equals) | 지정된 `HIBCPASCodetext` 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| [getBarcodeType()](#getbarcodetype) | 바코드 유형을 가져옵니다. |
| [getConstructedCodetext()](#getconstructedcodetext) | 코드텍스트를 구성합니다 |
| [getDataLocation()](#getdatalocation) | 데이터 위치를 식별합니다. |
| [getRecords()](#getrecords) | 레코드 목록을 가져옵니다 |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [initFromString(constructedCodetext)](#initfromstring) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |
| [setBarcodeType()](#setbarcodetype) | 바코드 유형을 가져오거나 설정합니다. HIBC PAS 코드 텍스트는 HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData를 사용하여 인코딩할 수 있습니다. |
| [setDataLocation()](#setdatalocation) | 데이터 위치를 식별합니다. |

### _fromMwObject() (static) {#-frommwobject}

HIBCPASRecord 생성자

### addHIBCPASRecord(record) {#addhibcpasrecord}

새 레코드를 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 레코드 | 추가될 레코드 |

### addRecord(dataType, data) {#addrecord}

새 레코드를 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| dataType | 데이터 유형 |
| 데이터 | 데이터 문자열 |

### clear() {#clear}

레코드 목록을 지웁니다

### equals(obj) {#equals}

지정된 `HIBCPASCodetext` 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 `HIBCPASCodetext` 값. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

바코드 유형을 가져옵니다.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

코드텍스트를 구성합니다

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

데이터 위치를 식별합니다.

### getRecords() {#getrecords}

레코드 목록을 가져옵니다

**Returns:** List of records

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

구성된 코드텍스트에서 인스턴스를 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| constructedCodetext | 구성된 코드텍스트. |

### setBarcodeType() {#setbarcodetype}

바코드 유형을 가져오거나 설정합니다. HIBC PAS 코드 텍스트는 HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS 및 HIBCQRPAS 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

데이터 위치를 식별합니다.
