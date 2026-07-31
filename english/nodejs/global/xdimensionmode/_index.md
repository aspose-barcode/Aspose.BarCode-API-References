---
title: "XDimensionMode"
linktitle: "XDimensionMode"
articleTitle: "XDimensionMode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. This sample shows how to use XDimension mode let reader..."
type: docs
weight: 620
url: /nodejs/global/xdimensionmode/
---

## XDimensionMode

Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. This sample shows how to use XDimension mode let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setXDimension(XDimensionMode.SMALL); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }
