---
title: "Klasse ComplexBarcodeGenerator"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.ComplexBarcodeGenerator Klasse. ComplexBarcodeGenerator für die Backend-Erzeugung komplexer Barcodes, z. B. zur Generierung von SwissQR‑Bildern"
type: docs
weight: 510
url: /de/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

ComplexBarcodeGenerator zur Erzeugung von Backend‑Komplex‑Barcode‑Bildern (z. B. SwissQR).

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | Erstellt eine Instanz von ComplexBarcodeGenerator. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | Generierungsparameter. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | Erzeugt ein komplexes Barcode‑Bild mit den aktuellen Einstellungen. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | Erzeugt und speichert ein komplexes Barcode‑Bild mit den aktuellen Einstellungen. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Erzeugt und speichert ein komplexes Barcode‑Bild mit den aktuellen Einstellungen. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Erzeugt und speichert ein komplexes Barcode‑Bild mit den aktuellen Einstellungen. |

## Beispiele

Dieses Beispiel zeigt, wie man ein SwissQR‑Bild erstellt und speichert.

```csharp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // Initialisiere den Rest der Felder
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

### Siehe auch

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


