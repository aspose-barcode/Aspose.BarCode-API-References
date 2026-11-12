---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "인식된 DotCode 바코드의 특수 데이터를 저장합니다. 이 샘플은 DotCode 원시 값을 가져오는 방법을 보여줍니다"
type: docs
weight: 380
url: /ko/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

인식된 DotCode 바코드의 특수 데이터를 저장합니다. 이 샘플은 DotCode 원시 값을 가져오는 방법을 보여줍니다

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스가 지정된 `DotCodeExtendedParameters` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | 코드가 다음 데이터를 초기화 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다 또는 |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | DotCode 구조화 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | DotCode 구조화 추가 모드 바코드 수를 가져옵니다. 기본값은 -1입니다. 수는 1에서 35 사이의 값이어야 합니다. 값: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | DotCode 구조화 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | DotCode 구조화 추가 모드 바코드 수를 가져옵니다. 기본값은 -1입니다. 수는 1에서 35 사이의 값이어야 합니다. 값: |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isReaderInitialization()](#isreaderinitialization) | 코드가 다음 데이터를 초기화 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다 또는 |
| [toString()](#tostring) | 이 `DotCodeExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### equals(obj) {#equals}

이 인스턴스가 지정된 `DotCodeExtendedParameters` 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 System.Object 값을 제공합니다. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

코드가 다음 데이터를 초기화 또는 바코드 판독기 재프로그램 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

DotCode 구조화 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다. 값: DotCode 구조화 추가 모드 바코드의 ID.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

DotCode 구조화 추가 모드 바코드 수를 가져옵니다. 기본값은 -1입니다. 수는 1에서 35 사이의 값이어야 합니다. 값: DotCode 구조화 추가 모드 바코드의 수.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

DotCode 구조화 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다. 값: DotCode 구조화 추가 모드 바코드의 ID.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

DotCode 구조화 추가 모드 바코드 수를 가져옵니다. 기본값은 -1입니다. 수는 1에서 35 사이의 값이어야 합니다. 값: DotCode 구조화 추가 모드 바코드의 수.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

코드가 다음 데이터를 초기화 또는 바코드 판독기 재프로그램 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

### toString() {#tostring}

이 `DotCodeExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
