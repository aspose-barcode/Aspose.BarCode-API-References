---
title: "Enum DeconvolutionMode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. Modalità di deconvoluzione per il ripristino delle immagini che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione che può ripristinare un'immagine degradata e convoluta da qualsiasi funzione naturale come la sfocatura durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione dell'immagine che la corrode, dobbiamo verificare le funzioni più conosciute come sharp o la morfologia matematica"
type: docs
weight: 240
url: /it/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Modalità di deconvoluzione (ripristino delle immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione che può ripristinare un'immagine degradata (convoluta) da qualsiasi funzione naturale come la sfocatura, durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione dell'immagine che la corrompe, dobbiamo verificare le funzioni più conosciute come sharp o la morfologia matematica.

```csharp
public enum DeconvolutionMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Fast | `0` | Abilita metodi di deconvoluzione rapidi per immagini di alta qualità. |
| Normal | `1` | Abilita metodi di deconvoluzione normali per immagini comuni. |
| Slow | `2` | Abilita metodi di deconvoluzione lenti per immagini di bassa qualità. |

## Esempi

Questo esempio mostra come utilizzare la modalità Deconvolution

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Vedi anche

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


