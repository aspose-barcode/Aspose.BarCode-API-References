---
title: "EnableChecksum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "在生成 1D 条码时启用校验和。"
type: docs
weight: 250
url: /zh/nodejs/global/enablechecksum/
---

## EnableChecksum

在生成 1D 条码时启用校验和。默认情况下，对于必须包含校验和的符号视为 Yes，对于仅可能包含校验和的符号视为 No。校验和从不使用的符号：Codabar。校验和可能的符号：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN。校验和始终使用的符号：其余符号。

## 值

| 名称 | 描述 |
| --- | --- |
| DEFAULT | 如果规范要求校验和——将会附加校验和。 |
| YES | 如果可能，始终使用校验和。 |
| NO | 不要使用校验和。 |
