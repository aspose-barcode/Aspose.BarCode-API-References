---
title: "Enum DeconvolutionMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. डिकॉन्भोल्यूशन इमेज पुनर्स्थापना मोड जो छवि क्षरण के स्तर को परिभाषित करता है। मूल रूप से डिकॉन्भोल्यूशन एक फ़ंक्शन है जो कैमरा द्वारा छवि प्राप्त करने के दौरान ब्लर जैसी किसी भी प्राकृतिक फ़ंक्शन द्वारा विकृत छवि को पुनर्स्थापित कर सकता है। क्योंकि हम उस छवि फ़ंक्शन का पता नहीं लगा सकते जो छवि को भ्रष्ट करता है, हमें सबसे ज्ञात फ़ंक्शन जैसे शार्प या गणितीय मॉरफ़ोलॉजी की जाँच करनी पड़ती है।"
type: docs
weight: 240
url: /hi/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Deconvolution (इमेज रिस्टोरेशन) मोड जो इमेज क्षय के स्तर को परिभाषित करता है। मूल रूप से डिकनवोल्यूशन एक फ़ंक्शन है जो कैमरा द्वारा छवि प्राप्त करने के दौरान ब्लर जैसी किसी भी प्राकृतिक फ़ंक्शन द्वारा क्षतिग्रस्त (कन्वॉल्यूटेड) इमेज को पुनर्स्थापित कर सकता है। चूंकि हम उस इमेज फ़ंक्शन का पता नहीं लगा सकते जो इमेज को भ्रष्ट करता है, हमें शार्प या गणितीय मोर्फ़ोलॉजी जैसी सबसे ज्ञात फ़ंक्शनों की जाँच करनी पड़ती है।

```csharp
public enum DeconvolutionMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Fast | `0` | उच्च गुणवत्ता वाली छवियों के लिए तेज़ डिकॉन्भोल्यूशन विधियों को सक्षम करता है। |
| Normal | `1` | सामान्य छवियों के लिए सामान्य डीकोन्वॉल्यूशन विधियों को सक्षम बनाता है। |
| Slow | `2` | कम गुणवत्ता वाली छवियों के लिए धीमी डीकोन्वॉल्यूशन विधियों को सक्षम बनाता है। |

## उदाहरण

यह नमूना दिखाता है कि डीकोन्वॉल्यूशन मोड का उपयोग कैसे करें

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


