---
title: "Enum XDimensionMode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Enum Aspose.BarCode.BarCodeRecognition.XDimensionMode. Modalità di riconoscimento che imposta la dimensione da 1 all'infinito dell'elemento minimo del codice a barre, cella della matrice o barra"
type: docs
weight: 400
url: /it/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Modalità di riconoscimento che imposta la dimensione (da 1 all'infinito) dell'elemento minimo del codice a barre: cella della matrice o barra.

```csharp
public enum XDimensionMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | Il valore di XDimension è rilevato dall'IA (SVM). Al momento è lo stesso di Normale |
| Small | `1` | Rileva codici a barre con XDimension piccolo da 1 pixel o più con qualità da BarcodeQuality |
| Normal | `2` | Rileva codici a barre con XDimension classico da 2 pixel o più con qualità da BarcodeQuality o codici a barre di alta qualità. |
| Large | `3` | Rileva codici a barre con XDimension grande con qualità da BarcodeQuality catturata con telecamere ad alta risoluzione. |
| UseMinimalXDimension | `4` | Rileva codici a barre dalla dimensione impostata in MinimalXDimension con qualità da BarcodeQuality |

## Esempi

Questo esempio mostra come utilizzare la modalità XDimension

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Vedi anche

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


