---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Modalità che abilita i metodi per riconoscere gli elementi del codice a barre con la qualità selezionata."
type: docs
weight: 80
url: /it/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento. Questo esempio mostra come utilizzare la modalità BarcodeQuality let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Valori

| Nome | Descrizione |
| --- | --- |
| SOLID | Specifica una linea solida. |
| DASH | Specifica una linea composta da trattini. |
| DOT | Specifica una linea composta da punti. |
| DASH_DOT | Specifica una linea composta da un pattern ripetuto di trattino-punto. |
| DASH_DOT_DOT | Specifica una linea composta da un pattern ripetuto di trattino-punto-punto. |
