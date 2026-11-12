---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "Code128 バーコードのエンコーディングモードです。"
type: docs
weight: 130
url: /ja/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Code128 バーコードのエンコーディングモードです。 `Code 128` 仕様です。このコードは、異なるエンコーディングで Code 128 を生成する方法を示しています //Generate code 128 with ISO 15417 encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generate code 128 only with Codeset A encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## 値

| 名前 | 説明 |
| --- | --- |
| CODE_SET_A | ASCII 文字 00 から 95（0–9、A–Z および制御コード）、特殊文字、そして FNC 1–4 /// |
| CODE_SET_B | ASCII 文字 32 から 127（0–9、A–Z、a–z）、特殊文字、そして FNC 1–4 /// |
| CODE_SET_C | 00–99（単一コードポイントで2桁をエンコード）と FNC1 /// |
