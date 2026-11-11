---
title: "Enum TwoDComponentType"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.TwoDComponentType enum. Type van 2D‑component"
type: docs
weight: 1730
url: /nl/net/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enumeration

Type van 2D-component

```csharp
public enum TwoDComponentType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | Selecteer automatisch type van 2D‑component |
| CC_A | `1` | CC-A type van 2D‑component. Het is een structurele variant van MicroPDF417 |
| CC_B | `2` | CC-B type van 2D‑component. Het is een MicroPDF417‑symbool. |
| CC_C | `3` | CC-C type van 2D‑component. Het is een PDF417‑symbool. |

## Voorbeelden

Dit voorbeeld toont hoe een GS1 Composite Bar‑afbeelding te maken en op te slaan. Merk op dat 1D‑codetekst en 2D‑codetekst gescheiden zijn door het symbool '/'

```csharp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
{
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
    
    // Beeldverhouding van 2D‑component
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
        
    // X‑dimensie van 1D‑ en 2D‑componenten
    generator.Parameters.Barcode.XDimension.Pixels = 3;
        
    // Hoogte van 1D‑component
    generator.Parameters.Barcode.BarHeight.Pixels = 100;
    
    generator.Save("test.png");
}
```

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


