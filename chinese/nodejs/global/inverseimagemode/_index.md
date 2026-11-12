---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "启用或禁用对颜色反转（亮度）图像中条形码的额外识别的模式。"
type: docs
weight: 370
url: /zh/nodejs/global/inverseimagemode/
---

## InverseImageMode

该模式用于在颜色（亮度）反转的图像上启用或禁用条码的额外识别。此示例展示了如何使用 InverseImage 模式 let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## 值

| 名称 | 描述 |
| --- | --- |
| 无 | 无包围条形码的边框 |
| FRAME | 框架包围条形码 |
| BAR | 两个水平条围绕条形码 |
| FRAME_OUT | 框架包围条形码 |
| BAR_OUT | 两个水平条围绕条形码 |
