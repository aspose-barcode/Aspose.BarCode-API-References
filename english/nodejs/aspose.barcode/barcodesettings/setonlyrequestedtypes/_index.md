---
title: "BarcodeSettings.setOnlyRequestedTypes"
linktitle: "setOnlyRequestedTypes"
articleTitle: "setOnlyRequestedTypes"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Returns only barcode types explicitly specified for recognition. When enabled, recognized barcodes of other compatible or equivalent types are filtered out. ..."
type: docs
weight: 80
url: /nodejs/aspose.barcode/barcodesettings/setonlyrequestedtypes/
---

## setOnlyRequestedTypes()

Returns only barcode types explicitly specified for recognition. When enabled, recognized barcodes of other compatible or equivalent types are filtered out. Default value is false. Example: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false
