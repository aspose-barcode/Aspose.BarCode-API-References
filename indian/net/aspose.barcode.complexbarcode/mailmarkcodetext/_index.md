---
title: "क्लास MailmarkCodetext"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.MailmarkCodetext क्लास। 4-स्टेट Royal Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 670
url: /hi/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

4-स्टेट Royal Mailmark कोड में एम्बेड किए गए टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | "0" - नल या परीक्षण "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रिमियम (RetailPublishing Mail) (भविष्य में संभावित उपयोग के लिए) "5" - स्थगित (रिटेल) "6" - एयर (रिटेल) (भविष्य में संभावित उपयोग के लिए) "7" - सर्फेस (रिटेल) (भविष्य में संभावित उपयोग के लिए) "8" - प्रिमियम (नेटवर्क एक्सेस) "9" - स्टैंडर्ड (नेटवर्क एक्सेस) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | PC और DP को PAF फ़ॉर्मेट का पालन करना चाहिए। नौ अक्षरों की स्ट्रिंग जो अंतरराष्ट्रीय "XY11 " को दर्शाती है (ध्यान दें कि 5 trailing spaces हैं) या अक्षरों का पैटर्न जो घरेलू सॉर्टिंग कोड को दर्शाता है। एक घरेलू सॉर्टिंग कोड में आउटवर्ड पोस्टकोड, इनवर्ड पोस्टकोड, और डिलीवरी पॉइंट सफ़िक्स शामिल होते हैं। |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | "0" – नल या परीक्षण "1" – लेटर "2" – बड़ा लेटर |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | अधिकतम मान 99999999 है। |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | बारकोड C के लिए अधिकतम मान 99 है और बारकोड L के लिए 999999 है। |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | वर्तमान में "1" – Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य में उपयोग के लिए आरक्षित हैं) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | बारकोड प्रकार को प्राप्त करता है। |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Mailmark डेटा से कोडटेक्स्ट बनाएं। |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | निर्मित कोडटेक्स्ट से Mailmark डेटा को प्रारंभ करता है। |

### और देखें

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


