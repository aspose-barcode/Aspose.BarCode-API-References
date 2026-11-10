---
title: "枚举 GS1ValidationErrorCode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode 枚举。标识 GS1 元素字符串 Digital Link URI 或值的验证错误"
type: docs
weight: 430
url: /zh/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

标识 GS1 元素字符串、Digital Link URI 或值验证错误。

```csharp
public enum GS1ValidationErrorCode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| EmptyElementString | `0` | 提供的 GS1 元素字符串为空。 |
| MissingOpeningParenthesis | `1` | 缺少应开始应用标识符的左括号。 |
| MissingClosingParenthesis | `2` | 应用标识符缺少右括号。 |
| InvalidApplicationIdentifier | `3` | 应用标识符未包含二至四个 ASCII 数字。 |
| UnknownApplicationIdentifier | `4` | 提供的应用标识符未在受支持的 GS1 语法字典中定义。 |
| MissingValue | `5` | 出现了没有值的应用标识符。 |
| InvalidEscapeSequence | `6` | 值包含不受支持的转义序列。仅支持 \(。 |
| ValueTooShort | `7` | 值的长度短于其应用标识符定义的最小长度。 |
| ValueTooLong | `8` | 值的长度长于其应用标识符定义的最大长度。 |
| InvalidCharacter | `9` | 值包含超出其组件允许字符集的字符。 |
| InvalidChecksum | `10` | 数字或字母校验和无效。 |
| InvalidDate | `11` | 根据其应用标识符定义的规则，日期组件不是有效日期。 |
| InvalidTime | `12` | 时间组件超出允许范围或结构无效。 |
| InvalidCodeListValue | `13` | 组件值未出现在其允许的封闭代码列表中。 |
| InvalidComponentLength | `14` | 组件未满足其特定长度结构。 |
| TruncatedComponent | `15` | 固定长度组件在所有必需字符出现之前结束。 |
| UnexpectedData | `16` | 在消耗完应用标识符定义的所有组件后仍有数据残留。 |
| InvalidValue | `17` | 组件违反了没有更具体验证错误代码的内容规则。 |
| GcpPrefixTooShort | `18` | 组件太短，无法容纳最小的四位结构化 GS1 公司前缀。 |
| InvalidGcpPrefix | `19` | 结构化的 GS1 公司前缀包含非 ASCII 数字的字符。 |
| InvalidDigitalLinkUri | `20` | 提供的值不是格式正确的绝对 GS1 Digital Link URI。 |
| UnsupportedDigitalLinkScheme | `21` | GS1 Digital Link URI 使用了除 HTTP 或 HTTPS 之外的方案。 |
| MissingDigitalLinkPrimaryKey | `22` | GS1 Digital Link URI 的路径不包含受支持的主键。 |
| InvalidDigitalLinkPath | `23` | GS1 Digital Link URI 的路径不由有效的 AI 与值对组成。 |
| InvalidDigitalLinkQualifier | `24` | 路径中的应用标识符在该位置不是允许的限定符。 |
| InvalidDigitalLinkQueryParameter | `25` | GS1 Digital Link 查询参数格式错误。 |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | 应用标识符不允许作为 GS1 Digital Link 数据属性。 |
| InvalidPercentEncoding | `27` | GS1 Digital Link URI 组件包含错误的百分号编码。 |
| MultipleDigitalLinkPrimaryKeys | `28` | 可以选择多个元素作为 GS1 Digital Link 的主键。 |
| UnsupportedElementCombination | `29` | 所提供的 GS1 元素组合不受所选符号或编码模式的支持。 |

### 另见

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


