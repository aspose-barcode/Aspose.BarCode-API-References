---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare l'enumerazione in C++."
type: docs
weight: 3800
url: /it/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Veloce | 0 | Abilita metodi di deconvoluzione veloci per immagini ad alta qualità. |
| Normal | 1 | Abilita metodi di deconvoluzione normali per immagini comuni. |
| Lento | 2 | Abilita metodi di deconvoluzione lenti per immagini a bassa qualità. |

## Osservazioni


Modalità di deconvoluzione (restauro delle immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione che può ripristinare un'immagine degradata (convoluta) da qualsiasi funzione naturale come il blur, durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione che corrompe l'immagine, dobbiamo verificare le funzioni più conosciute come sharp o la morfologia matematica.

Questo esempio mostra come utilizzare la modalità Deconvolution
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
