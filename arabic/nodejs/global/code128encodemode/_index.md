---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "وضع الترميز لباركودات Code128."
type: docs
weight: 130
url: /ar/nodejs/global/code128encodemode/
---

## Code128EncodeMode

وضع الترميز لباركودات Code128. مواصفة `Code 128`. يوضح هذا الكود كيفية إنشاء code 128 بترميزات مختلفة //Generate code 128 with ISO 15417 encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generate code 128 only with Codeset A encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## القيم

| اسم | الوصف |
| --- | --- |
| CODE_SET_A | أحرف ASCII من 00 إلى 95 (0–9، A–Z والرموز التحكمية)، أحرف خاصة، وFNC 1–4 /// |
| CODE_SET_B | أحرف ASCII من 32 إلى 127 (0–9، A–Z، a–z)، أحرف خاصة، وFNC 1–4 /// |
| CODE_SET_C | 00–99 (يشفّر رقمين باستخدام نقطة شفرة واحدة) وFNC1 /// |
