---
title: "Aspose::BarCode::Generation::Unit Klasse"
linktitle: "Unit"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::Unit Klasse. Gibt den Größenwert in verschiedenen Einheiten (Pixel, Zoll usw.) in C++ an."
type: docs
weight: 5000
url: /de/cpp/aspose.barcode.generation/unit/
---
## Unit class


Gibt den Größenwert in verschiedenen Einheiten an (Pixel, Zoll usw.).

```cpp
class Unit : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bestimmt, ob diese Instanz und ein angegebenes Objekt, das ebenfalls ein [Unit](./) Objekt sein muss, denselben Wert haben. |
| [get_Document](./get_document/)() | Liefert den Größenwert in Dokumenteinheiten. |
| [get_Inches](./get_inches/)() | Liefert den Größenwert in Zoll. |
| [get_Millimeters](./get_millimeters/)() | Liefert den Größenwert in Millimetern. |
| [get_Pixels](./get_pixels/)() | Liefert den Größenwert in Pixeln. |
| [get_Point](./get_point/)() | Liefert den Größenwert in Punkten. |
| [get_Resolution](./get_resolution/)() const | Auflösung |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für dieses Objekt zurück. |
| [set_Document](./set_document/)(float) | Setzt den Größenwert in Dokumenteinheiten. |
| [set_Inches](./set_inches/)(float) | Setzt den Größenwert in Zoll. |
| [set_Millimeters](./set_millimeters/)(float) | Setzt den Größenwert in Millimetern. |
| [set_Pixels](./set_pixels/)(float) | Setzt den Größenwert in Pixeln. |
| [set_Point](./set_point/)(float) | Setzt den Größenwert in Punkt. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [Unit](./) zurück. |
## Hinweise


Dieses Beispiel zeigt, wie man ein [BarCode](../../aspose.barcode/)‑Bild erstellt und speichert.
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
