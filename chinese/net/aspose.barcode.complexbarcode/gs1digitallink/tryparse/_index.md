---
title: "GS1DigitalLink.TryParse"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "GS1DigitalLink 方法。尝试解析未压缩的 GS1 Digital Link URI 并返回结构化的验证错误"
type: docs
weight: 190
url: /zh/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

尝试解析未压缩的 GS1 Digital Link URI 并返回结构化的验证错误。

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 字符串 | 要解析的 GS1 Digital Link URI。 |
| 结果 | GS1DigitalLink& | 当此方法返回 true 时，包含已解析的 GS1 Digital Link；否则为 null。 |
| validationResult | GS1ValidationResult& | 包含验证结果，或当 *value* 为 null 时返回 null。 |

### 返回值

解析成功时为 True；否则为 false。

### 另见

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


