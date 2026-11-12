---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes en color."
type: docs
weight: 160
url: /es/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color. Este ejemplo muestra cómo usar el modo ComplexBackground let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Valores

| Nombre | Descripción |
| --- | --- |
| C_TABLE | Utilice C_TABLE para interpretar la información del cliente. Permite A..Z, a..z, 1..9, espacio y el símbolo #. |
| N_TABLE | Utilice N_TABLE para interpretar la información del cliente. Permite dígitos. |
| OTHER | No interprete la información del cliente. Permite solo el símbolo 0, 1, 2 o 3. |
