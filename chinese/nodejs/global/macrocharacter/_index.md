---
title: "MacroCharacter"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。"
type: docs
weight: 380
url: /zh/nodejs/global/macrocharacter/
---

## MacroCharacter

宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。05 宏字符被翻译为 "[)>\u001E05\u001D" 作为解码数据头部，"\u001E\u0004" 作为解码数据尾部。06 宏字符被翻译为 "[)>\u001E06\u001D" 作为解码数据头部，"\u001E\u0004" 作为解码数据尾部。这些示例展示了如何在 MicroPdf417 和 DataMatrix 中编码宏字符。

## 值

| 名称 | 描述 |
| --- | --- |
| AUTO | 自动确定 |
| TYPE_7 | 24 x 24 模块 |
| TYPE_9 | 32 x 32 模块 |
| TYPE_29 | 16 x 48 模块 |
