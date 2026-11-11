---
title: "Klasse FontUnit"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.FontUnit klasse. Definieert een specifiek formaat voor tekst, inclusief lettertypegrootte en stijlkenmerken waarbij de grootte in Unit value property"
type: docs
weight: 1320
url: /nl/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken waarbij de grootte in de eigenschap Unit value staat.

```csharp
public sealed class FontUnit
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname/) { get; set; } | Haalt of stelt de lettertype‑naam van dit Font in. |
| [Size](../../aspose.barcode.generation/fontunit/size/) { get; } | Haalt of stelt de grootte van dit FontUnit in Unit value in. |
| [Style](../../aspose.barcode.generation/fontunit/style/) { get; set; } | Haalt of stelt stijl‑informatie voor dit FontUnit in. |

## Voorbeelden

Dit voorbeeld laat zien hoe u een BarCode‑afbeelding maakt en opslaat.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


