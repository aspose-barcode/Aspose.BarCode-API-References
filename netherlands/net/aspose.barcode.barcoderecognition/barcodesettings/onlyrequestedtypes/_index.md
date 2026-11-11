---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarcodeSettings-eigenschap. Retourneert alleen barcode-types die expliciet zijn opgegeven voor herkenning. Wanneer ingeschakeld worden herkende barcodes van andere compatibele of equivalente types gefilterd. Standaardwaarde is false"
type: docs
weight: 50
url: /nl/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Retourneert alleen barcode-typen die expliciet zijn opgegeven voor herkenning. Wanneer ingeschakeld, worden herkende barcodes van andere compatibele of equivalente typen gefilterd. Standaardwaarde is false.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Retourneert alleen barcode‑typen die expliciet zijn opgegeven voor herkenning. Standaardwaarde is false.

## Voorbeelden

Dit voorbeeld toont hoe je herkenningsresultaten kunt beperken tot alleen de gevraagde barcode‑typen.

```csharp
[C#]
//genereer EAN13-barcode
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//herken alleen UPCA-barcodes (geen resultaten, omdat de bron EAN13 is)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//herken compatibele typen: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 wordt geretourneerd als UPCA‑equivalent)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### Zie ook

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


