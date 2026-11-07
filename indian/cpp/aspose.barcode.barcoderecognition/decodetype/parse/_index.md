---
title: "विधि"
linktitle: "Parse"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "विधि। स्ट्रिंग प्रतिनिधित्व को एक SingleDecodeType के उदाहरण में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि C++ में रूपांतरण सफल हुआ या विफल।"
type: docs
weight: 400
url: /hi/cpp/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType::Parse method


एक [SingleDecodeType](../../singledecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::Parse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | System::String | एक स्ट्रिंग जिसमें एक [SingleDecodeType](../../singledecodetype/) \"EAN8\" या \"EAN13\" या \"CodaBar\"... के रूप में हो, जिसे परिवर्तित किया जाना है। |
| result | System::SharedPtr\<SingleDecodeType\>\& | एक वास्तविक [SingleDecodeType](../../singledecodetype/) लौटाता है, जब रूपांतरण सफलतापूर्वक पूरा हो जाता है; अन्यथा यह अनिश्चित प्रकार लौटाता है: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## और देखें

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
