---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "백엔드 바코드 이미지 생성을 위한 BarcodeGenerator."
type: docs
weight: 130
url: /ko/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

백엔드 바코드 이미지 생성을 위한 BarcodeGenerator. 지원되는 심볼: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR 코드 ...

```js
new BarcodeGenerator(encodeType, codeText)
```

BarcodeGenerator 생성자.

| 매개변수 | 설명 |
| --- | --- |
| encodeType | 바코드 심볼 유형. 심볼을 설정하려면 EncodeTypes 클래스를 사용하십시오. |
| codeText | 인코딩할 텍스트. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | 지정된 xml 파일에서 BarCode 속성을 가져와 BarcodeGenerator 인스턴스를 생성합니다. |
| [exportToXml(filePath)](#exporttoxml) | 지정된 xml 파일로 BarCode 속성을 내보냅니다. |
| [generateBarCodeImage(format)](#generatebarcodeimage) | 현재 설정으로 바코드 이미지를 생성합니다. 이 샘플은 바코드 이미지를 만들고 저장하는 방법을 보여줍니다. |
| [getBarcodeType()](#getbarcodetype) | 바코드 심볼 유형. |
| [getCodeText()](#getcodetext) | 인코딩할 텍스트. |
| [getParameters()](#getparameters) | 생성 매개변수. |
| [save(filePath, format)](#save) | 바코드 이미지를 특정 형식의 특정 파일에 저장합니다. |
| [setBarcodeType()](#setbarcodetype) | 바코드 심볼 유형. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | 지정된 `encoding `을 사용하여 Unicode `codeText `를 바이트 시퀀스로 인코딩합니다. UTF-8이 가장 일반적으로 사용되는 en |

### importFromXml(filePath) (static) {#importfromxml}

지정된 xml 파일에서 BarCode 속성을 가져와 BarcodeGenerator 인스턴스를 생성합니다.

| 매개변수 | 설명 |
| --- | --- |
| filePath | 파일 이름 |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

지정된 xml 파일로 BarCode 속성을 내보냅니다.

| 매개변수 | 설명 |
| --- | --- |
| filePath | XML 파일 |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

현재 설정으로 바코드 이미지를 생성합니다. 이 샘플은 바코드 이미지를 만들고 저장하는 방법을 보여줍니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 형식 | BarCodeImageFormat | BarCodeImageFormat 값 (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

바코드 심볼 유형.

### getCodeText() {#getcodetext}

인코딩할 텍스트.

### getParameters() {#getparameters}

생성 매개변수.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

바코드 이미지를 특정 형식의 특정 파일에 저장합니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 저장할 경로. |
| 형식 | BarCodeImageFormat | BarCodeImageFormat 값 (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

바코드 심볼 유형.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

지정된 `encoding `을 사용하여 Unicode `codeText `를 바이트 시퀀스로 인코딩합니다. UTF-8이 가장 일반적으로 사용되는 인코딩입니다. 인코딩이 이를 지원하고 `insertBOM `가 `true`로 설정된 경우, 함수는 `byte order mark (BOM) `를 포함합니다. 이 함수는 2D 바코드 전용으로 설계되었습니다(e.g., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR 등). 국가별 또는 특수 인코딩을 사용한 Unicode 텍스트 수동 인코딩을 가능하게 하지만, 현대 애플리케이션에서는 이 방법이 구식으로 간주됩니다. 최신 사용 사례에서는 Unicode 데이터에 `ECI ` 인코딩을 권장합니다. 1D 바코드, GS1 호환 바코드(2D 포함) 또는 HIBC 바코드(2D 포함)와 함께 이 함수를 사용하면 해당 바코드 표준에서 지원되지 않으며 예측할 수 없는 결과가 발생할 수 있습니다. 이 예제는 2D 바코드에 대해 BOM을 사용하거나 사용하지 않을 때 `SetCodeText`를 사용하는 방법을 보여줍니다.
//Encode codetext using UTF-8 with BOM
let gen = new BarcodeGenerator(EncodeTypes.QR, null);
gen.setCodeText(\"車種名\", \"UTF-8\", true);
gen.save(\"barcode.png\", BarCodeImageFormat.PNG);
let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++) {
    let result = results[i];
    console.log(\"BarCode CodeText: \" + result.getCodeText());
}
//Encode codetext using UTF-8 without BOM
let gen = new BarcodeGenerator(EncodeTypes.QR, null);
gen.setCodeText(\"車種名\", \"UTF-8\", false);
gen.save(\"barcode.png\", BarCodeImageFormat.PNG);
let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++) {
    let result = results[i];
    console.log(\"BarCode CodeText: \" + result.getCodeText());
}

| 매개변수 | 설명 |
| --- | --- |
| codeText | CodeText 문자열 |
| 인코딩 | 적용된 인코딩 |
| insertBOM | 지정된 인코딩이 지원하는 경우 (예: UTF-8, UTF-16, UTF-32) 바이트 순서 표시(BOM)를 삽입할지 여부를 나타냅니다. `true`로 설정하면 BOM이 추가되고, `false`로 설정하면 인코딩이 일반적으로 BOM을 사용하더라도 BOM이 생략됩니다. |
