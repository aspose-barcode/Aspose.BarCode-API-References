---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "Code128 바코드에 대한 인코딩 모드."
type: docs
weight: 130
url: /ko/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Code128 바코드에 대한 인코딩 모드. `Code 128` 사양. 이 코드는 다양한 인코딩으로 code 128을 생성하는 방법을 보여줍니다. //Generate code 128 with ISO 15417 encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generate code 128 only with Codeset A encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## 값

| 이름 | 설명 |
| --- | --- |
| CODE_SET_A | ASCII 문자 00~95 (0–9, A–Z 및 제어 코드), 특수 문자, 및 FNC 1–4 /// |
| CODE_SET_B | ASCII 문자 32~127 (0–9, A–Z, a–z), 특수 문자, 및 FNC 1–4 /// |
| CODE_SET_C | 00–99 (단일 코드 포인트로 두 자리 숫자를 인코딩) 및 FNC1 /// |
