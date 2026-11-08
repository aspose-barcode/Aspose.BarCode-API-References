---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder enum i C++."
type: docs
weight: 4000
url: /sv/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | Värdet för XDimension upptäcks av AI (SVM). För närvarande samma som Normal |
| Small | 1 | Detekterar streckkoder med liten XDimension på 1 pixel eller mer med kvalitet från BarcodeQuality |
| Normal | 2 | Detekterar streckkoder med klassisk XDimension på 2 pixlar eller mer med kvalitet från BarcodeQuality eller högkvalitativa streckkoder. |
| Large | 3 | Detekterar streckkoder med stor XDimension med kvalitet från BarcodeQuality fångade med högupplösta kameror. |
| UseMinimalXDimension | 4 | Detekterar streckkoder från storlek som anges i MinimalXDimension med kvalitet från BarcodeQuality |

## Anmärkningar


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

Detta exempel visar hur man använder XDimension-läget
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
