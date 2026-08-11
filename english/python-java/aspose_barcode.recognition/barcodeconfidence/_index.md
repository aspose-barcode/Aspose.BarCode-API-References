---
title: "BarCodeConfidence"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode for Python via Java"
description: "Contains recognition confidence level. This sample shows how BarCodeConfidence changed, depending on barcode type"
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition/barcodeconfidence/
---

## BarCodeConfidence enum

**Module:** `aspose_barcode.recognition.barcode_confidence`


Contains recognition confidence level. This sample shows how BarCodeConfidence changed, depending on barcode type


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [MODERATE](#moderate) | `"80"` | Recognition confidence of barcode (mostly 1D barcodes) with weak checksumm or even without it. Could contains some misrecognitions in codetext or even fake recognitions if is low |
| [NONE](#none) | `"0"` | Recognition confidence of barcode where codetext was not recognized correctly or barcode was detected as posible fake. |
| [STRONG](#strong) | `"100"` | Recognition confidence which was confirmed with BCH codes like Reed–Solomon. There must not be errors in read codetext or fake recognitions |
### BarCodeConfidence.MODERATE {#moderate}

**Type:** `string`

**Value:** `"80"`

Recognition confidence of barcode (mostly 1D barcodes) with weak checksumm or even without it. Could contains some misrecognitions in codetext or even fake recognitions if is low

### BarCodeConfidence.NONE {#none}

**Type:** `string`

**Value:** `"0"`

Recognition confidence of barcode where codetext was not recognized correctly or barcode was detected as posible fake.

### BarCodeConfidence.STRONG {#strong}

**Type:** `string`

**Value:** `"100"`

Recognition confidence which was confirmed with BCH codes like Reed–Solomon. There must not be errors in read codetext or fake recognitions

