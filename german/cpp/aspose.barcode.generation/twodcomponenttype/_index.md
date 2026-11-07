---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " enum. Typ einer 2D-Komponente in C++."
type: docs
weight: 8700
url: /de/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


Typ der 2D-Komponente

```cpp
enum class TwoDComponentType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Automatische Auswahl des Typs einer 2D-Komponente |
| CC_A | 1 | CC-A Typ einer 2D-Komponente. Es ist eine strukturelle Variante von MicroPDF417 |
| CC_B | 2 | CC-B Typ einer 2D-Komponente. Es ist ein MicroPDF417-Symbol. |
| CC_C | 3 | CC-C Typ einer 2D-Komponente. Es ist ein PDF417-Symbol. |

## Hinweise


Dieses Beispiel zeigt, wie man ein GS1 Composite Bar-Bild erstellt und speichert. Beachten Sie, dass 1D-Codetext und 2D-Codetext durch das Symbol '/' getrennt sind.
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
    using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
    {
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

    // Seitenverhältnis der 2D-Komponente
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

    // X-Dimension von 1D- und 2D-Komponenten
    generator.Parameters.Barcode.XDimension.Pixels = 3;

    // Höhe der 1D-Komponente
    generator.Parameters.Barcode.BarHeight.Pixels = 100;

    generator.Save("test.png");
}
```

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
