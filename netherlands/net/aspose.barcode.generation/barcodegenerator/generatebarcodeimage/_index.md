---
title: "BarcodeGenerator.GenerateBarCodeImage"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarcodeGenerator-methode. De barcode-afbeelding genereren met de huidige instellingen"
type: docs
weight: 80
url: /nl/net/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator.GenerateBarCodeImage method

Genereer de barcode‑afbeelding met de huidige instellingen.

```csharp
public Bitmap GenerateBarCodeImage()
```

### Retourwaarde

Barcode-afbeelding. Zie Bitmap.

## Voorbeelden

Dit voorbeeld laat zien hoe je een barcode‑afbeelding maakt en opslaat.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

### Zie ook

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


