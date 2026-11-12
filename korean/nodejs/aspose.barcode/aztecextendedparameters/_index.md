---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "Aztec 인식 바코드의 특수 데이터를 저장합니다. 이 예제는 Aztec 원시 값을 가져오는 방법을 보여줍니다. let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /ko/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Aztec 인식 바코드의 특수 데이터를 저장합니다. 이 예제는 Aztec 원시 값을 가져오는 방법을 보여줍니다. let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | `AztecExtendedParameters` 값과 이 인스턴스가 동일한지 여부를 나타내는 값을 반환합니다. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Aztec 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Aztec 구조 추가 모드 바코드 수를 가져옵니다. 기본값은 0이며, 카운트는 1에서 26 사이의 값이어야 합니다. Value: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Aztec 구조 추가 모드의 파일 ID를 가져옵니다. 기본값은 빈 문자열이며, Value: The File ID of the Aztec stru |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isReaderInitialization()](#isreaderinitialization) | 코드가 다음 데이터를 초기화 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다 또는 |
| [toString()](#tostring) | 이 `AztecExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### equals(obj) {#equals}

`AztecExtendedParameters` 값과 이 인스턴스가 동일한지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 System.Object 값을 제공합니다. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Aztec 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 0이며, Value: The barcode ID of the Aztec structured append mode.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Aztec 구조 추가 모드 바코드 수를 가져옵니다. 기본값은 0이며, 카운트는 1에서 26 사이의 값이어야 합니다. Value: The barcodes count of the Aztec structured append mode.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Aztec 구조 추가 모드의 파일 ID를 가져옵니다. 기본값은 빈 문자열이며, Value: The File ID of the Aztec structured append mode.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

코드가 다음 데이터를 초기화 또는 바코드 판독기 재프로그램 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

### toString() {#tostring}

이 `AztecExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this `AztecExtendedParameters`.
