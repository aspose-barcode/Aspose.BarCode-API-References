---
title: Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile class
linktitle: USADriveIdJurisdSubfile
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile class. Class for Jurisdiction specific fields for USA DL in C++.'
type: docs
weight: 2800
url: /cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
## USADriveIdJurisdSubfile class


Class for Jurisdiction specific fields for USA DL

```cpp
class USADriveIdJurisdSubfile : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddOrReplace](./addorreplace/)(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | Adds new **DataElement** or replaces it if ElementID already exists. |
| [AddOrReplace](./addorreplace/)(System::String, System::String) | Adds a new **DataElement** with the specified identifier and value, or replaces the existing element if an entry with the same ElementID is already present. |
| [Clear](./clear/)() | Clears all data elements |
| [FindDataElement](./finddataelement/)(System::String, bool) | Searches for data element by 3-letter id |
| [get_Count](./get_count/)() | Returns number of data elements |
| virtual [idx_get](./idx_get/)(System::String) | Indexing by 3-letter element id |
| virtual [idx_get](./idx_get/)(int32_t) | Indexing by index number |
| virtual [idx_set](./idx_set/)(System::String, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | Indexing by 3-letter element id |
| virtual [idx_set](./idx_set/)(int32_t, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | Indexing by index number |
| [Insert](./insert/)(int32_t, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | Inserts the specified **DataElement** at the given index. If a **DataElement** with the same ElementID already exists, it will be replaced. |
| [RemoveAt](./removeat/)(int32_t) | Tries to remove element at index |
| [RemoveAt](./removeat/)(System::String) | Tries to remove element with 3-letter id |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/)() |  |
## See Also

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
