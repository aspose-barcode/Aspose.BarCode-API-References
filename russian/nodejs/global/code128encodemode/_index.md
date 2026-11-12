---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Режим кодирования для штрихкодов Code128."
type: docs
weight: 130
url: /ru/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Режим кодирования для штрихкодов Code128. Спецификация `Code 128`. Этот код демонстрирует, как генерировать код 128 с различными кодировками //Генерировать код 128 с кодировкой ISO 15417 let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Генерировать код 128 только с кодировкой Codeset A let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## Значения

| Имя | Описание |
| --- | --- |
| CODE_SET_A | Символы ASCII от 00 до 95 (0–9, A–Z и управляющие коды), специальные символы и FNC 1–4 /// |
| CODE_SET_B | Символы ASCII от 32 до 127 (0–9, A–Z, a–z), специальные символы и FNC 1–4 /// |
| CODE_SET_C | 00–99 (кодирует две цифры одним кодовым пунктом) и FNC1 /// |
