---
title: "enum"
linktitle: "बारकोड गुणवत्ता मोड"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में enum का उपयोग कैसे करें।"
type: docs
weight: 3600
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| उच्च | 0 | उच्च गुणवत्ता वाले बारकोड के लिए पहचान विधियों को सक्षम करता है। |
| सामान्य | 1 | सामान्य (Normal) गुणवत्ता वाले बारकोड के लिए पहचान विधियों को सक्षम करता है। |
| निम्न | 2 | निम्न गुणवत्ता वाले बारकोड के लिए पहचान विधियों को सक्षम करता है। |

## टिप्पणियाँ


वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने की विधियों को सक्षम करता है। कम गुणवत्ता वाले बारकोड तत्वों को पहचानने के लिए अधिक कठिन विधियों की आवश्यकता होती है, जिससे पहचान धीमी हो जाती है।

यह नमूना दिखाता है कि BarcodeQuality मोड का उपयोग कैसे करें
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
