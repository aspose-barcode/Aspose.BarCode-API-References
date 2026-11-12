---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (luminance)."
type: docs
weight: 370
url: /ru/nodejs/global/inverseimagemode/
---

## InverseImageMode

Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (яркость). Этот пример показывает, как использовать режим InverseImage let reader = new BarCodeReader(\"test.png\", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log(\"BarCode CodeText: \" + result.getCodeText()); }

## Значения

| Имя | Описание |
| --- | --- |
| NONE | Нет границы, охватывающей штрих-код |
| FRAME | FRAME, охватывающая штрих-код |
| BAR | Две горизонтальные полосы, охватывающие штрих-код |
| FRAME_OUT | FRAME, охватывающая штрих-код |
| BAR_OUT | Две горизонтальные полосы, охватывающие штрих-код |
