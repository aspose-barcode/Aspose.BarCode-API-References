---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia)."
type: docs
weight: 370
url: /es/nodejs/global/inverseimagemode/
---

## InverseImageMode

Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). Este ejemplo muestra cómo usar el modo InverseImage let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Valores

| Nombre | Descripción |
| --- | --- |
| NONE | Sin borde que rodea el código de barras |
| MARCO | MARCO que rodea el código de barras |
| BARRA | Dos barras horizontales que rodean el código de barras |
| FRAME_OUT | MARCO que rodea el código de barras |
| BAR_OUT | Dos barras horizontales que rodean el código de barras |
