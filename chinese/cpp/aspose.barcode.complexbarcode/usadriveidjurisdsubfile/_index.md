---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile 类"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile 类。用于在 C++ 中针对美国驾照的司法特定字段的类。"
type: docs
weight: 3100
url: /zh/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
## USADriveIdJurisdSubfile class


用于美国 DL 特定司法辖区字段的类。

```cpp
class USADriveIdJurisdSubfile : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [AddOrReplace](./addorreplace/)(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | 添加新的 **DataElement**，如果 ElementID 已存在则替换。 |
| [AddOrReplace](./addorreplace/)(System::String, System::String) | 添加具有指定标识符和值的新的 **DataElement**，如果已存在具有相同 ElementID 的条目则替换现有元素。 |
| [Clear](./clear/)() | 清除所有数据元素 |
| [FindDataElement](./finddataelement/)(System::String, bool) | 按 3 字母 ID 搜索数据元素 |
| [get_Count](./get_count/)() | 返回数据元素的数量 |
| [idx_get](./idx_get/)(System::String) | 通过 3 字母元素 ID 进行索引 |
| [idx_get](./idx_get/)(int32_t) | 通过索引号进行索引 |
| [idx_set](./idx_set/)(System::String, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | 通过 3 字母元素 ID 进行索引 |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | 通过索引号进行索引 |
| [Insert](./insert/)(int32_t, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | 在给定索引处插入指定的 **DataElement**。如果具有相同 ElementID 的 **DataElement** 已存在，则会被替换。 |
| [RemoveAt](./removeat/)(int32_t) | 尝试删除指定索引处的元素 |
| [RemoveAt](./removeat/)(System::String) | 尝试删除具有 3 字母 ID 的元素 |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/)() |  |
## 另见

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
