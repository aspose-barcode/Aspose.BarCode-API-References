---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode Python के लिए .NET API रेफ़रेंस"
description: 
type: docs
url: /hi/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

बारकोड इमेज जनरेशन पैरामीटर।

यह BaseGenerationParameters प्रकार निम्नलिखित सदस्यों को उजागर करता है:
## गुण
| नाम | विवरण |
| :- | :- |
| use_anti_alias | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि छवि रेंडर करने के लिए anti-aliasing मोड उपयोग किया गया है या नहीं |
| back_color | बारकोड छवि का पृष्ठभूमि रंग।<br/>            डिफ़ॉल्ट मान: Color.White.<br/>            देखें [Color](/barcode/python-net/aspose.drawing/color/). |
| रिज़ॉल्यूशन | BarCode छवि का रिज़ॉल्यूशन प्राप्त करता है या सेट करता है।<br/>            दोनों आयामों के लिए एक मान।<br/>            डिफ़ॉल्ट मान: 96 dpi. |
| rotation_angle | BarCode छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है।<br/>            यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है।<br/>            डिफ़ॉल्ट मान: 0. |
| caption_above | BarCode छवि के ऊपर कैप्शन। देखें [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | BarCode छवि के नीचे कैप्शन। देखें [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | छवि पैरामीटर। देखें [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | स्वचालित आकार निर्धारण मोड के विभिन्न प्रकार निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट मान: AutoSizeMode.None. |
| image_height | BarCode छवि की ऊँचाई जब [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) प्रॉपर्टी AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट हो। |
| image_width | BarCode छवि की चौड़ाई जब [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) प्रॉपर्टी AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट हो। |
| barcode | यह [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) प्राप्त करता है जिसमें सभी बारकोड गुण शामिल हैं। |
| border | यह [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) प्राप्त करता है जिसमें बारकोड बॉर्डर के सभी कॉन्फ़िगरेशन गुण शामिल हैं। |

### संबंधित देखें

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

