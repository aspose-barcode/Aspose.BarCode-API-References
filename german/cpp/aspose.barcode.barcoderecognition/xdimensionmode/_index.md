---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man das enum in C++ verwendet."
type: docs
weight: 4000
url: /de/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Der Wert von XDimension wird von KI (SVM) ermittelt. Derzeit identisch mit Normal. |
| Klein | 1 | Erkennt Barcodes mit kleiner XDimension von 1 Pixel oder mehr mit Qualität von BarcodeQuality |
| Normal | 2 | Erkennt Barcodes mit klassischer XDimension von 2 Pixeln oder mehr mit Qualität von BarcodeQuality oder hochwertigen Barcodes. |
| Groß | 3 | Erkennt Barcodes mit großem XDimension und Qualität aus BarcodeQuality, aufgenommen mit hochauflösenden Kameras. |
| UseMinimalXDimension | 4 | Erkennt Barcodes anhand der in MinimalXDimension festgelegten Größe und Qualität aus BarcodeQuality. |

## Hinweise


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

Dieses Beispiel zeigt, wie man den XDimension-Modus verwendet.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
