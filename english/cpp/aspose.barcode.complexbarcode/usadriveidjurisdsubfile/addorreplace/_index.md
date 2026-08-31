---
title:  method
linktitle: AddOrReplace
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Adds new DataElement or replaces it if ElementID already exists in C++.'
type: docs
weight: 800
url: /cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/addorreplace/
---
## USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) method


Adds new **DataElement** or replaces it if ElementID already exists.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr<USADriveIdJurisdSubfile::DataElement> node)
```


| Parameter | Type | Description |
| --- | --- | --- |
| node | System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\> | **DataElement** to add |

### ReturnValue

Added/replaced data element

## See Also

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## USADriveIdJurisdSubfile::AddOrReplace(System::String, System::String) method


Adds a new **DataElement** with the specified identifier and value, or replaces the existing element if an entry with the same ElementID is already present.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::String id, System::String value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| id | System::String | A 3-letter identifier that uniquely specifies the jurisdiction-related data element. |
| value | System::String | The text value assigned to the data element; this value will overwrite the existing one if the element already exists. |

### ReturnValue

The **DataElement** instance that was added to the collection or updated in place.

## See Also

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
