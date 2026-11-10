---
title: "GS1Codetext.Validate"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "GS1Codetext 方法。验证形式为 AIvalueAIvalue 的括号化 GS1 元素字符串，而无需构造对象。值内部的文字  必须写成  ，不支持其他转义序列，且  不需要转义"
type: docs
weight: 150
url: /zh/net/aspose.barcode.complexbarcode/gs1codetext/validate/
---
## GS1Codetext.Validate method

在不构建对象的情况下验证括号形式的 GS1 元素字符串（格式为 (AI)value(AI)value）。值中的字面 '(' 必须写成 \\(; 不支持其他转义序列，')' 不需要转义。

```csharp
public static GS1ValidationResult Validate(string value)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 字符串 | 待验证的括号化 GS1 元素字符串。 |

### 返回值

结构化验证结果。

### 另见

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


