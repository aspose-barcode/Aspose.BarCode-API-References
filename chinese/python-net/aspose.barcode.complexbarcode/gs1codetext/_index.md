---
title: "GS1Codetext"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

表示用于编码和解码的 GS1 代码文本，作为有序序列的<br/>            应用标识符元素。保留源顺序和重复的应用标识符。 括号表示形式为 (AI)value(AI)value。<br/>            值中的文字左括号 '(' 必须写成 \\(; 这是唯一支持的转义序列。值中的右括号 ')' 不需要转义。

GS1Codetext 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| GS1Codetext() | 初始化 GS1Codetext 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| barcode_type | 获取或设置用于编码此 GS1 codetext 的条形码类型。<br/>            支持的类型有 GS1Aztec、GS1CodablockF、GS1Code128、GS1DataMatrix、<br/>            GS1DotCode、GS1HanXin、GS1MicroPdf417、GS1QR 和 GS1 DataBar 类型。<br/>            默认值为 GS1Code128。 |
| 计数 | 获取 Application Identifier 元素的数量。 |
| 元素 | 获取所有元素的副本，按源顺序排列。 |
## Indexer
| 名称 | 描述 |
| :- | :- |
| [index] | 按有序序列中的位置获取元素。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| get_first(application_identifier) | 获取应用标识符的第一个值。 |
| get_all(application_identifier) | 按源顺序获取应用标识符的所有值。 |
| add(application_identifier, value) | 追加已验证的应用标识符元素。 |
| validate(value) | 验证形式为 (AI)value(AI)value 的带括号 GS1 元素字符串，而不<br/>            构造对象。值中的文字 '(' 必须写成 \(；不支持其他转义序列，且 ')' 不需要转义。 |
| parse(value) | 解析形式为 (AI)value(AI)value 的带括号 GS1 元素字符串。值中的文字<br/>            '(' 必须写成 \(；不支持其他转义序列，且 ')' 不需要转义。 |
| try_parse(value, result, validation_result) | 尝试解析形式为 (AI)value(AI)value 的带括号 GS1 元素字符串<br/>            并返回结构化的验证错误。值中的文字 '(' 必须<br/>            写成 \(；不支持其他转义序列，且 ')' 不需要<br/>            转义。 |
| get_constructed_codetext() | 构造形式为 (AI)value(AI)value 的带括号 GS1 codetext。<br/>            值中的文字左括号需转义为 \(。 |
| init_from_string(constructed_codetext) | 从形式为 (AI)value(AI)value 的带括号 GS1 codetext 初始化此实例。<br/>            仅在成功解析提供的 codetext 后，才会替换已有元素。 |
| get_barcode_type() | 获取用于编码此 GS1 codetext 的条形码类型。 |

### 另见

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

