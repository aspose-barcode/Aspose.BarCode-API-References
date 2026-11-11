---
title: "Enum ComplexBackgroundMode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode enum. Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori"
type: docs
weight: 200
url: /it/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori.

```csharp
public enum ComplexBackgroundMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | Attualmente è lo stesso di Disabled. Disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. |
| Disabled | `1` | Disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. |
| Enabled | `2` | Abilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. |

## Esempi

Questo esempio mostra come utilizzare la modalità ComplexBackground

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Vedi anche

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


