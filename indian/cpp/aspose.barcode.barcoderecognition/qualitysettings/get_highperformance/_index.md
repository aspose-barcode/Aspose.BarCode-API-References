---
title: "विधि"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " विधि। HighPerformance पहचान गुणवत्ता प्रीसेट। इस मोड में उच्च गुणवत्ता वाले बारकोड अच्छी तरह पहचाने जाते हैं, C++ में।"
type: docs
weight: 100
url: /hi/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


HighPerformance पहचान गुणवत्ता प्रीसेट। इस मोड में उच्च गुणवत्ता वाले बारकोड अच्छी तरह से पहचाने जाते हैं।

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## टिप्पणियाँ


यह उदाहरण दिखाता है कि HighPerformance मोड का उपयोग कैसे करें।
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighPerformance पहचान गुणवत्ता प्रीसेट।
## और देखें

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
