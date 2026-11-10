---
title: "क्लास SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData क्लास। HIBC LIC द्वितीयक और अतिरिक्त डेटा संग्रहीत करने के लिए क्लास।"
type: docs
weight: 770
url: /hi/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

HIBC LIC द्वितीय और अतिरिक्त डेटा को संग्रहीत करने के लिए क्लास।

```csharp
public class SecondaryAndAdditionalData
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | निर्माण तिथि की पहचान करता है। इस फ़ील्ड का उपयोग न करने के लिए निर्माण तिथि को DateTime.MinValue पर सेट किया जा सकता है। डिफ़ॉल्ट मान: DateTime.MinValue। |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो इसका उपयोग किया जाएगा। |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | समाप्ति तिथि के स्वरूप की पहचान करता है। |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | लॉट या बैच नंबर की पहचान करता है। लॉट/बैच नंबर अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए जिसकी अधिकतम लंबाई 18 प्रतीक है। |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | मात्रा की पहचान करता है, यह 0 से 500 के बीच पूर्णांक मान होना चाहिए। इस फ़ील्ड का उपयोग न करने के लिए मात्रा को -1 पर सेट किया जा सकता है। डिफ़ॉल्ट मान: -1 |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | सीरियल नंबर की पहचान करता है। सीरियल नंबर अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए जिसकी अधिकतम लंबाई 18 प्रतीक है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट `SecondaryAndAdditionalData` मान के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | HIBC LIC विनिर्देश के अनुसार स्ट्रिंग स्वरूप से द्वितीयक और अतिरिक्त पूरक डेटा को इंस्टैंशिएट करता है। |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | डेटा को HIBC LIC विनिर्देश के अनुसार स्ट्रिंग स्वरूप में परिवर्तित करता है। |

### और देखें

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


