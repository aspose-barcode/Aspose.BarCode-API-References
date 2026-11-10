---
title: "GS1Codetext.TryParse"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "GS1Codetext 方法。尝试解析括号形式的 GS1 元素字符串，格式为 AIvalueAIvalue，并返回结构化的验证错误。值中的文字  必须写成  ，不支持其他转义序列，且  不需要转义。"
type: docs
weight: 140
url: /zh/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

尝试解析括号形式的 GS1 元素字符串（格式为 (AI)value(AI)value），并返回结构化的验证错误。值中的字面 '(' 必须写成 \\(; 不支持其他转义序列，')' 不需要转义。

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 字符串 | 待解析的括号形式的 GS1 元素字符串。 |
| 结果 | GS1Codetext& | 当此方法返回 true 时，包含已解析的 GS1 编码文本；否则为 null。 |
| validationResult | GS1ValidationResult& | 包含验证结果，或当 *value* 为 null 时返回 null。 |

### 返回值

解析成功时为 True；否则为 false。

### 另见

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


