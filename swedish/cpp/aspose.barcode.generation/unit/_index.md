---
title: "Aspose::BarCode::Generation::Unit klass"
linktitle: "Unit"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::Unit klass. Anger storleksvärdet i olika enheter (Pixel, Inches, etc.) i C++."
type: docs
weight: 5000
url: /sv/cpp/aspose.barcode.generation/unit/
---
## Unit class


Anger storleksvärdet i olika enheter (pixel, tum, osv).

```cpp
class Unit : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bestämmer om detta objekt och ett specificerat objekt, som också måste vara ett [Unit](./)-objekt, har samma värde. |
| [get_Document](./get_document/)() | Hämtar storleksvärde i dokumentenheter. |
| [get_Inches](./get_inches/)() | Hämtar storleksvärde i tum. |
| [get_Millimeters](./get_millimeters/)() | Hämtar storleksvärde i millimeter. |
| [get_Pixels](./get_pixels/)() | Hämtar storleksvärde i pixlar. |
| [get_Point](./get_point/)() | Hämtar storleksvärde i punkt. |
| [get_Resolution](./get_resolution/)() const | Upplösning |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash-koden för detta objekt. |
| [set_Document](./set_document/)(float) | Ställer in storleksvärde i dokumentenheter. |
| [set_Inches](./set_inches/)(float) | Ställer in storleksvärde i tum. |
| [set_Millimeters](./set_millimeters/)(float) | Ställer in storleksvärde i millimeter. |
| [set_Pixels](./set_pixels/)(float) | Ställer in storleksvärde i pixlar. |
| [set_Point](./set_point/)(float) | Ställer in storleksvärde i punkt. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [Unit](./). |
## Anmärkningar


Detta exempel visar hur man skapar och sparar en [BarCode](../../aspose.barcode/) bild.
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
