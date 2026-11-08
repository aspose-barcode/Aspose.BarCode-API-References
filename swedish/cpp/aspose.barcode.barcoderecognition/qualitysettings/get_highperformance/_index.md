---
title: "metod"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. HighPerformance‑igenkänningskvalitetspreset. Högkvalitativa streckkoder känns igen väl i detta läge i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


HighPerformance‑förinställning för igenkänningskvalitet. Högkvalitativa streckkoder känns igen väl i detta läge.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## Anmärkningar


Detta exempel visar hur man använder HighPerformance‑läget
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighPerformance‑igenkänningskvalitetspreset.
## Se även

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
