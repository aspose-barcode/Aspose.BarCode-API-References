---
title: Aspose::BarCode::BarCodeRecognition::Quadrangle class
linktitle: Quadrangle
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::Quadrangle class. Stores a set of four Points that represent a Quadrangle region in C++.'
type: docs
weight: 2700
url: /cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


Stores a set of four [Point](../)s that represent a [Quadrangle](./) region.

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Aspose::BarCode::BarCodeRecognition::Quadrangle>>
```

## Methods

| Method | Description |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | Determines if the specified [Point](../) is contained within this [Quadrangle](./) class. |
| [Contains](./contains/)(int32_t, int32_t) | Determines if the specified point is contained within this [Quadrangle](./) class. |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | Determines if the specified [Quadrangle](./) is contained or intersect this [Quadrangle](./) class. |
| [Contains](./contains/)(System::Drawing::Rectangle) | Determines if the specified [Rectangle](../) is contained or intersect this [Quadrangle](./) class. |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | Returns a value indicating whether this instance is equal to a specified [Quadrangle](./) value. |
| [get_BoundingRectangle](./get_boundingrectangle/)() | Gets [Rectangle](../) bounding this [Quadrangle](./) |
| [get_IsEmpty](./get_isempty/)() | **Tests** whether all [Point](../)s of this [Quadrangle](./) have values of zero. |
| [get_LeftBottom](./get_leftbottom/)() const | Gets left-bottom corner [Point](../) of [Quadrangle](./) region |
| [get_LeftTop](./get_lefttop/)() const | Gets left-top corner [Point](../) of [Quadrangle](./) region |
| [get_RightBottom](./get_rightbottom/)() const | Gets right-bottom corner [Point](../) of [Quadrangle](./) region |
| [get_RightTop](./get_righttop/)() const | Gets right-top corner [Point](../) of [Quadrangle](./) region |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [Quadrangle](./quadrangle/)() | Initializes a new empty instance of the [Quadrangle](./) class. |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | Initializes a new instance of the [Quadrangle](./) class with the describing points. |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | Gets left-bottom corner [Point](../) of [Quadrangle](./) region |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | Gets left-top corner [Point](../) of [Quadrangle](./) region |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | Gets right-bottom corner [Point](../) of [Quadrangle](./) region |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | Gets right-top corner [Point](../) of [Quadrangle](./) region |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [Quadrangle](./). |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Represents a [Quadrangle](./) class with its properties left uninitialized. |
## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
