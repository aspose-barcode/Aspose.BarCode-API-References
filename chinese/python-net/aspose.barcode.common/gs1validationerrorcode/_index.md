---
title: "GS1ValidationErrorCode"
second_title: "Aspose.Sildes for Python via .NET API 参考文档"
description: 
type: docs
url: /zh/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

标识 GS1 元素字符串、Digital Link URI 或值的验证错误。

## Members
| 成员名称 | 描述 |
| :- | :- |
| EMPTY_ELEMENT_STRING | 提供的 GS1 元素字符串为空。 |
| MISSING_OPENING_PARENTHESIS | 缺少一个应该用于开始应用标识符的左括号。 |
| MISSING_CLOSING_PARENTHESIS | 应用标识符缺少右括号。 |
| INVALID_APPLICATION_IDENTIFIER | 应用标识符未包含两到四个 ASCII 数字。 |
| UNKNOWN_APPLICATION_IDENTIFIER | 提供的应用标识符未在受支持的 GS1 语法字典中定义。 |
| MISSING_VALUE | 出现了没有值的应用标识符。 |
| INVALID_ESCAPE_SEQUENCE | 一个值包含不受支持的转义序列。仅支持 \(。 |
| VALUE_TOO_SHORT | 该值短于其应用标识符定义的最小长度。 |
| VALUE_TOO_LONG | 该值长于其应用标识符定义的最大长度。 |
| INVALID_CHARACTER | 该值包含超出其组件允许字符集的字符。 |
| INVALID_CHECKSUM | 数字或字母校验和无效。 |
| INVALID_DATE | 根据其应用标识符定义的规则，日期组件不是有效日期。 |
| INVALID_TIME | 时间组件超出其允许的范围或结构无效。 |
| INVALID_CODE_LIST_VALUE | 组件值未出现在其允许的封闭代码列表中。 |
| INVALID_COMPONENT_LENGTH | 组件未满足其特定的长度结构。 |
| TRUNCATED_COMPONENT | 固定长度组件在所有必需字符出现之前就结束。 |
| UNEXPECTED_DATA | 在消耗完应用标识符定义的所有组件后仍有数据残留。 |
| INVALID_VALUE | 组件违反了一条内容规则，而该规则没有更具体的验证错误代码。 |
| GCP_PREFIX_TOO_SHORT | 组件太短，无法容纳最少四位的结构化 GS1 公司前缀。 |
| INVALID_GCP_PREFIX | 结构化的 GS1 公司前缀包含非 ASCII 数字的字符。 |
| INVALID_DIGITAL_LINK_URI | 提供的值不是格式良好的绝对 GS1 Digital Link URI。 |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | GS1 Digital Link URI 使用了非 HTTP 或 HTTPS 的方案。 |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | GS1 Digital Link URI 路径未包含受支持的主键。 |
| INVALID_DIGITAL_LINK_PATH | GS1 Digital Link URI 路径未由有效的 AI 与值对组成。 |
| INVALID_DIGITAL_LINK_QUALIFIER | 路径应用标识符在该位置不是允许的限定符。 |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | GS1 Digital Link 查询参数格式错误。 |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | 不允许将应用标识符用作 GS1 Digital Link 数据属性。 |
| INVALID_PERCENT_ENCODING | GS1 Digital Link URI 组件包含格式错误的百分号编码。 |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | 可以选择多个元素作为 GS1 Digital Link 主键。 |
| UNSUPPORTED_ELEMENT_COMBINATION | 所提供的 GS1 元素组合不受所选符号或编码模式的支持。 |

### 另见

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

