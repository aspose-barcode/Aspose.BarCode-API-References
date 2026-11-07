---
title: "विधि"
linktitle: "Parse"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "विधि। BaseEncodeType के स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि C++ में परिवर्तन सफल हुआ या विफल।"
type: docs
weight: 300
url: /hi/cpp/aspose.barcode.generation/encodetypes/parse/
---
## EncodeTypes::Parse method


एक [BaseEncodeType](../../baseencodetype/) की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::Parse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | System::String | एक स्ट्रिंग जिसमें परिवर्तित करने के लिए [BaseEncodeType](../../baseencodetype/) प्रतिनिधित्व शामिल है। |
| result | System::SharedPtr\<BaseEncodeType\>\& | जब रूपांतरण सफलतापूर्वक पूरा हो जाता है, तब एक वास्तविक [BaseEncodeType](../../baseencodetype/) लौटाता है; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## टिप्पणियाँ



अन्यथा यह null लौटाता है।

## और देखें

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
