---
title: "विधि"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। NormalQuality पहचान गुणवत्ता प्रीसेट। C++ में अधिकांश बारकोड के लिए उपयुक्त।"
type: docs
weight: 200
url: /hi/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


NormalQuality पहचान गुणवत्ता प्रीसेट। अधिकांश बारकोड्स के लिए उपयुक्त।

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## टिप्पणियाँ


यह नमूना दिखाता है कि NormalQuality मोड का उपयोग कैसे करें
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


NormalQuality पहचान गुणवत्ता प्रीसेट।
## और देखें

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
