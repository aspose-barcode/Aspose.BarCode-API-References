---
title: "Aspose::BarCode::Generation::FontUnit Klasse"
linktitle: "FontUnit"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::FontUnit Klasse. Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stilattribute, wobei die Größe in der Unit-Wert‑Eigenschaft in C++ angegeben ist."
type: docs
weight: 2500
url: /de/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stilattribute, wobei die Größe im [Unit](../unit/)-Wert‑Eigenschaft angegeben ist.

```cpp
class FontUnit : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | Gibt den Schriftartnamen dieser Schrift zurück. |
| [get_Size](./get_size/)() const | Ermittelt die Größe dieser [FontUnit](./) im [Unit](../unit/)-Wert. |
| [get_Style](./get_style/)() const | Ermittelt Stilinformationen für diese [FontUnit](./). |
| [set_FamilyName](./set_familyname/)(System::String) | Setzt den Schriftartnamen dieser Schrift. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | Setzt Stilinformationen für diese [FontUnit](./). |
## Hinweise


Dieses Beispiel zeigt, wie man ein [BarCode](../../aspose.barcode/)‑Bild erstellt und speichert.
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
