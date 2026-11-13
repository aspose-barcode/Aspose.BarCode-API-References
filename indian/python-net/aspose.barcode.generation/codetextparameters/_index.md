---
title: "CodetextParameters"
second_title: "Aspose.BarCode Python के लिए .NET API रेफ़रेंस"
description: 
type: docs
url: /hi/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Codetext पैरामीटर।

CodetextParameters प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:
## गुण
| नाम | विवरण |
| :- | :- |
| two_d_display_text | 2D बारकोड में कोडटेक्स्ट के बजाय प्रदर्शित किया जाने वाला टेक्स्ट।<br/>            उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | FontMode निर्दिष्ट करें। यदि FontMode को Auto पर सेट किया जाता है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा।<br/>            विशेष रूप से AutoSizeMode.Nearest या AutoSizeMode.Interpolation में FontMode.Auto का उपयोग करने की सलाह दी जाती है।<br/>            डिफ़ॉल्ट मान: FontMode.Auto. |
| font | प्रदर्शित होने वाले CodeText के फ़ॉन्ट को निर्दिष्ट करें.<br/>            डिफ़ॉल्ट मान: Arial 5pt regular.<br/>            यदि FontMode को FontMode.Auto पर सेट किया गया है तो इसे नज़रअंदाज़ किया जाएगा. |
| space | [Unit](/barcode/python-net/aspose.barcode.generation/unit/) मान में CodeText और BarCode के बीच का अंतराल।<br/>            डिफ़ॉल्ट मान: 2pt.<br/>            EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon के लिए नज़रअंदाज़ किया जाता है. |
| संरेखण | कोड टेक्स्ट का संरेखण प्राप्त करता है या सेट करता है।<br/>            डिफ़ॉल्ट मान: StringAlignment.Center. |
| रंग | CodeText के प्रदर्शित रंग को निर्दिष्ट करें।<br/>            डिफ़ॉल्ट मान: Color.Black. |
| स्थान | CodeText के प्रदर्शित स्थान को निर्दिष्ट करें, CodeText को छिपाने के लिए CodeLocation.None सेट करें।<br/>            डिफ़ॉल्ट मान: 1D बारकोड के लिए CodeLocation.Below और 2D बारकोड के लिए CodeLocation.None. |
| no_wrap | पाठ के भीतर शब्द रैप (लाइन ब्रेक) निर्दिष्ट करें।<br/>            डिफ़ॉल्ट मान: false. |

### संबंधित देखें

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

