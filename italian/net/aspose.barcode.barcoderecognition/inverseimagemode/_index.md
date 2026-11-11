---
title: "Enum InverseImageMode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con luminanza dei colori invertita"
type: docs
weight: 270
url: /it/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti (luminanza).

```csharp
public enum InverseImageMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | Disabilita il riconoscimento aggiuntivo di codici a barre su immagini inverse per tutti i tipi di codice a barre tranne QR Code. |
| Disabled | `1` | Disabilita il riconoscimento aggiuntivo di codici a barre su immagini inverse. |
| Enabled | `2` | Abilita il riconoscimento aggiuntivo di codici a barre su immagini inverse |

## Esempi

Questo esempio mostra come utilizzare la modalità InverseImage

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Vedi anche

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


