---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
articleTitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Mode which enables or disables additional recognition of color barcodes on color images. This sample shows how to use ComplexBackground mode let reader = new..."
type: docs
weight: 160
url: /nodejs/aspose.barcode/complexbackgroundmode/
---

## ComplexBackgroundMode

Mode which enables or disables additional recognition of color barcodes on color images. This sample shows how to use ComplexBackground mode let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Values

| Name | Description |
| --- | --- |
| C_TABLE | Use C_TABLE to interpret the customer information. Allows A..Z, a..z, 1..9, space and # sing. |
| N_TABLE | Use N_TABLE to interpret the customer information. Allows digits. |
| OTHER | Do not interpret the customer information. Allows 0, 1, 2 or 3 symbol only. |
