---
title: "विधि"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "मेथड। MaxQuality पहचान गुणवत्ता प्रीसेट। यह प्रीसेट सभी संभावित बारकोड को पहचानने के लिए विकसित किया गया है, यहाँ तक कि C++ में गलत बारकोड भी।"
type: docs
weight: 400
url: /hi/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


MaxQuality पहचान गुणवत्ता प्रीसेट। यह प्रीसेट सभी संभावित बारकोड्स को पहचानने के लिए विकसित किया गया है, यहाँ तक कि गलत बारकोड्स को भी।

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## टिप्पणियाँ


यह नमूना दिखाता है कि MaxQuality मोड का उपयोग कैसे करें
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


MaxQuality पहचान गुणवत्ता प्रीसेट।
## और देखें

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
