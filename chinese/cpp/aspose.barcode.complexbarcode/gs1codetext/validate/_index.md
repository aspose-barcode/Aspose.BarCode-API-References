---
title: "method"
linktitle: "Validate"
second_title: "Aspose.BarCode for C++ API 参考"
description: "方法。验证形式为 (AI)value(AI)value 的括号式 GS1 元素字符串，而不构造对象。值中的文字 ''('' 必须写成 (；不支持其他转义序列，且 '')'' 在 C++ 中不需要转义。"
type: docs
weight: 1400
url: /zh/cpp/aspose.barcode.complexbarcode/gs1codetext/validate/
---
## GS1Codetext::Validate method


验证括号形式的 GS1 元素字符串，格式为 (AI)value(AI)value，且不构造对象。值中的文字 '(' 必须写成 (；不支持其他转义序列，')' 不需要转义。

```cpp
static System::SharedPtr<Common::GS1ValidationResult> Aspose::BarCode::ComplexBarcode::GS1Codetext::Validate(System::String value)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| value | System::String | 待验证的括号式 GS1 元素字符串。 |

### ReturnValue

结构化验证结果。

## 另见

* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
