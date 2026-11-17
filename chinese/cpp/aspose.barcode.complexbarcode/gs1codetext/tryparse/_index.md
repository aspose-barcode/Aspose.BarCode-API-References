---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 参考"
description: " method. 尝试解析形式为 (AI)value(AI)value 的带括号的 GS1 元素字符串，并返回结构化的验证错误。值中的字面字符 ''('' 必须写成 (; 不支持其他转义序列，且 '')'' 在 C++ 中无需转义。"
type: docs
weight: 1600
url: /zh/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


尝试解析括号形式的 GS1 元素字符串，格式为 (AI)value(AI)value，并返回结构化的验证错误。值中的文字 '(' 必须写成 (；不支持其他转义序列，')' 不需要转义。

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| value | System::String | 待解析的带括号的 GS1 元素字符串。 |
| result | System::SharedPtr\<GS1Codetext\>\& | 当此方法返回 true 时，包含已解析的 GS1 编码文本；否则为 null。 |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | 包含验证结果，或在 *value* 为 null 时返回 null。 |

### ReturnValue

当解析成功时为 True；否则为 false。

## 另见

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
