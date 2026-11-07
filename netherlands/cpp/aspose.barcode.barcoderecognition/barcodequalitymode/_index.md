---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je enum in C++."
type: docs
weight: 3600
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| High | 0 | Schakelt herkenningsmethoden in voor barcodes van hoge kwaliteit. |
| Normal | 1 | Schakelt herkenningsmethoden in voor barcodes van gewone (normale) kwaliteit. |
| Low | 2 | Schakelt herkenningsmethoden in voor barcodes van lage kwaliteit. |

## Opmerkingen


Modus die methoden inschakelt om barcode‑elementen te herkennen met de geselecteerde kwaliteit. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, wat de herkenning vertraagt.

Dit voorbeeld laat zien hoe u de BarcodeQuality-modus gebruikt
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
