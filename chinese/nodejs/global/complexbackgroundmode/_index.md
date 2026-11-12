---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "此模式启用或禁用对彩色图像中彩色条形码的额外识别。"
type: docs
weight: 160
url: /zh/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

此模式启用或禁用对彩色图像中彩色条码的额外识别。此示例展示了如何使用 ComplexBackground 模式 let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## 值

| 名称 | 描述 |
| --- | --- |
| C_TABLE | 使用 C_TABLE 解释客户信息。允许 A..Z、a..z、1..9、空格和 # 符号。 |
| N_TABLE | 使用 N_TABLE 解释客户信息。允许数字。 |
| OTHER | 不要解释客户信息。仅允许 0、1、2 或 3 符号。 |
