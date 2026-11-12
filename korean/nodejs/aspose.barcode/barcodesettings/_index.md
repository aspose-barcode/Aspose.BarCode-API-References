---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "주요 BarCode 디코딩 매개변수입니다."
type: docs
weight: 150
url: /ko/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

주요 바코드 디코딩 매개변수입니다. 인식된 데이터에 영향을 주는 매개변수를 포함합니다.

```js
new BarcodeSettings(settings)
```

BarcodeSettings 복사 생성자

| 매개변수 | 설명 |
| --- | --- |
| 설정 | 데이터의 소스 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | AustraliaPost 디코딩 매개변수를 가져옵니다 |
| [getChecksumValidation()](#getchecksumvalidation) | 1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다. 기본값은 해당 심볼에 대해 Yes로 처리됩니다. |
| [getDetectEncoding()](#getdetectencoding) | Unicode 코드셋에 대한 코드텍스트 인코딩을 엔진이 감지하도록 강제하는 플래그입니다. 기본값은 true입니다. |
| [getStripFNC()](#getstripfnc) | 코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. 기본값은 false입니다. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | 인식에 명시적으로 지정된 바코드 유형만 반환합니다. 활성화하면 다른 호환 가능한 ... |
| [setChecksumValidation(value)](#setchecksumvalidation) | 1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다. 기본값은 해당 심볼에 대해 Yes로 처리됩니다. |
| [setDetectEncoding()](#setdetectencoding) | Unicode 코드셋에 대한 코드텍스트 인코딩을 엔진이 감지하도록 강제하는 플래그입니다. 기본값은 true입니다. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | 인식에 명시적으로 지정된 바코드 유형만 반환합니다. 활성화하면 다른 호환 가능한 ... |
| [setStripFNC(value)](#setstripfnc) | 코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. 기본값은 false입니다. |

### getAustraliaPost() {#getaustraliapost}

AustraliaPost 디코딩 매개변수를 가져옵니다

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다. 기본값은 체크섬이 반드시 포함되어야 하는 심볼에 대해서는 Yes로, 체크섬이 선택적인 경우는 No로 처리됩니다. 체크섬이 사용되지 않는 경우: Codabar, PatchCode, Pharmacode, DataLogic2of5. 체크섬이 가능한 경우: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. 체크섬이 항상 사용되는 경우: 나머지 심볼.

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

Unicode 코드셋에 대한 코드텍스트 인코딩을 엔진이 감지하도록 강제하는 플래그입니다. 기본값은 true입니다.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. 기본값은 false입니다.

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

인식에 명시적으로 지정된 바코드 유형만 반환합니다. 활성화하면 다른 호환 또는 동등한 유형의 인식된 바코드가 필터링됩니다. 기본값은 false입니다. 예시: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다. 기본값은 체크섬이 반드시 포함되어야 하는 심볼에 대해서는 Yes로, 체크섬이 선택적인 경우는 No로 처리됩니다. 체크섬이 사용되지 않는 경우: Codabar, PatchCode, Pharmacode, DataLogic2of5. 체크섬이 가능한 경우: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. 체크섬이 항상 사용되는 경우: 나머지 심볼.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

Unicode 코드셋에 대한 코드텍스트 인코딩을 엔진이 감지하도록 강제하는 플래그입니다. 기본값은 true입니다.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

인식에 명시적으로 지정된 바코드 유형만 반환합니다. 활성화하면 다른 호환 또는 동등한 유형의 인식된 바코드가 필터링됩니다. 기본값은 false입니다. 예시: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. 기본값은 false입니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. 기본값은 false입니다. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
