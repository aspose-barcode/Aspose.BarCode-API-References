---
title: "GS1DigitalLink"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

表示用于编码和解码的 GS1 Digital Link 代码文本，作为有序序列的<br/>            应用标识符元素。保留源顺序和重复的应用标识符。<br/>            构造的代码文本是未压缩的 GS1 Digital Link URI。<br/>            解析时会忽略非 GS1 查询参数和 URI 片段。

GS1DigitalLink 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| GS1DigitalLink(uri_stem) | 初始化 GS1DigitalLink 类的新实例 |
| GS1DigitalLink(uri_stem, primary_application_identifier) | 初始化 GS1DigitalLink 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| uri_stem | 获取 GS1 主键路径段之前的绝对 URI 前缀。<br/>            该 stem 不包含查询字符串或片段。 |
| primary_application_identifier | 获取用作 Digital Link 主键的应用标识符。<br/>            Null 表示在构建 URI 时会自动选择主键。 |
| barcode_type | 获取或设置用于编码此 GS1 Digital Link 的条形码类型。<br/>            支持的类型有 QR、DataMatrix、Aztec、Pdf417、MicroPdf417、DotCode、HanXin、CodablockF 和 Code128。<br/>            默认值为 QR。 |
| 计数 | 获取 Application Identifier 元素的数量。 |
| 元素 | 获取所有元素的副本，按源顺序排列。 |
## Indexer
| 名称 | 描述 |
| :- | :- |
| [index] | 按有序序列中的位置获取元素。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| create(uri_stem, codetext) | 通过从 GS1 codetext 复制所有元素并选择唯一可用的主键来创建 GS1 Digital Link。<br/>             |
| create(uri_stem, codetext, primary_application_identifier) | 通过从 GS1 codetext 复制所有元素并选择唯一可用的主键来创建 GS1 Digital Link。<br/>             |
| get_first(application_identifier) | 获取应用标识符的第一个值。 |
| get_all(application_identifier) | 按源顺序获取应用标识符的所有值。 |
| add(application_identifier, value) | 追加已验证的应用标识符元素。 |
| validate(value) | 在不构建对象的情况下验证未压缩的 GS1 Digital Link URI。 |
| parse(value) | 解析未压缩的 GS1 Digital Link URI。 |
| try_parse(value, result, validation_result) | 尝试解析未压缩的 GS1 Digital Link URI 并返回结构化的验证错误。 |
| to_gs1_codetext() | 创建一个独立的 GS1 codetext，包含当前的 GS1 元素。<br/>            不包括仅限 URI 的信息。 |
| to_uri_string() | 将当前对象状态格式化为未压缩的 GS1 Digital Link URI。 |
| get_constructed_codetext() | 构建未压缩的 GS1 Digital Link URI。 |
| init_from_string(constructed_codetext) | 从未压缩的 GS1 Digital Link URI 初始化此实例。<br/>            仅在成功解析提供的 URI 后才会替换现有状态。<br/>            所选的条码类型将被保留。 |
| get_barcode_type() | 获取用于编码此 GS1 Digital Link 的条码类型。 |

### 另见

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

