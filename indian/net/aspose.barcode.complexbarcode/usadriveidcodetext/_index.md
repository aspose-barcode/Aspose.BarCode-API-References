---
title: "क्लास USADriveIdCodetext"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext क्लास। USA ड्राइविंग लाइसेंस PDF417 कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास"
type: docs
weight: 810
url: /hi/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

USA ड्राइविंग लाइसेंस PDF417 कोड में एम्बेड किए गए टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | AAMVA संस्करण संख्या 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | यह संख्या जारी करने वाले अधिकार को अद्वितीय रूप से पहचानती है और ISO जारी करने प्राधिकरण (AAMVA) से संपर्क करके प्राप्त की जा सकती है। पूर्ण 6-अंकीय IIN को एन्कोड किया जाना चाहिए। |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | अधिकार-विशिष्ट फ़ील्ड |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | अधिकार संस्करण संख्या 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | कार्ड के अनिवार्य तत्व (फ़ील्ड्स) |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | सबफ़ाइलों की संख्या 00-99 |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | कार्ड के वैकल्पिक तत्व (फ़ील्ड) |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | निम्नलिखित सबफ़ाइलों, प्रकारों, ऑफ़सेट और लंबाइयों के बारे में जानकारी शामिल है। महत्वपूर्ण: केवल प्रकार सेट करें, ऑफ़सेट और लंबाई स्वचालित रूप से सेट हो जाएगी। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | USA DL (Pdf417) का बारकोड प्रकार लौटाता है |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | USA DL डेटा से कोडटेक्स्ट बनाएं |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | कोडटेक्स्ट से USA DL ऑब्जेक्ट को प्रारंभ करें |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | XML में सहेजता है |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | कार्ड के अनिवार्य तत्व (फ़ील्ड्स) |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | कार्ड के वैकल्पिक तत्व (फ़ील्ड) |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | USA DL सबफ़ाइल गुणों का ऑफ़सेट और लंबाई स्वतः सेट हो जाता है। |

### और देखें

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


