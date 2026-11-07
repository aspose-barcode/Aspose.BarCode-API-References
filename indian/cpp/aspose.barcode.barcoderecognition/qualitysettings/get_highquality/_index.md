---
title: "विधि"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "मेथड। HighQuality पहचान गुणवत्ता प्रीसेट। यह प्रीसेट कम गुणवत्ता वाले बारकोड के लिए विकसित किया गया है। C++ में अत्यधिक क्षतिग्रस्त बारकोड का पता लगाने की अनुमति देता है।"
type: docs
weight: 300
url: /hi/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


HighQuality पहचान गुणवत्ता प्रीसेट। यह प्रीसेट कम गुणवत्ता वाले बारकोड के लिए विकसित किया गया है। यह अत्यधिक क्षतिग्रस्त बारकोड का पता लगाने की अनुमति देता है।

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## टिप्पणियाँ


यह नमूना दिखाता है कि HighQuality मोड का उपयोग कैसे करें
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighQuality पहचान गुणवत्ता प्रीसेट।
## और देखें

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
