---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Proprietà BarcodeSettings. Restituisce solo i tipi di codice a barre specificati esplicitamente per il riconoscimento. Quando abilitato, i codici a barre riconosciuti di altri tipi compatibili o equivalenti vengono filtrati. Il valore predefinito è false"
type: docs
weight: 50
url: /it/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Restituisce solo i tipi di codice a barre specificati esplicitamente per il riconoscimento. Quando abilitato, i codici a barre riconosciuti di altri tipi compatibili o equivalenti vengono filtrati. Il valore predefinito è false.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Restituisce solo i tipi di codice a barre specificati esplicitamente per il riconoscimento. Il valore predefinito è false.

## Esempi

Questo esempio mostra come limitare i risultati del riconoscimento solo ai tipi di codice a barre richiesti

```csharp
[C#]
//genera codice a barre EAN13
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//riconosci solo codici a barre UPCA (nessun risultato, perché la sorgente è EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//riconosci tipi compatibili: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 verrà restituito come equivalente UPCA)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### Vedi anche

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


