---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Modus, der die zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert."
type: docs
weight: 370
url: /de/nodejs/global/inverseimagemode/
---

## InverseImageMode

Modus, der die zusätzliche Erkennung von Strichcodes auf Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert. Dieses Beispiel zeigt, wie man den InverseImage-Modus verwendet let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Werte

| Name | Beschreibung |
| --- | --- |
| NONE | Kein Rand um den Barcode |
| RAHMEN | RAHMEN, der den Barcode umschließt |
| STREIFEN | Zwei horizontale Balken, die den Barcode umschließen |
| FRAME_OUT | RAHMEN, der den Barcode umschließt |
| BAR_OUT | Zwei horizontale Balken, die den Barcode umschließen |
