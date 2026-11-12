---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "AustraliaPost 디코딩 매개변수."
type: docs
weight: 30
url: /ko/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

AustraliaPost 디코딩 매개변수. AustraliaPost 심볼리즘의 인식된 데이터에 영향을 주는 매개변수를 포함합니다.

```js
new AustraliaPostSettings()
```

AustraliaPostSettings 생성자

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | AustralianPost BarCode의 고객 정보에 대한 해석 유형을 가져옵니다. DEFAULT는 CustomerInformationInterpre입니다. |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | 디코딩 중에 고객 정보 필드의 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그 |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | AustralianPost BarCode의 고객 정보에 대한 해석 유형을 설정합니다. DEFAULT는 CustomerInformationInterpre입니다. |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | 디코딩 중에 고객 정보 필드의 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그 |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

AustralianPost BarCode의 고객 정보에 대한 해석 유형을 가져옵니다. DEFAULT는 CustomerInformationInterpretingType.OTHER입니다.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

디코딩 중에 CTable 방식으로 고객 정보 필드의 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그입니다. CTable 인코딩 방식은 인코딩 테이블에 빈틈이 없으며, 채우기 패턴 시퀀스 "333"은 문자 "z"로 디코딩됩니다.

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setCustomerInformationInterpretingType(value) {#setcustomerinformationinterpretingtype}

AustralianPost BarCode의 고객 정보에 대한 해석 유형을 설정합니다. DEFAULT는 CustomerInformationInterpretingType.OTHER입니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | AustralianPost BarCode에 대한 고객 정보의 해석 유형(CTable, NTable 또는 Other) |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

디코딩 중에 CTable 방식으로 고객 정보 필드의 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그입니다. CTable 인코딩 방식은 인코딩 테이블에 빈틈이 없으며, 채우기 패턴 시퀀스 "333"은 문자 "z"로 디코딩됩니다.

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```
