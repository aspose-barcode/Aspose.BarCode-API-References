---
title: "Klasse Unit"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.Unit klasse. Specificeert de groottewaarde in verschillende eenheden Pixel Inches enz."
type: docs
weight: 1740
url: /nl/net/aspose.barcode.generation/unit/
---
## Unit class

Specificeert de groottewaarde in verschillende eenheden (Pixel, Inches, enz.).

```csharp
public sealed class Unit
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | Haalt op of stelt de groottewaarde in documenteenheden in. |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | Haalt op of stelt de groottewaarde in inches in. |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | Haalt op of stelt de groottewaarde in millimeters in. |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | Haalt op of stelt de groottewaarde in pixels in. |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | Haalt op of stelt de groottewaarde in punten in. |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | Resolutie |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | Bepaalt of deze instantie en een opgegeven object, dat ook een `Unit`-object moet zijn, dezelfde waarde hebben. |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | Retourneert de hashcode voor dit object. |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `Unit`. |

## Voorbeelden

Dit voorbeeld laat zien hoe u een BarCode‑afbeelding maakt en opslaat.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


