---
title: "método"
linktitle: "AddOrReplace"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Añade un nuevo DataElement o lo reemplaza si ElementID ya existe en C++."
type: docs
weight: 800
url: /es/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/addorreplace/
---
## USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) method


Agrega un nuevo **DataElement** o lo reemplaza si ElementID ya existe.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr<USADriveIdJurisdSubfile::DataElement> node)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\> | **DataElement** para agregar |

### ReturnValue

Elemento de datos añadido/reemplazado

## Ver también

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## USADriveIdJurisdSubfile::AddOrReplace(System::String, System::String) method


Agrega un nuevo **DataElement** con el identificador y valor especificados, o reemplaza el elemento existente si ya existe una entrada con el mismo ElementID.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::String id, System::String value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | System::String | Un identificador de 3 letras que especifica de forma única el elemento de datos relacionado con la jurisdicción. |
| valor | System::String | El valor de texto asignado al elemento de datos; este valor sobrescribirá el existente si el elemento ya existe. |

### ReturnValue

La instancia **DataElement** que se añadió a la colección o se actualizó en el lugar.

## Ver también

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
