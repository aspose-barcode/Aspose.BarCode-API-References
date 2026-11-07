---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में enum का उपयोग कैसे करें।"
type: docs
weight: 3800
url: /hi/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| तेज़ | 0 | उच्च गुणवत्ता वाली छवियों के लिए तेज डीकोन्वॉल्यूशन विधियों को सक्षम करता है। |
| सामान्य | 1 | सामान्य छवियों के लिए सामान्य डीकोन्वॉल्यूशन विधियों को सक्षम करता है। |
| धीमा | 2 | निम्न गुणवत्ता वाली छवियों के लिए धीमी डीकोन्वॉल्यूशन विधियों को सक्षम करता है। |

## टिप्पणियाँ


Deconvolution (इमेज रिस्टोरेशन) मोड जो छवि क्षय के स्तर को परिभाषित करता है। मूल रूप से डिकॉन्भोल्यूशन एक फ़ंक्शन है जो कैमरा द्वारा छवि प्राप्त करने के दौरान ब्लर जैसी किसी भी प्राकृतिक फ़ंक्शन द्वारा क्षतिग्रस्त (कन्वॉल्यूटेड) छवि को पुनर्स्थापित कर सकता है। क्योंकि हम उस फ़ंक्शन का पता नहीं लगा सकते जो छवि को भ्रष्ट करता है, हमें सबसे ज्ञात फ़ंक्शन जैसे शार्प या गणितीय मोर्फ़ोलॉजी की जाँच करनी पड़ती है।

यह उदाहरण दिखाता है कि Deconvolution मोड का उपयोग कैसे करें
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
