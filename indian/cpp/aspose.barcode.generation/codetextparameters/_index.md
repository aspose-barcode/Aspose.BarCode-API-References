---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::CodetextParameters class. C++ में Codetext पैरामीटर।"
type: docs
weight: 1500
url: /hi/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


कोडटेक्स्ट पैरामीटर।

```cpp
class CodetextParameters : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | कोड टेक्स्ट की संरेखण प्राप्त करता है। डिफ़ॉल्ट मान: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | CodeText के प्रदर्शित रंग को निर्दिष्ट करें। डिफ़ॉल्ट मान: Color.Black. |
| [get_Font](./get_font/)() const | कोडटेक्स्ट के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। डिफ़ॉल्ट मान: Arial 5pt regular। यदि FontMode को [FontMode.Auto](../aztecencodemode/) पर सेट किया गया है तो इसे अनदेखा किया जाता है। |
| [get_FontMode](./get_fontmode/)() const | FontMode को निर्दिष्ट करें। यदि FontMode Auto पर सेट है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। यह विशेष रूप से [FontMode.Auto](../aztecencodemode/) का उपयोग करने की सलाह दी जाती है, विशेषकर [AutoSizeMode.Nearest](../autosizemode/) या [AutoSizeMode.Interpolation](../autosizemode/) में। डिफ़ॉल्ट मान: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | कोडटेक्स्ट के प्रदर्शित स्थान को निर्दिष्ट करें, कोडटेक्स्ट को छिपाने के लिए [CodeLocation.None](../codelocation/) सेट करें। डिफ़ॉल्ट मान: 1D बारकोड के लिए [CodeLocation.Below](../codelocation/) और 2D बारकोड के लिए [CodeLocation.None](../codelocation/)। |
| [get_NoWrap](./get_nowrap/)() const | पाठ के भीतर शब्द रैप (लाइन ब्रेक) निर्दिष्ट करें। डिफ़ॉल्ट मान: false। |
| [get_Space](./get_space/)() const | कोडटेक्स्ट और [BarCode](../../aspose.barcode/) के बीच का अंतराल, [Unit ](../unit/) मान में। डिफ़ॉल्ट मान: 2pt। EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon के लिए इसे अनदेखा किया जाता है। |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | 2D बारकोड में कोडटेक्स्ट के बजाय प्रदर्शित किया जाने वाला पाठ। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode। |
| [set_Alignment](./set_alignment/)(TextAlignment) | कोड टेक्स्ट की संरेखण सेट करता है। डिफ़ॉल्ट मान: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | CodeText के प्रदर्शित रंग को निर्दिष्ट करें। डिफ़ॉल्ट मान: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | FontMode को निर्दिष्ट करें। यदि FontMode Auto पर सेट है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। यह विशेष रूप से [FontMode.Auto](../aztecencodemode/) का उपयोग करने की सलाह दी जाती है, विशेषकर [AutoSizeMode.Nearest](../autosizemode/) या [AutoSizeMode.Interpolation](../autosizemode/) में। डिफ़ॉल्ट मान: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | कोडटेक्स्ट के प्रदर्शित स्थान को निर्दिष्ट करें, कोडटेक्स्ट को छिपाने के लिए [CodeLocation.None](../codelocation/) सेट करें। डिफ़ॉल्ट मान: 1D बारकोड के लिए [CodeLocation.Below](../codelocation/) और 2D बारकोड के लिए [CodeLocation.None](../codelocation/)। |
| [set_NoWrap](./set_nowrap/)(bool) | पाठ के भीतर शब्द रैप (लाइन ब्रेक) निर्दिष्ट करें। डिफ़ॉल्ट मान: false। |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | कोडटेक्स्ट और [BarCode](../../aspose.barcode/) के बीच का अंतराल, [Unit ](../unit/) मान में। डिफ़ॉल्ट मान: 2pt। EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon के लिए इसे अनदेखा किया जाता है। |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | 2D बारकोड में कोडटेक्स्ट के बजाय प्रदर्शित किया जाने वाला पाठ। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode। |
| [ToString](./tostring/)() const override | इस [CodetextParameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
