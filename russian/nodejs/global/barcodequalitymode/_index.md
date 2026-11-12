---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Режим, который включает методы распознавания элементов штрихкода с выбранным качеством."
type: docs
weight: 80
url: /ru/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

Режим, который позволяет методам распознавать элементы штрих‑кода с выбранным качеством. Элемент штрих‑кода с более низким качеством требует более сложных методов, что замедляет распознавание. Этот пример показывает, как использовать режим BarcodeQuality let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Значения

| Имя | Описание |
| --- | --- |
| SOLID | Указывает сплошную линию. |
| DASH | Указывает линию, состоящую из тире. |
| DOT | Указывает линию, состоящую из точек. |
| DASH_DOT | Указывает линию, состоящую из повторяющегося шаблона тире‑точка. |
| DASH_DOT_DOT | Указывает линию, состоящую из повторяющегося шаблона тире‑точка‑точка. |
