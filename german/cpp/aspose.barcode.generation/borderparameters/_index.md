---
title: "Aspose::BarCode::Generation::BorderParameters Klasse"
linktitle: "BorderParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::BorderParameters Klasse. Barcode-Bildrand-Parameter in C++."
type: docs
weight: 800
url: /de/cpp/aspose.barcode.generation/borderparameters/
---
## BorderParameters class


Parameter für Barcode-Bildrand

```cpp
class BorderParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_Color](./get_color/)() const | Randfarbe. Standardwert: Color.Black. |
| [get_DashStyle](./get_dashstyle/)() const | Rand‑Strichstil. Standardwert: [BorderDashStyle.Solid](../borderdashstyle/). |
| [get_Visible](./get_visible/)() const | Rand‑Sichtbarkeit. Wenn false, wird der Parameter Width immer ignoriert (0). Standardwert: false. |
| [get_Width](./get_width/)() const | Randbreite. Standardwert: 0. Ignoriert, wenn Visible auf false gesetzt ist. |
| [set_Color](./set_color/)(System::Drawing::Color) | Randfarbe. Standardwert: Color.Black. |
| [set_DashStyle](./set_dashstyle/)(BorderDashStyle) | Rand‑Strichstil. Standardwert: [BorderDashStyle.Solid](../borderdashstyle/). |
| [set_Visible](./set_visible/)(bool) | Rand‑Sichtbarkeit. Wenn false, wird der Parameter Width immer ignoriert (0). Standardwert: false. |
| [set_Width](./set_width/)(System::SharedPtr\<Unit\>) | Randbreite. Standardwert: 0. Ignoriert, wenn Visible auf false gesetzt ist. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [BorderParameters](./) zurück. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
