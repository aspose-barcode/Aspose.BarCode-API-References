---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " enum. Code128 बारकोड के लिए एन्कोडिंग मोड। C++ में Code128 विनिर्देश।"
type: docs
weight: 5900
url: /hi/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Code128 बारकोड के लिए एन्कोडिंग मोड। Code 128

विनिर्देश।

```cpp
enum class Code128EncodeMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ऑटो | 0 | कोडटेक्स्ट को क्लासिक ISO 15417 मोड में एन्कोड करें। इस मोड का उपयोग सभी सामान्य मामलों में किया जाना चाहिए। |
| CodeA | 1 | कोडटेक्स्ट को केवल 128A कोडसेट में एन्कोड करें। |
| CodeB | 2 | कोडटेक्स्ट को केवल 128B कोडसेट में एन्कोड करें। |
| CodeC | 4 | कोडटेक्स्ट को केवल 128C कोडसेट में एन्कोड करें। |
| CodeAB | 3 | कोडटेक्स्ट को केवल 128A और 128B कोडसेट्स में एन्कोड करें। |
| CodeAC | 5 | कोडटेक्स्ट को केवल 128A और 128C कोडसेट्स में एन्कोड करें। |
| CodeBC | 6 | कोडटेक्स्ट को केवल 128B और 128C कोडसेट्स में एन्कोड करें। |

## टिप्पणियाँ


यह कोड दिखाता है कि विभिन्न एन्कोडिंग्स के साथ कोड 128 कैसे जेनरेट करें।
```cpp
[C#]
//ISO 15417 एन्कोडिंग के साथ कोड 128 जेनरेट करें।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//केवल कोडसेट A एन्कोडिंग के साथ कोड 128 जेनरेट करें।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
