---
title: "BarCodeConfidence Enum"
linktitle: "BarCodeConfidence"
articleTitle: "BarCodeConfidence"
second_title: "Aspose.BarCode for PHP via Java"
description: "Contains recognition confidence level This sample shows how BarCodeConfidence changed, depending on barcode type Moderate confidence Strong confidence"
type: docs
weight: 10
url: /php/aspose/barcode/recognition/barcodeconfidence/
---

## BarCodeConfidence enum

**Namespace:** `Aspose.Barcode.Recognition`


Contains recognition confidence level This sample shows how BarCodeConfidence changed, depending on barcode type Moderate confidence Strong confidence


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [MODERATE](/php/aspose/barcode/recognition/barcodeconfidence/moderate/) | `80` | Recognition confidence of barcode (mostly 1D barcodes) with weak checksumm or even without it. Could contains some misrecognitions in codetext or even fake recognitions if is low |
| [NONE](/php/aspose/barcode/recognition/barcodeconfidence/none/) | `0` | Recognition confidence of barcode where codetext was not recognized correctly or barcode was detected as posible fake |
| [STRONG](/php/aspose/barcode/recognition/barcodeconfidence/strong/) | `100` | Recognition confidence which was confirmed with BCH codes like Reed–Solomon. There must not be errors in read codetext or fake recognitions |
