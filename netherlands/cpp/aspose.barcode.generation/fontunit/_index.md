---
title: "Aspose::BarCode::Generation::FontUnit class"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::FontUnit class. Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken waarbij de grootte in de Unit-waarde-eigenschap in C++ staat."
type: docs
weight: 2500
url: /nl/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken waarbij de grootte in de [Unit](../unit/) waarde-eigenschap staat.

```cpp
class FontUnit : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | Haalt de naam van het lettertype van dit Font op. |
| [get_Size](./get_size/)() const | Haalt de grootte van deze [FontUnit](./) op in [Unit](../unit/) waarde. |
| [get_Style](./get_style/)() const | Haalt stijlinformatie op voor deze [FontUnit](./). |
| [set_FamilyName](./set_familyname/)(System::String) | Stelt de naam van dit Font in. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | Stelt stijlinformatie in voor deze [FontUnit](./). |
## Opmerkingen


Deze voorbeeld toont hoe een [BarCode](../../aspose.barcode/) afbeelding te maken en op te slaan.
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
