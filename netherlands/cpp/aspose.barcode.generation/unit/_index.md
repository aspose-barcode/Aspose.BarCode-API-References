---
title: "Aspose::BarCode::Generation::Unit klasse"
linktitle: "Unit"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::Unit klasse. Specificeert de groottewaarde in verschillende eenheden (Pixel, Inches, etc.) in C++."
type: docs
weight: 5000
url: /nl/cpp/aspose.barcode.generation/unit/
---
## Unit class


Specificeert de groottewaarde in verschillende eenheden (pixel, inches, enz.).

```cpp
class Unit : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bepaalt of deze instantie en een opgegeven object, dat ook een [Unit](./)‑object moet zijn, dezelfde waarde hebben. |
| [get_Document](./get_document/)() | Haalt de groottewaarde op in documenteenheden. |
| [get_Inches](./get_inches/)() | Haalt de groottewaarde op in inches. |
| [get_Millimeters](./get_millimeters/)() | Haalt de groottewaarde op in millimeters. |
| [get_Pixels](./get_pixels/)() | Haalt de groottewaarde op in pixels. |
| [get_Point](./get_point/)() | Haalt de groottewaarde op in point. |
| [get_Resolution](./get_resolution/)() const | Resolutie |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hash‑code voor dit object. |
| [set_Document](./set_document/)(float) | Stelt de groottewaarde in in documenteenheden. |
| [set_Inches](./set_inches/)(float) | Stelt de groottewaarde in in inches. |
| [set_Millimeters](./set_millimeters/)(float) | Stelt de groottewaarde in in millimeters. |
| [set_Pixels](./set_pixels/)(float) | Stelt de groottewaarde in in pixels. |
| [set_Point](./set_point/)(float) | Stelt de groottewaarde in in point. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [Unit](./). |
## Opmerkingen


Deze voorbeeld toont hoe een [BarCode](../../aspose.barcode/) afbeelding te maken en op te slaan.
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
