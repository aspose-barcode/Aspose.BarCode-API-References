---
title: "क्लास Mailmark2DCodetext"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.Mailmark2DCodetext क्लास। Royal Mail 2D Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 650
url: /hi/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Royal Mail 2D Mailmark कोड में एम्बेड किए गए टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | आइटम की क्लास की पहचान करता है। |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.C40। |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | 2D Mailmark प्रकार Data Matrix बारकोड का आकार निर्धारित करता है। |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | डिलीवरी पते के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। क्षेत्र (1 या 2 अक्षर) जिला (1 या 2 अक्षर) सेक्टर (1 अक्षर) यूनिट (2 अक्षर) DPS (2 अक्षर)। पोस्टकोड और DPS को वैध PAF® फ़ॉर्मेट के अनुरूप होना चाहिए। |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | प्रत्येक उत्पाद प्रकार के लिए Royal Mail Mailmark बारकोड पेलोड की पहचान करता है। |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक Mailmark बारकोड को कम से कम 90 दिनों तक अद्वितीय रूप से पहचाने जाने के लिए एक ID ले जाना आवश्यक है। अधिकतम मान: 99999999। |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | Return to Sender पोस्ट कोड को शामिल करता है लेकिन DPS नहीं। PC (बिना DPS के) को PAF® फ़ॉर्मेट के अनुरूप होना चाहिए। |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया गया है। |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999। |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | UPU देश ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर। |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | प्रत्येक Information Type ID के लिए प्रासंगिक बारकोड संस्करण की पहचान करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | बारकोड प्रकार को प्राप्त करता है। |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | Mailmark डेटा से कोडटेक्स्ट बनाएं। |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | निर्मित कोडटेक्स्ट से Mailmark डेटा को प्रारंभ करता है। |

### और देखें

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


