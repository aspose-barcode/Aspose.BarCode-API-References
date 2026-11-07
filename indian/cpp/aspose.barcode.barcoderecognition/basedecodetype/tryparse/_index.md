---
title: "विधि"
linktitle: "TryParse"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "विधि। स्ट्रिंग प्रतिनिधित्व को एक SingleDecodeType के उदाहरण में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि C++ में रूपांतरण सफल हुआ या विफल।"
type: docs
weight: 400
url: /hi/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


एक [SingleDecodeType](../../singledecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | System::String | एक स्ट्रिंग जिसमें एक [SingleDecodeType](../../singledecodetype/) \"EAN8\" या \"EAN13\" या \"CodaBar\"... के रूप में हो, जिसे परिवर्तित किया जाना है। |
| result | System::SharedPtr\<SingleDecodeType\>\& | जब रूपांतरण सफलतापूर्वक पूरा हो जाता है तो एक वास्तविक [SingleDecodeType](../../singledecodetype/) लौटाया जाता है; अन्यथा यह अनिश्चित प्रकार लौटाता है: [DecodeType.None](../../decodetype/none/)। |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## और देखें

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


एक [MultiDecodeType](../../multidecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | System::String | एक स्ट्रिंग जिसमें एक [MultiDecodeType](../../multidecodetype/) प्रतिनिधित्व हो, जिसे परिवर्तित किया जाना है। |
| result | System::SharedPtr\<MultiDecodeType\>\& | जब रूपांतरण सफलतापूर्वक पूरा हो जाता है तो एक वास्तविक [MultiDecodeType](../../multidecodetype/) लौटाया जाता है; अन्यथा यह अनिश्चित प्रकार लौटाता है: नया [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## और देखें

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


एक [BaseDecodeType](../) की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है, वास्तविक प्रकार निर्धारित करने के बाद। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | System::String | एक स्ट्रिंग जिसमें एक [MultiDecodeType](../../multidecodetype/) प्रतिनिधित्व हो, जिसे परिवर्तित किया जाना है। |
| result | System::SharedPtr\<BaseDecodeType\>\& | जब रूपांतरण सफलतापूर्वक पूरा हो जाता है तो एक वास्तविक [MultiDecodeType](../../multidecodetype/) लौटाया जाता है; अन्यथा यह अनिश्चित प्रकार लौटाता है: [DecodeType.None](../../decodetype/none/)। |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## और देखें

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
