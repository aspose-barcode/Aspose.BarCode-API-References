---
title: "क्लास Address"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.Address क्लास। लेनदार या ऋणकर्ता का पता।"
type: docs
weight: 480
url: /hi/net/aspose.barcode.complexbarcode/address/
---
## Address class

ऋणदाता या ऋणग्राही का पता।

आप या तो सड़क, घर नंबर, पोस्टल कोड और शहर (प्रकार संरचित पता) या पता पंक्ति 1 और 2 (प्रकार संयुक्त पता तत्व) सेट कर सकते हैं। इन में से किसी भी फ़ील्ड को सेट करने पर प्रकार स्वचालित रूप से निर्धारित हो जाता है। फ़ील्ड सेट करने से पहले पता प्रकार अनिर्धारित रहता है। यदि दोनों प्रकार के फ़ील्ड सेट किए जाते हैं, तो पता प्रकार संघर्षपूर्ण हो जाता है। नाम और देश कोड हमेशा सेट होना चाहिए जब तक सभी फ़ील्ड खाली न हों।

```csharp
public sealed class Address : IEquatable<Address>
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [Address](address/)() | Address का इंस्टेंस बनाता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | पता पंक्ति 1 को प्राप्त करता है या सेट करता है। |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | पता पंक्ति 2 को प्राप्त करता है या सेट करता है। |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | दो-अक्षर ISO देश कोड को प्राप्त करता है या सेट करता है। |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | घर नंबर को प्राप्त करता है या सेट करता है। |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है, चाहे वह प्राकृतिक व्यक्ति का पहला और अंतिम नाम हो या कानूनी व्यक्ति की कंपनी का नाम। |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | पोस्टल कोड को प्राप्त करता है या सेट करता है। |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | सड़क को प्राप्त करता है या सेट करता है। |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | शहर या कस्बे को प्राप्त करता है या सेट करता है। |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | पता प्रकार को प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | सभी फ़ील्ड साफ़ करता है और प्रकार को अनिर्धारित सेट करता है। |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | निर्धारित करता है कि निर्दिष्ट पता वर्तमान पते के बराबर है या नहीं। |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड प्राप्त करता है। |

### और देखें

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


