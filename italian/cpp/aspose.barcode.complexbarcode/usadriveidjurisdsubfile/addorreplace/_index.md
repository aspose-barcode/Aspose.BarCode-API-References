---
title: "method"
linktitle: "AddOrReplace"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Aggiunge un nuovo DataElement o lo sostituisce se ElementID esiste già in C++."
type: docs
weight: 800
url: /it/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/addorreplace/
---
## USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) method


Aggiunge un nuovo **DataElement** o lo sostituisce se ElementID esiste già.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr<USADriveIdJurisdSubfile::DataElement> node)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| nodo | System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\> | **DataElement** da aggiungere |

### ReturnValue

Elemento dati aggiunto/sostituito

## Vedi anche

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## USADriveIdJurisdSubfile::AddOrReplace(System::String, System::String) method


Aggiunge un nuovo **DataElement** con l'identificatore e il valore specificati, oppure sostituisce l'elemento esistente se è già presente una voce con lo stesso ElementID.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::String id, System::String value)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| id | System::String | Un identificatore a 3 lettere che specifica in modo univoco l'elemento dati relativo alla giurisdizione. |
| value | System::String | Il valore di testo assegnato all'elemento dati; questo valore sovrascriverà quello esistente se l'elemento è già presente. |

### ReturnValue

L'istanza **DataElement** che è stata aggiunta alla collezione o aggiornata in loco.

## Vedi anche

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
