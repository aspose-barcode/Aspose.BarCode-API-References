---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Modus, der Methoden aktiviert, um Barcode-Elemente mit der ausgewählten Qualität zu erkennen."
type: docs
weight: 80
url: /de/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

Modus, der Methoden ermöglicht, Barcode-Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode-Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt. Dieses Beispiel zeigt, wie man den BarcodeQuality-Modus verwendet let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Werte

| Name | Beschreibung |
| --- | --- |
| FEST | Gibt eine feste Linie an. |
| STRICH | Gibt eine Linie an, die aus Strichen besteht. |
| DOT | Gibt eine Linie an, die aus Punkten besteht. |
| DASH_DOT | Gibt eine Linie an, die aus einem wiederholenden Muster von Strich-Punkt besteht. |
| DASH_DOT_DOT | Gibt eine Linie an, die aus einem wiederholenden Muster von Strich-Punkt-Punkt besteht. |
