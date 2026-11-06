---
title: "method"
linktitle: "AddOrReplace"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法. 在 C++ 中添加新的 DataElement，或在 ElementID 已存在时替换它。"
type: docs
weight: 800
url: /zh/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/addorreplace/
---
## USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) method


添加新的 **DataElement**，如果 ElementID 已存在则替换。

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr<USADriveIdJurisdSubfile::DataElement> node)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 节点 | System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\> | **DataElement** 要添加 |

### ReturnValue

已添加/已替换的数据元素

## 另见

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## USADriveIdJurisdSubfile::AddOrReplace(System::String, System::String) method


添加具有指定标识符和值的新的 **DataElement**，如果已存在具有相同 ElementID 的条目则替换现有元素。

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::String id, System::String value)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 标识符 | System::String | 一个唯一指定司法相关数据元素的 3 字母标识符。 |
| value | System::String | 分配给数据元素的文本值；如果该元素已存在，此值将覆盖现有值。 |

### ReturnValue

已添加到集合或就地更新的 **DataElement** 实例。

## 另见

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
