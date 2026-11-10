---
title: "एन्यूम Code128EncodeMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.Code128EncodeMode एन्यूम। Code128 बारकोड के लिए एन्कोडिंग मोड। Code 128 विनिर्देश।"
type: docs
weight: 1120
url: /hi/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

कोड128 बारकोड के लिए एन्कोडिंग मोड। [Code 128](https://en.wikipedia.org/wiki/Code_128) विनिर्देशन।

```csharp
public enum Code128EncodeMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Auto | `0` | कोडटेक्स्ट को क्लासिक ISO 15417 मोड में एन्कोड करें। यह मोड सभी सामान्य मामलों में उपयोग किया जाना चाहिए। |
| CodeA | `1` | कोडटेक्स्ट को केवल 128A कोडसेट में एन्कोड करें। |
| CodeB | `2` | कोडटेक्स्ट को केवल 128B कोडसेट में एन्कोड करें। |
| CodeC | `4` | कोडटेक्स्ट को केवल 128C कोडसेट में एन्कोड करें। |
| CodeAB | `3` | कोडटेक्स्ट को केवल 128A और 128B कोडसेट्स में एन्कोड करें। |
| CodeAC | `5` | कोडटेक्स्ट को केवल 128A और 128C कोडसेट्स में एन्कोड करें। |
| CodeBC | `6` | कोडटेक्स्ट को केवल 128B और 128C कोडसेट्स में एन्कोड करें। |

## उदाहरण

यह कोड विभिन्न एन्कोडिंग्स के साथ कोड 128 उत्पन्न करने का प्रदर्शन करता है।

```csharp
[C#]
//ISO 15417 एन्कोडिंग के साथ कोड 128 उत्पन्न करें।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//केवल कोडसेट A एन्कोडिंग के साथ कोड 128 उत्पन्न करें।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


