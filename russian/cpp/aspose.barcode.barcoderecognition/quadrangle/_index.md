---
title: "Класс Aspose::BarCode::BarCodeRecognition::Quadrangle"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::BarCodeRecognition::Quadrangle. Сохраняет набор из четырёх Point, представляющих регион Quadrangle в C++."
type: docs
weight: 3000
url: /ru/cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


Сохраняет набор из четырёх [Point](../)s, представляющих регион [Quadrangle](./).

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Quadrangle>>
```

## Methods

| Method | Описание |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | Определяет, содержится ли указанный [Point](../) внутри этого класса [Quadrangle](./). |
| [Contains](./contains/)(int32_t, int32_t) | Определяет, содержится ли указанная точка в этом классе [Quadrangle](./). |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | Определяет, содержится ли указанный [Quadrangle](./) или пересекает этот [Quadrangle](./) класс. |
| [Contains](./contains/)(System::Drawing::Rectangle) | Определяет, содержится ли указанный [Rectangle](../) или пересекает этот [Quadrangle](./) класс. |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [Quadrangle](./). |
| [get_BoundingRectangle](./get_boundingrectangle/)() | Получает [Rectangle](../), ограничивающий этот [Quadrangle](./) |
| [get_IsEmpty](./get_isempty/)() | **Tests** определяет, имеют ли все [Point](../)s этого [Quadrangle](./) нулевые значения. |
| [get_LeftBottom](./get_leftbottom/)() const | Получает левый нижний угол [Point](../) региона [Quadrangle](./) |
| [get_LeftTop](./get_lefttop/)() const | Получает левый верхний угол [Point](../) региона [Quadrangle](./) |
| [get_RightBottom](./get_rightbottom/)() const | Получает правый нижний угол [Point](../) региона [Quadrangle](./) |
| [get_RightTop](./get_righttop/)() const | Получает правый верхний угол [Point](../) региона [Quadrangle](./) |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [Quadrangle](./quadrangle/)() | Инициализирует новый пустой экземпляр класса [Quadrangle](./). |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | Инициализирует новый экземпляр класса [Quadrangle](./) с описывающими точками. |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | Получает левый нижний угол [Point](../) региона [Quadrangle](./) |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | Получает левый верхний угол [Point](../) региона [Quadrangle](./) |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | Получает правый нижний угол [Point](../) региона [Quadrangle](./) |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | Получает правый верхний угол [Point](../) региона [Quadrangle](./) |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [Quadrangle](./). |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](./empty/) | Представляет класс [Quadrangle](./) с неинициализированными свойствами. |
## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
