---
title: "Aspose::BarCode::Generation::FontUnit class"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::FontUnit class. Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut där storleken är i Unit‑värdeegenskapen i C++."
type: docs
weight: 2500
url: /sv/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut där storleken är i [Unit](../unit/) värdeegenskap.

```cpp
class FontUnit : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | Hämtar teckensnittsnamnet för detta Font. |
| [get_Size](./get_size/)() const | Hämtar storleken på detta [FontUnit](./) i [Unit](../unit/) värde. |
| [get_Style](./get_style/)() const | Hämtar stilinformation för detta [FontUnit](./). |
| [set_FamilyName](./set_familyname/)(System::String) | Ställer in teckensnittets namn för detta Font. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | Ställer in stilinformation för detta [FontUnit](./). |
## Anmärkningar


Detta exempel visar hur man skapar och sparar en [BarCode](../../aspose.barcode/) bild.
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
