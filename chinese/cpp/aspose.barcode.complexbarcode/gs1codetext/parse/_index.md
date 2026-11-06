---
title: "method"
linktitle: "Parse"
second_title: "Aspose.BarCode for C++ API 参考"
description: "方法。解析形式为 (AI)value(AI)value 的括号式 GS1 元素字符串。值中的文字 ''('' 必须写成 (；不支持其他转义序列，且 '')'' 在 C++ 中不需要转义。"
type: docs
weight: 1500
url: /zh/cpp/aspose.barcode.complexbarcode/gs1codetext/parse/
---
## GS1Codetext::Parse method


解析括号形式的 GS1 元素字符串，格式为 (AI)value(AI)value。值中的字面 '(' 必须写成 (；不支持其他转义序列，')' 不需要转义。

```cpp
static System::SharedPtr<GS1Codetext> Aspose::BarCode::ComplexBarcode::GS1Codetext::Parse(System::String value)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| value | System::String | 待解析的带括号的 GS1 元素字符串。 |

### ReturnValue

已解析的 GS1 编码文本。

## 另见

* Class [GS1Codetext](../)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
