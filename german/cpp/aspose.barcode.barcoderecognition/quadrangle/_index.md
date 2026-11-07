---
title: "Aspose::BarCode::BarCodeRecognition::Quadrangle Klasse"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::Quadrangle Klasse. Speichert ein Set von vier Points, die eine Quadrangle‑Region in C++ darstellen."
type: docs
weight: 3000
url: /de/cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


Speichert ein Set von vier [Point](../)s, die eine [Quadrangle](./)-Region darstellen.

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Quadrangle>>
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | Bestimmt, ob der angegebene [Point](../) in dieser [Quadrangle](./)-Klasse enthalten ist. |
| [Contains](./contains/)(int32_t, int32_t) | Bestimmt, ob der angegebene Punkt in dieser [Quadrangle](./)-Klasse enthalten ist. |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | Bestimmt, ob das angegebene [Quadrangle](./) in dieser [Quadrangle](./)-Klasse enthalten ist oder sie schneidet. |
| [Contains](./contains/)(System::Drawing::Rectangle) | Bestimmt, ob das angegebene [Rectangle](../) in dieser [Quadrangle](./)-Klasse enthalten ist oder sie schneidet. |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [Quadrangle](./)-Wert entspricht. |
| [get_BoundingRectangle](./get_boundingrectangle/)() | Ermittelt das [Rectangle](../), das dieses [Quadrangle](./) begrenzt |
| [get_IsEmpty](./get_isempty/)() | **Tests** ob alle [Point](../)s dieses [Quadrangle](./) den Wert Null haben. |
| [get_LeftBottom](./get_leftbottom/)() const | Ermittelt den linken unteren Eckpunkt [Point](../) der [Quadrangle](./)-Region |
| [get_LeftTop](./get_lefttop/)() const | Ermittelt den linken oberen Eckpunkt [Point](../) der [Quadrangle](./)-Region |
| [get_RightBottom](./get_rightbottom/)() const | Ermittelt den rechten unteren Eckpunkt [Point](../) der [Quadrangle](./)-Region |
| [get_RightTop](./get_righttop/)() const | Ermittelt den rechten oberen Eckpunkt [Point](../) der [Quadrangle](./)-Region |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [Quadrangle](./quadrangle/)() | Initialisiert eine neue leere Instanz der [Quadrangle](./)-Klasse. |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | Initialisiert eine neue Instanz der [Quadrangle](./)-Klasse mit den beschreibenden Punkten. |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | Ermittelt den linken unteren Eckpunkt [Point](../) der [Quadrangle](./)-Region |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | Ermittelt den linken oberen Eckpunkt [Point](../) der [Quadrangle](./)-Region |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | Ermittelt den rechten unteren Eckpunkt [Point](../) der [Quadrangle](./)-Region |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | Ermittelt den rechten oberen Eckpunkt [Point](../) der [Quadrangle](./)-Region |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [Quadrangle](./) zurück. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Stellt eine [Quadrangle](./)-Klasse dar, deren Eigenschaften nicht initialisiert sind. |
## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
