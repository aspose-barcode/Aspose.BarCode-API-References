---
title: "Aspose::BarCode::Generation::BorderParameters klass"
linktitle: "BorderParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::BorderParameters klass. Parametrar för streckkodsbildens kant i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.barcode.generation/borderparameters/
---
## BorderParameters class


Parametrar för streckkodens bildkant

```cpp
class BorderParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Color](./get_color/)() const | Kantfärg. Standardvärde: Color.Black. |
| [get_DashStyle](./get_dashstyle/)() const | Kantens streckstil. Standardvärde: [BorderDashStyle.Solid](../borderdashstyle/). |
| [get_Visible](./get_visible/)() const | Kantens synlighet. Om falskt ignoreras parametern Width alltid (0). Standardvärde: falskt. |
| [get_Width](./get_width/)() const | Kantbredd. Standardvärde: 0. Ignoreras om Visible är satt till falskt. |
| [set_Color](./set_color/)(System::Drawing::Color) | Kantfärg. Standardvärde: Color.Black. |
| [set_DashStyle](./set_dashstyle/)(BorderDashStyle) | Kantens streckstil. Standardvärde: [BorderDashStyle.Solid](../borderdashstyle/). |
| [set_Visible](./set_visible/)(bool) | Kantens synlighet. Om falskt ignoreras parametern Width alltid (0). Standardvärde: falskt. |
| [set_Width](./set_width/)(System::SharedPtr\<Unit\>) | Kantbredd. Standardvärde: 0. Ignoreras om Visible är satt till falskt. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [BorderParameters](./). |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
