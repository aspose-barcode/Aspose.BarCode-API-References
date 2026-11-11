---
title: "Enum BarcodeQualityMode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode enum. Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento"
type: docs
weight: 110
url: /it/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento.

```csharp
public enum BarcodeQualityMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| High | `0` | Abilita i metodi di riconoscimento per codici a barre di alta qualità. |
| Normal | `1` | Abilita i metodi di riconoscimento per codici a barre di qualità comune (normale). |
| Low | `2` | Abilita i metodi di riconoscimento per codici a barre di bassa qualità. |

## Esempi

Questo esempio mostra come utilizzare la modalità BarcodeQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Vedi anche

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


