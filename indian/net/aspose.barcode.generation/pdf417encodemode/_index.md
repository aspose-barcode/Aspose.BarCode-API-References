---
title: "Enum Pdf417EncodeMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.Pdf417EncodeMode enum. Pdf417 बारकोड एन्कोड मोड"
type: docs
weight: 1540
url: /hi/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Pdf417 बारकोड एन्कोड मोड

```csharp
public enum Pdf417EncodeMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Auto | `0` | Auto मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। Unicode अक्षरों को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और एक ECI पहचानकर्ता डाला जाता है। यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है। |
| Binary | `1` | Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यदि कोई Unicode अक्षर पाया जाता है, तो एक अपवाद फेंका जाता है। |
| ECI | `2` | ECI मोड में, पूरे संदेश को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और एक ECI पहचानकर्ता डाला जाता है। यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है। कृपया ध्यान दें कि कुछ पुराने (2006 से पूर्व) स्कैनर इस मोड का समर्थन नहीं कर सकते हैं। |
| Extended | `3` | विस्तारित मोड जो कई ECI मोडों का समर्थन करता है। |

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


