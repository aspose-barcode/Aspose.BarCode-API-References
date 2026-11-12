---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "백엔드 복합 바코드용 ComplexBarcodeGenerator (예:"
type: docs
weight: 280
url: /ko/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

백엔드 복합 바코드(예: SwissQR) 이미지 생성을 위한 ComplexBarcodeGenerator.

```js
new ComplexBarcodeGenerator(complexCodetext)
```

ComplexBarcodeGenerator의 인스턴스를 생성합니다.

| 매개변수 | 설명 |
| --- | --- |
| complexCodetext | 복합 코드텍스트 |

**Example:**

```js
This sample shows how to create and save a SwissQR image.
   let swissQRCodetext = new SwissQRCodetext(null);
   swissQRCodetext.getBill().setAccount("Account");
   swissQRCodetext.getBill().setBillInformation("BillInformation");
   swissQRCodetext.getBill().setBillInformation("BillInformation");
   swissQRCodetext.getBill().setAmount(1024);
   swissQRCodetext.getBill().getCreditor().setName("Creditor.Name");
   swissQRCodetext.getBill().getCreditor().setAddressLine1("Creditor.AddressLine1");
   swissQRCodetext.getBill().getCreditor().setAddressLine2("Creditor.AddressLine2");
   swissQRCodetext.getBill().getCreditor().setCountryCode("Nl");
   swissQRCodetext.getBill().setUnstructuredMessage("UnstructuredMessage");
   swissQRCodetext.getBill().setReference("Reference");
   swissQRCodetext.getBill().setAlternativeSchemes([new AlternativeScheme("AlternativeSchemeInstruction1"),new AlternativeScheme("AlternativeSchemeInstruction2")]);
   swissQRCodetext.getBill().setDebtor(new Address(null));
   swissQRCodetext.getBill().getDebtor().setName("Debtor.Name");
   swissQRCodetext.getBill().getDebtor().setAddressLine1("Debtor.AddressLine1");
   swissQRCodetext.getBill().getDebtor().setAddressLine2("Debtor.AddressLine2");
   swissQRCodetext.getBill().getDebtor().setCountryCode("Lux");
   let cg = new ComplexBarcodeGenerator(swissQRCodetext);
   let res = cg.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | 현재 설정으로 복합 바코드 이미지를 생성합니다. |
| [getParameters()](#getparameters) | 생성 매개변수. |
| [save(filePath, format)](#save) | 현재 설정으로 복합 바코드 이미지를 생성하고 저장합니다. |

### generateBarCodeImage() {#generatebarcodeimage}

현재 설정으로 복합 바코드 이미지를 생성합니다.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

생성 매개변수.

### save(filePath, format) {#save}

현재 설정으로 복합 바코드 이미지를 생성하고 저장합니다.

| 매개변수 | 설명 |
| --- | --- |
| filePath | 저장할 경로. |
| 형식 | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
