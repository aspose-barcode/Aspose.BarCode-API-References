---
title: "QualitySettings.getMaxQuality"
linktitle: "getMaxQuality"
articleTitle: "getMaxQuality"
second_title: "Aspose.BarCode for Node.js via Java"
description: "MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes. This sample shows how to use Max..."
type: docs
weight: 30
url: /nodejs/aspose.barcode/qualitysettings/getmaxquality/
---

## getMaxQuality() (static)

MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes. This sample shows how to use MaxQuality mode reader = new BarCodeReader("test.png"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Value: MaxQuality recognition quality preset.
