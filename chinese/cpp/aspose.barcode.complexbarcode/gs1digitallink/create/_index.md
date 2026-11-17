---
title: "method"
linktitle: "创建"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。通过复制所有来自 GS1 codetext 的元素并选择唯一可用的主键来创建 GS1 Digital Link（C++）。"
type: docs
weight: 2100
url: /zh/cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


通过从 GS1 代码文本复制所有元素并选择唯一可用的主键来创建 GS1 Digital Link。

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| uriStem | System::String | 主键之前的绝对 HTTP 或 HTTPS URI 前缀。 |
| codetext | System::SharedPtr\<GS1Codetext\> | 其元素被复制的 GS1 codetext。 |

### ReturnValue

包含已复制元素的 GS1 Digital Link。

## 另见

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


通过从 GS1 代码文本复制所有元素并使用指定的主键来创建 GS1 Digital Link。

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| uriStem | System::String | 主键之前的绝对 HTTP 或 HTTPS URI 前缀。 |
| codetext | System::SharedPtr\<GS1Codetext\> | 其元素被复制的 GS1 codetext。 |
| primaryApplicationIdentifier | System::String | 主键 AI。 |

### ReturnValue

包含已复制元素的 GS1 Digital Link。

## 另见

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
