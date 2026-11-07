---
title: "method"
linktitle: "AddOrReplace"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Добавляет новый DataElement или заменяет его, если ElementID уже существует в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/addorreplace/
---
## USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) method


Добавляет новый **DataElement** или заменяет его, если ElementID уже существует.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr<USADriveIdJurisdSubfile::DataElement> node)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| узел | System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\> | **DataElement** для добавления |

### ReturnValue

Добавлен/заменён элемент данных

## См. также

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## USADriveIdJurisdSubfile::AddOrReplace(System::String, System::String) method


Добавляет новый **DataElement** с указанным идентификатором и значением, либо заменяет существующий элемент, если запись с тем же ElementID уже присутствует.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::String id, System::String value)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| id | System::String | Трёхбуквенный идентификатор, который однозначно определяет элемент данных, связанный с юрисдикцией. |
| value | System::String | Текстовое значение, присвоенное элементу данных; это значение перезапишет существующее, если элемент уже существует. |

### ReturnValue

Экземпляр **DataElement**, который был добавлен в коллекцию или обновлён на месте.

## См. также

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
