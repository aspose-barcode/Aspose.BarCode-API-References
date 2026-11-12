---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "인식된 DataMatrix 바코드의 특수 데이터를 저장합니다. 이 샘플은 DataMatrix 원시 값을 가져오는 방법을 보여줍니다. let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /ko/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

인식된 DataMatrix 바코드의 특수 데이터를 저장합니다. 이 샘플은 DataMatrix 원시 값을 가져오는 방법을 보여줍니다. let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | `DataMatrixExtendedParameters` 지정 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | DataMatrix 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | DataMatrix 구조 추가 모드 바코드 수를 가져옵니다. 기본값은 -1이며, 카운트는 1에서 35 사이의 값이어야 합니다. |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | DataMatrix 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isReaderProgramming()](#isreaderprogramming) | 코드가 다음 데이터를 초기화 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다 또는 |
| [toString()](#tostring) | `DataMatrixExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### equals(obj) {#equals}

`DataMatrixExtendedParameters` 지정 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 System.Object 값을 제공합니다. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

DataMatrix 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다. 값: DataMatrix 구조 추가 모드 바코드의 ID.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

DataMatrix 구조 추가 모드 바코드 수를 가져옵니다. 기본값은 -1이며, 카운트는 1에서 35 사이의 값이어야 합니다. 값: DataMatrix 구조 추가 모드 바코드의 수.

### getStructuredAppendFileId() {#getstructuredappendfileid}

DataMatrix 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다. 값: DataMatrix 구조 추가 모드 바코드의 ID.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

코드가 다음 데이터를 초기화 또는 바코드 판독기 재프로그램 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

### toString() {#tostring}

`DataMatrixExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
