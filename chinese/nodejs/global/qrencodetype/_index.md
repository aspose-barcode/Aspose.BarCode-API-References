---
title: "QREncodeType"
linktitle: "QREncodeType"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "QR / MicroQR 选择模式。"
type: docs
weight: 490
url: /zh/nodejs/global/qrencodetype/
---

## QREncodeType

QR / MicroQR 选择模式。选择 FORCE_QR 以获取标准 QR 符号，选择 AUTO 以获取 MicroQR。若可能，使用 FORCE_MICRO_QR 可强制生成 MicroQR 符号。

## 值

| 名称 | 描述 |
| --- | --- |
| AUTO | 模式从 MicroQR V1 开始条码版本协商 |
| FORCE_QR | 模式从 QR V1 开始条码版本协商 |
| FORCE_MICRO_QR | 模式从 MicroQR V1 到 V4 开始条码版本协商。如果数据无法编码为 MicroQR，将抛出异常。 |
