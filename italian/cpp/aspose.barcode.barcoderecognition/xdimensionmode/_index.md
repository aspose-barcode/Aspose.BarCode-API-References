---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare l'enumerazione in C++."
type: docs
weight: 4000
url: /it/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | Il valore di XDimension è rilevato dall'AI (SVM). Al momento è lo stesso di Normal |
| Small | 1 | Rileva codici a barre con XDimension piccola di 1 pixel o più con qualità da BarcodeQuality |
| Normal | 2 | Rileva codici a barre con XDimension classica di 2 pixel o più con qualità da BarcodeQuality o codici a barre ad alta qualità. |
| Large | 3 | Rileva codici a barre con XDimension grande con qualità da BarcodeQuality catturata con fotocamere ad alta risoluzione. |
| UseMinimalXDimension | 4 | Rileva i codici a barre dalla dimensione impostata in MinimalXDimension con qualità da BarcodeQuality |

## Osservazioni


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

Questo esempio mostra come utilizzare la modalità XDimension
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
