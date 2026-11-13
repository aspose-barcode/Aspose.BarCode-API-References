---
title: "AztecParameters"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/aztecparameters/
---

## AztecParameters class

Aztec 参数。

AztecParameters 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| encode_mode | 获取或设置 Aztec 编码模式。 <br/>            默认值: Auto. |
| eci_encoding | 获取或设置 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。<br/>            默认值: ISO-8859-1 |
| structured_append_barcode_id | Aztec 条码的结构化追加模式的条码 ID。条码 ID 应在 1 到条码总数的范围内。<br/>            默认值: 0 |
| structured_append_barcodes_count | Aztec 条形码的结构追加模式的条码计数。条码计数应在 1 到 26 的范围内。<br/>            默认值：0 |
| structured_append_file_id | Aztec 条形码结构追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。<br/>            默认值：空字符串 |
| error_level | Aztec 条形码的错误纠正级别。<br/>            值应在 5 到 95 之间。 |
| symbol_mode | 获取或设置 Aztec 符号模式。<br/>            默认值：AztecSymbolMode.Auto。 |
| layers_count | 获取或设置 Aztec 符号的层数。紧凑模式下层数应在 1 到 3 的范围内，<br/>            完全范围模式下应在 1 到 32 的范围内。<br/>            默认值：0（自动）。 |
| is_reader_initialization | 用于指示读取器将符号中包含的数据<br/>            解释为读取器初始化的编程。 |
| aspect_ratio | 2D 条码模块的高/宽比例。 |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

