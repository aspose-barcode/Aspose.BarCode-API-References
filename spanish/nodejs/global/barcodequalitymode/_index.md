---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Modo que habilita métodos para reconocer elementos del código de barras con la calidad seleccionada."
type: docs
weight: 80
url: /es/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

Modo que permite a los métodos reconocer elementos de código de barras con la calidad seleccionada. Un elemento de código de barras con calidad inferior requiere métodos más intensivos, lo que ralentiza el reconocimiento. Este ejemplo muestra cómo usar el modo BarcodeQuality let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Valores

| Nombre | Descripción |
| --- | --- |
| SÓLIDO | Especifica una línea sólida. |
| GUION | Especifica una línea compuesta de guiones. |
| PUNTO | Especifica una línea compuesta de puntos. |
| DASH_DOT | Especifica una línea con un patrón repetido de guion-punto. |
| DASH_DOT_DOT | Especifica una línea con un patrón repetido de guion-punto-punto. |
