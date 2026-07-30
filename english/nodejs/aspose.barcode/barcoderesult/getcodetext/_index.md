---
title: "BarCodeResult.getCodeText"
linktitle: "getCodeText"
articleTitle: "getCodeText"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Gets the code text with encoding. This example shows how to use `getCodeText`: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText..."
type: docs
weight: 40
url: /nodejs/aspose.barcode/barcoderesult/getcodetext/
---

## getCodeText(encoding)

Gets the code text with encoding. This example shows how to use `getCodeText`: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| Parameter | Description |
| --- | --- |
| encoding | The encoding for codetext. |

**Returns:** A string containing recognized code text.
