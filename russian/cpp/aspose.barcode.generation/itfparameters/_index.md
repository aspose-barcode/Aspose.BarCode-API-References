---
title: "Aspose::BarCode::Generation::ITFParameters класс"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::ITFParameters класс. Параметры ITF в C++."
type: docs
weight: 3300
url: /ru/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


Параметры ITF.

```cpp
class ITFParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | Получает толщину границы ITF (полосы‑несущей) в значении [Unit](../unit/). Значение по умолчанию: 12pt. |
| [get_BorderType](./get_bordertype/)() const | Тип границы штрих‑кода ITF. Значение по умолчанию: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | Размер тихих зон в xDimension. Значение по умолчанию: 10, что означает, что если xDimension = 2px, то тихие зоны будут 20px. |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | Устанавливает толщину границы ITF (полосы несущего элемента) в значении [Unit](../unit/). Значение по умолчанию: 12pt. |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | Тип границы штрих‑кода ITF. Значение по умолчанию: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | Размер тихих зон в xDimension. Значение по умолчанию: 10, что означает, что если xDimension = 2px, то тихие зоны будут 20px. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этих [ITFParameters](./). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
