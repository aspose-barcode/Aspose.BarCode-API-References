---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile класс"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile класс. Класс для полей, специфичных для юрисдикции, для водительского удостоверения США (USA DL) в C++."
type: docs
weight: 3100
url: /ru/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
## USADriveIdJurisdSubfile class


Класс для полей, специфичных для юрисдикции, для водительского удостоверения США.

```cpp
class USADriveIdJurisdSubfile : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [AddOrReplace](./addorreplace/)(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | Добавляет новый **DataElement** или заменяет его, если ElementID уже существует. |
| [AddOrReplace](./addorreplace/)(System::String, System::String) | Добавляет новый **DataElement** с указанным идентификатором и значением, либо заменяет существующий элемент, если запись с тем же ElementID уже присутствует. |
| [Clear](./clear/)() | Очищает все элементы данных |
| [FindDataElement](./finddataelement/)(System::String, bool) | Ищет элемент данных по 3-буквенному идентификатору |
| [get_Count](./get_count/)() | Возвращает количество элементов данных |
| [idx_get](./idx_get/)(System::String) | Индексация по 3-буквенному идентификатору элемента |
| [idx_get](./idx_get/)(int32_t) | Индексация по номеру индекса |
| [idx_set](./idx_set/)(System::String, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | Индексация по 3-буквенному идентификатору элемента |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | Индексация по номеру индекса |
| [Insert](./insert/)(int32_t, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | Вставляет указанный **DataElement** в заданный индекс. Если **DataElement** с тем же ElementID уже существует, он будет заменён. |
| [RemoveAt](./removeat/)(int32_t) | Пытается удалить элемент по индексу |
| [RemoveAt](./removeat/)(System::String) | Пытается удалить элемент с 3-буквенным идентификатором |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/)() |  |
## См. также

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
