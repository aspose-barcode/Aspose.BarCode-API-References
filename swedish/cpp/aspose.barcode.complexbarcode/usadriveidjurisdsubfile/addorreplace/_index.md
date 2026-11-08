---
title: "metod"
linktitle: "AddOrReplace"
second_title: "Aspose.BarCode for C++ API-referens"
description: " method. Lägger till ett nytt DataElement eller ersätter det om ElementID redan finns i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/addorreplace/
---
## USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) method


Lägger till ett nytt **DataElement** eller ersätter det om ElementID redan finns.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr<USADriveIdJurisdSubfile::DataElement> node)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nod | System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\> | **DataElement** att lägga till |

### ReturnValue

Tillagt/ersatt dataelement

## Se även

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## USADriveIdJurisdSubfile::AddOrReplace(System::String, System::String) method


Lägger till ett nytt **DataElement** med den angivna identifieraren och värdet, eller ersätter det befintliga elementet om en post med samma ElementID redan finns.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::String id, System::String value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | System::String | En 3‑bokstavig identifierare som unikt specificerar det jurisdiktionsrelaterade dataelementet. |
| värde | System::String | Textvärdet som tilldelas dataelementet; detta värde kommer att skriva över det befintliga om elementet redan finns. |

### ReturnValue

Den **DataElement**‑instans som lades till i samlingen eller uppdaterades på plats.

## Se även

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
