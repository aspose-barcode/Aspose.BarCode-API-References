---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je enum in C++."
type: docs
weight: 4000
url: /nl/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | 0 | Waarde van XDimension wordt gedetecteerd door AI (SVM). Op dit moment hetzelfde als Normaal |
| Klein | 1 | Detecteert barcodes met een kleine XDimension van 1 pixel of meer met kwaliteit van BarcodeQuality |
| Normal | 2 | Detecteert barcodes met een klassieke XDimension van 2 pixels of meer met kwaliteit van BarcodeQuality of barcodes van hoge kwaliteit. |
| Groot | 3 | Detecteert barcodes met een grote XDimension met kwaliteit van BarcodeQuality, vastgelegd met hoge-resolutiecamera's. |
| UseMinimalXDimension | 4 | Detecteert barcodes van grootte ingesteld in MinimalXDimension met kwaliteit van BarcodeQuality |

## Opmerkingen


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

Dit voorbeeld toont hoe XDimension-modus te gebruiken
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
