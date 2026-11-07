---
title: "विधि"
linktitle: "TryParse"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " method. ब्रैकेटेड GS1 एलिमेंट स्ट्रिंग को (AI)value(AI)value रूप में पार्स करने का प्रयास करता है और संरचित वैधता त्रुटियाँ लौटाता है। मान के अंदर एक लिटरल '(' को (; के रूप में लिखा जाना चाहिए; कोई अन्य एस्केप सीक्वेंस समर्थित नहीं है, और ')' को C++ में एस्केप करने की आवश्यकता नहीं है।"
type: docs
weight: 1600
url: /hi/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


ब्रैकेटेड GS1 तत्व स्ट्रिंग को (AI)value(AI)value के रूप में पार्स करने का प्रयास करता है और संरचित सत्यापन त्रुटियां लौटाता है। मान के भीतर एक साधारण '(' को (; के रूप में लिखा जाना चाहिए; कोई अन्य एस्केप सीक्वेंस समर्थित नहीं है, और ')' को एस्केप करने की आवश्यकता नहीं है।

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | System::String | पार्स करने के लिए ब्रैकेटेड GS1 एलिमेंट स्ट्रिंग। |
| result | System::SharedPtr\<GS1Codetext\>\& | जब यह method true लौटाता है, तो इसमें पार्स किया गया GS1 कोडटेक्स्ट होता है; अन्यथा null। |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | वैधता परिणाम को शामिल करता है, या जब *value* null हो तो null। |

### ReturnValue

पार्सिंग सफल होने पर true; अन्यथा false।

## और देखें

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
