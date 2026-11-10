---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarcodeSettings-Eigenschaft. Gibt nur Barcode-Typen zurück, die ausdrücklich für die Erkennung angegeben wurden. Wenn aktiviert, werden erkannte Barcodes anderer kompatibler oder gleichwertiger Typen herausgefiltert. Standardwert ist false"
type: docs
weight: 50
url: /de/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Gibt nur Barcode-Typen zurück, die ausdrücklich für die Erkennung angegeben wurden. Wenn aktiviert, werden erkannte Barcodes anderer kompatibler oder äquivalenter Typen herausgefiltert. Standardwert ist false.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Gibt nur Barcode-Typen zurück, die ausdrücklich für die Erkennung angegeben wurden. Standardwert ist false.

## Beispiele

Dieses Beispiel zeigt, wie man Erkennungsergebnisse nur auf die angeforderten Barcode-Typen beschränkt

```csharp
[C#]
//EAN13-Barcode erzeugen
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//Nur UPCA-Barcodes erkennen (keine Ergebnisse, weil die Quelle EAN13 ist)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//Kompatible Typen erkennen: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 wird als UPCA-Äquivalent zurückgegeben)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### Siehe auch

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


