---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode for C++ API-referens"
description: " enum. Typ av 2D-komponent i C++."
type: docs
weight: 8700
url: /sv/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


Typ av 2D-komponent

```cpp
enum class TwoDComponentType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | Automatiskt välj typ av 2D-komponent |
| CC_A | 1 | CC-A typ av 2D-komponent. Det är en strukturell variant av MicroPDF417 |
| CC_B | 2 | CC-B typ av 2D-komponent. Det är en MicroPDF417-symbol. |
| CC_C | 3 | CC-C typ av 2D-komponent. Det är en PDF417-symbol. |

## Anmärkningar


Detta exempel visar hur man skapar och sparar en GS1 Composite Bar-bild. Observera att 1D-kodtext och 2D-kodtext separeras av symbolen '/'
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
    using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
    {
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

    // Bildförhållande för 2D-komponent
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

    // X-dimension för 1D- och 2D-komponenter
    generator.Parameters.Barcode.XDimension.Pixels = 3;

    // Höjd för 1D-komponent
    generator.Parameters.Barcode.BarHeight.Pixels = 100;

    generator.Save("test.png");
}
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
