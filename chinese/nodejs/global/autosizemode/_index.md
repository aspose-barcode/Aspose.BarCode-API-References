---
title: "AutoSizeMode"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "指定不同类型的自动尺寸模式。"
type: docs
weight: 20
url: /zh/nodejs/global/autosizemode/
---

## AutoSizeMode

指定不同类型的自动尺寸模式。默认值为 AutoSizeMode.NONE。

## 值

| 名称 | 描述 |
| --- | --- |
| 无 | 自动调整大小已禁用。默认值。 |
| NEAREST | 条形码会调整为最近的最低可能尺寸，该尺寸由 BarCodeWidth 和 BarCodeHeight 属性指定。 |
| INTERPOLATION | 将条形码调整为指定尺寸，缩放幅度较小，但由于使用插值进行缩放，某些情况下可能会略有损坏。尺寸可通过 BarcodeGenerator.BarCodeWidth 和 BarcodeGenerator.BarCodeHeight 属性指定。 |
