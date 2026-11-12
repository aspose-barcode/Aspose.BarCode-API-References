---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях."
type: docs
weight: 160
url: /ru/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. Этот пример показывает, как использовать режим ComplexBackground let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Значения

| Имя | Описание |
| --- | --- |
| C_TABLE | Используйте C_TABLE для интерпретации информации о клиенте. Разрешены A..Z, a..z, 1..9, пробел и символ #. |
| N_TABLE | Используйте N_TABLE для интерпретации информации о клиенте. Разрешены цифры. |
| OTHER | Не интерпретировать информацию о клиенте. Разрешён только символ 0, 1, 2 или 3. |
