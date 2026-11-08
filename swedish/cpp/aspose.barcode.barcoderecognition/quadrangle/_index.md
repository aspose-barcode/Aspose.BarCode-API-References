---
title: "Aspose::BarCode::BarCodeRecognition::Quadrangle klass"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::Quadrangle klass. Lagrar en uppsättning av fyra Points som representerar ett Quadrangle-område i C++."
type: docs
weight: 3000
url: /sv/cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


Lagrar en uppsättning av fyra [Point](../)s som representerar ett [Quadrangle](./)-område.

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Quadrangle>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | Bestämmer om den specificerade [Point](../) finns inom denna [Quadrangle](./)-klass. |
| [Contains](./contains/)(int32_t, int32_t) | Bestämmer om den angivna punkten finns inom denna [Quadrangle](./)-klass. |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | Bestämmer om den angivna [Quadrangle](./) är innehållen eller skär denna [Quadrangle](./)-klass. |
| [Contains](./contains/)(System::Drawing::Rectangle) | Bestämmer om den angivna [Rectangle](../) är innehållen eller skär denna [Quadrangle](./)-klass. |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett angivet [Quadrangle](./)-värde. |
| [get_BoundingRectangle](./get_boundingrectangle/)() | Hämtar [Rectangle](../) som avgränsar denna [Quadrangle](./) |
| [get_IsEmpty](./get_isempty/)() | **Tester** om alla [Point](../)s i denna [Quadrangle](./) har värdena noll. |
| [get_LeftBottom](./get_leftbottom/)() const | Hämtar vänster‑nedre hörn [Point](../) av [Quadrangle](./)-regionen |
| [get_LeftTop](./get_lefttop/)() const | Hämtar vänster‑övre hörn [Point](../) av [Quadrangle](./)-regionen |
| [get_RightBottom](./get_rightbottom/)() const | Hämtar höger‑nedre hörn [Point](../) av [Quadrangle](./)-regionen |
| [get_RightTop](./get_righttop/)() const | Hämtar höger‑övre hörn [Point](../) av [Quadrangle](./)-regionen |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [Quadrangle](./quadrangle/)() | Initierar en ny tom instans av [Quadrangle](./)-klassen. |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | Initierar en ny instans av [Quadrangle](./)-klassen med de beskrivande punkterna. |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | Hämtar vänster‑nedre hörn [Point](../) av [Quadrangle](./)-regionen |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | Hämtar vänster‑övre hörn [Point](../) av [Quadrangle](./)-regionen |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | Hämtar höger‑nedre hörn [Point](../) av [Quadrangle](./)-regionen |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | Hämtar höger‑övre hörn [Point](../) av [Quadrangle](./)-regionen |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av denna [Quadrangle](./). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | Representerar en [Quadrangle](./)-klass med dess egenskaper oinitierade. |
## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
