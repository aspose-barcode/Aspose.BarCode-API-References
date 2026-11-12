---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "Code128 条形码的编码模式。"
type: docs
weight: 130
url: /zh/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Code128 条形码的编码模式。 `Code 128` 规范。 此代码演示如何使用不同的编码生成 Code 128 //使用 ISO 15417 编码生成 Code 128 let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //仅使用 Codeset A 编码生成 Code 128 let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## 值

| 名称 | 描述 |
| --- | --- |
| CODE_SET_A | ASCII 字符 00 到 95（0–9，A–Z 和控制码），特殊字符，以及 FNC 1–4 /// |
| CODE_SET_B | ASCII 字符 32 到 127（0–9，A–Z，a–z），特殊字符，以及 FNC 1–4 /// |
| CODE_SET_C | 00–99（使用单个代码点编码两个数字）和 FNC1 /// |
