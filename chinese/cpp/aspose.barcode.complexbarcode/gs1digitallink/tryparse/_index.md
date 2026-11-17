---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。尝试解析未压缩的 GS1 Digital Link URI 并在 C++ 中返回结构化的验证错误。"
type: docs
weight: 2000
url: /zh/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


尝试解析未压缩的 GS1 数字链接 URI 并返回结构化的验证错误。

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| value | System::String | 要解析的 GS1 Digital Link URI。 |
| result | System::SharedPtr\<GS1DigitalLink\>\& | 当此方法返回 true 时，包含已解析的 GS1 Digital Link；否则为 null。 |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | 包含验证结果，或在 *value* 为 null 时返回 null。 |

### ReturnValue

当解析成功时为 True；否则为 false。

## 另见

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
