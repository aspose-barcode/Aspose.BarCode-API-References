---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "启用使用所选质量识别条形码元素的方法的模式。"
type: docs
weight: 80
url: /zh/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

此模式启用方法以使用所选质量识别条形码元素。质量较低的条形码元素需要更多复杂的方法，从而减慢识别速度。此示例展示如何使用 BarcodeQuality 模式 let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## 值

| 名称 | 描述 |
| --- | --- |
| SOLID | 指定实线。 |
| DASH | 指定由短划线组成的线。 |
| DOT | 指定由点组成的线。 |
| DASH_DOT | 指定由短划线-点的重复模式组成的线。 |
| DASH_DOT_DOT | 指定由短划线-点-点的重复模式组成的线。 |
