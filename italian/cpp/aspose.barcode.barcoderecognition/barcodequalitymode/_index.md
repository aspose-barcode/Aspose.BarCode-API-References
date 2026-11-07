---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare l'enumerazione in C++."
type: docs
weight: 3600
url: /it/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| High | 0 | Abilita i metodi di riconoscimento per i codici a barre di alta qualità. |
| Normal | 1 | Abilita i metodi di riconoscimento per i codici a barre di qualità comune (Normale). |
| Low | 2 | Abilita i metodi di riconoscimento per i codici a barre di bassa qualità. |

## Osservazioni


Modalità che abilita i metodi per riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento.

Questo esempio mostra come utilizzare la modalità BarcodeQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
