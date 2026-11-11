---
title: "Klasse ComplexBarcodeGenerator"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.ComplexBarcodeGenerator klasse. ComplexBarcodeGenerator voor backend complexe barcode bijv. generatie van SwissQR‑afbeeldingen"
type: docs
weight: 510
url: /nl/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

ComplexBarcodeGenerator voor het genereren van afbeeldingen van complexe barcodes (bijv. SwissQR) op de backend.

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | Maakt een instantie van ComplexBarcodeGenerator aan. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | Generatieparameters. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | Genereert complexe barcode‑afbeelding met de huidige instellingen. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | Genereert en slaat complexe barcode‑afbeelding op met de huidige instellingen. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Genereert en slaat complexe barcode‑afbeelding op met de huidige instellingen. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Genereert en slaat complexe barcode‑afbeelding op met de huidige instellingen. |

## Voorbeelden

Dit voorbeeld toont hoe een SwissQR‑afbeelding te maken en op te slaan.

```csharp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // initialiseer de rest van de velden
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

### Zie ook

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


