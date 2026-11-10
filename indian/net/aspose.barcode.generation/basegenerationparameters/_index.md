---
title: "क्लास BaseGenerationParameters"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.BaseGenerationParameters क्लास। बारकोड इमेज जेनरेशन पैरामीटर"
type: docs
weight: 1030
url: /hi/net/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class

बारकोड इमेज जनरेशन पैरामीटर।

```csharp
public class BaseGenerationParameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.generation/basegenerationparameters/autosizemode/) { get; set; } | स्वचालित साइजिंग मोड के विभिन्न प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट मान: AutoSizeMode.None. |
| [BackColor](../../aspose.barcode.generation/basegenerationparameters/backcolor/) { get; set; } | बारकोड इमेज की बैकग्राउंड रंग। डिफ़ॉल्ट मान: Color.White। देखें Color. |
| [Barcode](../../aspose.barcode.generation/basegenerationparameters/barcode/) { get; } | उस [`BarcodeParameters`](../barcodeparameters/) को प्राप्त करता है जिसमें सभी बारकोड प्रॉपर्टीज़ शामिल हैं। |
| [Border](../../aspose.barcode.generation/basegenerationparameters/border/) { get; } | उस [`BorderParameters`](../borderparameters/) को प्राप्त करता है जिसमें बारकोड बॉर्डर के सभी कॉन्फ़िगरेशन प्रॉपर्टीज़ शामिल हैं। |
| [CaptionAbove](../../aspose.barcode.generation/basegenerationparameters/captionabove/) { get; } | बारकोड इमेज के ऊपर कैप्शन। देखें [`CaptionParameters`](../captionparameters/). |
| [CaptionBelow](../../aspose.barcode.generation/basegenerationparameters/captionbelow/) { get; } | बारकोड इमेज के नीचे कैप्शन। देखें [`CaptionParameters`](../captionparameters/). |
| [Image](../../aspose.barcode.generation/basegenerationparameters/image/) { get; } | इमेज पैरामीटर। देखें [`ImageParameters`](../imageparameters/). |
| [ImageHeight](../../aspose.barcode.generation/basegenerationparameters/imageheight/) { get; set; } | BarCode छवि की ऊँचाई जब [`AutoSizeMode`](./autosizemode/) प्रॉपर्टी को AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट किया जाता है। |
| [ImageWidth](../../aspose.barcode.generation/basegenerationparameters/imagewidth/) { get; set; } | BarCode छवि की चौड़ाई जब [`AutoSizeMode`](./autosizemode/) प्रॉपर्टी को AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट किया जाता है। |
| [Resolution](../../aspose.barcode.generation/basegenerationparameters/resolution/) { get; set; } | BarCode इमेज का रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। दोनों आयामों के लिए एक ही मान। डिफ़ॉल्ट मान: 96 dpi। |
| [RotationAngle](../../aspose.barcode.generation/basegenerationparameters/rotationangle/) { get; set; } | BarCode छवि का घूर्णन कोण, डिग्री में मापा जाता है, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घुमाव नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0। |
| [UseAntiAlias](../../aspose.barcode.generation/basegenerationparameters/useantialias/) { get; set; } | एक मान प्राप्त करता या सेट करता है जो यह दर्शाता है कि छवि रेंडर करने के लिए एंटी-एलियासिंग मोड उपयोग किया गया है या नहीं। |

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


