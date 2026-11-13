---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix 参数。

DataMatrixParameters 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| ecc_type | 获取或设置 Datamatrix ECC 类型。<br/>            默认值: DataMatrixEccType.Ecc200。 |
| version | 获取或设置 Datamatrix 符号大小。<br/>            默认值: Version.Auto。 |
| encode_mode | Datamatrix 条码的编码模式。<br/>            默认值: EncodeMode.Auto。 |
| structured_append_barcode_id | Datamatrix 条码的结构化追加模式的条码 ID。<br/>            默认值: 0 |
| structured_append_barcodes_count | Datamatrix 条码的结构化追加模式的条码计数。<br/>            默认值: 0 |
| structured_append_file_id | Datamatrix 条码的结构化追加模式的文件 ID。<br/>            默认值: 0 |
| is_reader_programming | 用于指示读取器将符号中包含的数据<br/>            解释为读取器初始化的编程。<br/>            默认值: false |
| macro_characters | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。<br/>            只能与 DataMatrixEccType.Ecc200 或 DataMatrixEccType.EccAuto 一起使用。<br/>            不能与 EncodeTypes.GS1DataMatrix 一起使用<br/>            默认值: MacroCharacters.None。 |
| aspect_ratio | 2D 条码模块的高/宽比例。 |
| eci_encoding | 获取或设置 ECI 编码。当 EncodeMode 为 Auto 时使用。<br/>            默认值：ISO-8859-1 |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

