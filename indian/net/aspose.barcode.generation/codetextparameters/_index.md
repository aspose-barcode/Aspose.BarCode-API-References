---
title: "क्लास CodetextParameters"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.CodetextParameters क्लास। कोडटेक्स्ट पैरामीटर"
type: docs
weight: 1160
url: /hi/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

कोडटेक्स्ट पैरामीटर।

```csharp
public class CodetextParameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | कोड टेक्स्ट की संरेखण प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: StringAlignment.Center। |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | CodeText के रंग को प्रदर्शित करने के लिए निर्दिष्ट करें। डिफ़ॉल्ट मान: Color.Black। |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | CodeText के फ़ॉन्ट को प्रदर्शित करने के लिए निर्दिष्ट करें। डिफ़ॉल्ट मान: Arial 5pt regular। यदि FontMode को FontMode.Auto पर सेट किया गया है तो इसे नजरअंदाज किया जाएगा। |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | FontMode निर्दिष्ट करें। यदि FontMode को Auto पर सेट किया जाता है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। AutoSizeMode.Nearest या AutoSizeMode.Interpolation में विशेष रूप से FontMode.Auto का उपयोग करने की सिफारिश की जाती है। डिफ़ॉल्ट मान: FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | CodeText स्थान के प्रदर्शन को निर्दिष्ट करें, CodeText को छिपाने के लिए CodeLocation.None सेट करें। डिफ़ॉल्ट मान: 1D बारकोड के लिए CodeLocation.Below और 2D बारकोड के लिए CodeLocation.None। |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | टेक्स्ट के भीतर शब्द रैप (लाइन ब्रेक) निर्दिष्ट करें। डिफ़ॉल्ट मान: false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | CodeText और BarCode के बीच की स्पेस [`Unit`](../unit/) मान में। डिफ़ॉल्ट मान: 2pt। EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon के लिए अनदेखा किया जाता है। |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | 2D बारकोड में codetext के बजाय प्रदर्शित किया जाने वाला पाठ। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | `CodetextParameters` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


