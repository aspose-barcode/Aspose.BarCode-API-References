---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " enum. C++ में Pdf417 बारकोड एन्कोड मोड।"
type: docs
weight: 7900
url: /hi/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Pdf417 बारकोड एन्कोड मोड

```cpp
enum class Pdf417EncodeMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ऑटो | 0 | Auto मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यूनिकोड अक्षरों को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और ECI पहचानकर्ता डाला जाता है। यदि कोई ऐसा अक्षर मिलता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक exception फेंका जाता है। |
| Binary | 1 | Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यदि कोई यूनिकोड अक्षर मिलता है, तो एक exception फेंका जाता है। |
| ECI | 2 | ECI मोड में, संपूर्ण संदेश को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और ECI पहचानकर्ता डाला जाता है। यदि कोई ऐसा अक्षर मिलता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक exception फेंका जाता है। कृपया ध्यान दें कि कुछ पुराने (2006 से पहले) स्कैनर इस मोड का समर्थन नहीं कर सकते हैं। |
| Extended | 3 |  |

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
