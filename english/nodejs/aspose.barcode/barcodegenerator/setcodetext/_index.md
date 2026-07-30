---
title: "BarcodeGenerator.setCodeText"
linktitle: "setCodeText"
articleTitle: "setCodeText"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Encodes the Unicode `codeText ` into a byte sequence using the specified `encoding `. UTF-8 is the most commonly used encoding. If the encoding supports it a..."
type: docs
weight: 90
url: /nodejs/aspose.barcode/barcodegenerator/setcodetext/
---

## setCodeText(codeText, encoding, insertBOM)

Encodes the Unicode `codeText ` into a byte sequence using the specified `encoding `. UTF-8 is the most commonly used encoding. If the encoding supports it and `insertBOM ` is set to `true`, the function includes a `byte order mark (BOM) `. This function is intended for use with 2D barcodes only (e.g., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). It enables manual encoding of Unicode text using national or special encodings; however, this method is considered obsolete in modern applications. For modern use cases, `ECI ` encoding is recommended for Unicode data. Using this function with 1D barcodes, GS1-compliant barcodes (including 2D), or HIBC barcodes (including 2D) is not supported by the corresponding barcode standards and may lead to unpredictable results. This example shows how to use `SetCodeText` with or without a BOM for 2D barcodes. //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", true); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", false); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

| Parameter | Description |
| --- | --- |
| codeText | CodeText string |
| encoding | Applied encoding |
| insertBOM | Indicates whether to insert a byte order mark (BOM) when the specified encoding supports it (e.g., UTF-8, UTF-16, UTF-32). If set to `true`, the BOM is added; if `false`, the BOM is omitted even if the encoding normally uses one. |
