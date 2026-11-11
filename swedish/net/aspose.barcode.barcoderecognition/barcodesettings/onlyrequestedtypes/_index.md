---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Aspose.BarCode för .NET API-referens"
description: "BarcodeSettings egenskap. Returnerar endast streckkodstyper som uttryckligen specificerats för igenkänning. När den är aktiverad filtreras erkända streckkoder av andra kompatibla eller motsvarande typer bort. Standardvärdet är falskt"
type: docs
weight: 50
url: /sv/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Returnerar endast streckkodstyper som uttryckligen specificerats för igenkänning. När den är aktiverad filtreras erkända streckkoder av andra kompatibla eller motsvarande typer bort. Standardvärdet är falskt.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Returnerar endast streckkodstyper som uttryckligen specificerats för igenkänning. Standardvärdet är falskt.

## Exempel

Detta exempel visar hur man begränsar igenkänningsresultat till endast begärda streckkodstyper

```csharp
[C#]
//generera EAN13-streckkod
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//igenkänn endast UPCA-streckkoder (inga resultat, eftersom källan är EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//igenkänn kompatibla typer: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 kommer att returneras som UPCA-ekvivalent)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### Se även

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


