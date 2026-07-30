---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
articleTitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows..."
type: docs
weight: 80
url: /nodejs/aspose.barcode/barcodequalitymode/
---

## BarcodeQualityMode

Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition. This sample shows how to use BarcodeQuality mode let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Values

| Name | Description |
| --- | --- |
| SOLID | Specifies a solid line. |
| DASH | Specifies a line consisting of dashes. |
| DOT | Specifies a line consisting of dots. |
| DASH_DOT | Specifies a line consisting of a repeating pattern of dash-dot. |
| DASH_DOT_DOT | Specifies a line consisting of a repeating pattern of dash-dot-dot. |
