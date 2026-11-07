---
title: "विधि"
linktitle: "TryParse"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "विधि। BaseEncodeType के स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि C++ में परिवर्तन सफल हुआ या विफल।"
type: docs
weight: 400
url: /hi/cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


एक [BaseEncodeType](../../baseencodetype/) की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | System::String | परिवर्तित करने के लिए \"Index:-1; Name:None\" स्वरूप की स्ट्रिंग। |
| result | System::SharedPtr\<BaseEncodeType\>\& | जब परिवर्तन सफलतापूर्वक पूर्ण हो जाता है, तो एक वास्तविक SingleEncodeType लौटाता है; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## टिप्पणियाँ



अन्यथा यह null लौटाता है।

## और देखें

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
