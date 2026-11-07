---
title: "विधि"
linktitle: "TryParse"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " method. MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में बदलता है। एक रिटर्न वैल्यू दर्शाती है कि परिवर्तन C++ में सफल हुआ या नहीं।"
type: docs
weight: 1100
url: /hi/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


[MultiDecodeType](../) की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में बदलता है। एक रिटर्न वैल्यू दर्शाती है कि परिवर्तन सफल हुआ या नहीं।

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | System::String | परिवर्तन के लिए "AllSupportedTypes" या "EAN8,EAN13,CodaBar" स्वरूप की स्ट्रिंग। |
| result | System::SharedPtr\<MultiDecodeType\>\& | जब परिवर्तन सफलतापूर्वक पूरा हो जाता है, तो वास्तविक [MultiDecodeType](../) लौटाया जाता है; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## टिप्पणियाँ



अन्यथा यह अनिश्चित प्रकार लौटाता है।

या [MultiDecodeType](../) ("None").

## और देखें

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
