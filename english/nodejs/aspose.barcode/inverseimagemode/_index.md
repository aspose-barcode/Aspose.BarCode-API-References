---
title: "InverseImageMode"
linktitle: "InverseImageMode"
articleTitle: "InverseImageMode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). This sample shows how to use InverseImage mode ..."
type: docs
weight: 370
url: /nodejs/aspose.barcode/inverseimagemode/
---

## InverseImageMode

Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). This sample shows how to use InverseImage mode let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Values

| Name | Description |
| --- | --- |
| NONE | NO border enclosing the barcode |
| FRAME | FRAME enclosing the barcode |
| BAR | Tow horizontal bars enclosing the barcode |
| FRAME_OUT | FRAME enclosing the barcode |
| BAR_OUT | Tow horizontal bars enclosing the barcode |
