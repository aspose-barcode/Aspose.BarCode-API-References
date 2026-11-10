---
title: "BarcodeGenerator.GenerateBarCodeImage"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarcodeGenerator-Methode. Barcode‑Bild anhand der aktuellen Einstellungen erzeugen"
type: docs
weight: 80
url: /de/net/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator.GenerateBarCodeImage method

Erzeugt das Barcode‑Bild mit den aktuellen Einstellungen.

```csharp
public Bitmap GenerateBarCodeImage()
```

### Rückgabewert

Barcode-Bild. Siehe Bitmap.

## Beispiele

Dieses Beispiel zeigt, wie man ein Barcode‑Bild erstellt und speichert.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

### Siehe auch

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


