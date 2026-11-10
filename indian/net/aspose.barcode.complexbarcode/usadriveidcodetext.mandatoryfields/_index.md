---
title: "क्लास USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields क्लास। कार्ड के अनिवार्य तत्व फ़ील्ड्स"
type: docs
weight: 820
url: /hi/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

कार्ड के अनिवार्य तत्व (फ़ील्ड्स)

```csharp
public class MandatoryFields
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, कार्डधारक पते का शहर भाग, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, संयुक्त राज्य और कनाडा में कार्डधारक पते का पोस्टल कोड भाग। यदि संयुक्त राज्य में पोस्टल कोड का अंतिम भाग ज्ञात नहीं है, तो शून्य का उपयोग करके अंतिम संख्या सेट को 9 अंकों तक भरा जाएगा, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, कार्डधारक पते का राज्य भाग, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, कार्डधारक पते का सड़क भाग, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, वह देश जहाँ DL/ID जारी किया गया है। U.S. = USA, Canada = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, जारी करने वाले प्राधिकरण द्वारा निर्धारित या गणना किया गया संख्या, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, दस्तावेज़ जारी होने की तिथि, U.S. के लिए MMDDCCYY, Canada के लिए CCYYMMDD, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, संख्या को उस ग्राहक को जारी किए गए विशिष्ट दस्तावेज़ को अन्य पिछले दस्तावेज़ों से अनन्य रूप से पहचानना चाहिए। यह संख्या दस्तावेज़ भेद, ऑडिट जानकारी संख्या, और/या इन्वेंटरी नियंत्रण के कई उद्देश्यों की सेवा कर सकती है, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, अधिकार क्षेत्र‑विशिष्ट समर्थन कोड, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, दस्तावेज़ समाप्ति तिथि, U.S. के लिए MMDDCCYY, Canada के लिए CCYYMMDD, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, कार्डधारक की आँखों का रंग। (ANSI D-20 कोड)। DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, कार्डधारक का पारिवारिक नाम, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, एक कोड जो दर्शाता है कि फ़ील्ड को छोटा किया गया है (T), छोटा नहीं किया गया है (N), या छोटा किया गया है या नहीं अज्ञात है (U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, कार्डधारक का पहला नाम, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, एक कोड जो दर्शाता है कि फ़ील्ड को छोटा किया गया है (T), छोटा नहीं किया गया है (N), या छोटा किया गया है या नहीं अज्ञात है (U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, कार्डधारक की ऊँचाई। इंच (in): इंच की संख्या के बाद " in" जैसे 6'1'' = "073 in" सेंटीमीटर(cm): सेंटीमीटर की संख्या के बाद " cm" जैसे 181 सेंटीमीटर = "181 cm", DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, दस्तावेज़ जारी होने की तिथि, U.S. के लिए MMDDCCYY, Canada के लिए CCYYMMDD, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, कार्डधारक का मध्य नाम(नाम)। कई मध्य नामों के मामले में उन्हें कॉमा "," से अलग किया जाएगा, DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, एक कोड जो दर्शाता है कि फ़ील्ड को छोटा किया गया है (T), छोटा नहीं किया गया है (N), या छोटा किया गया है या नहीं अज्ञात है (U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, अधिकार क्षेत्र‑विशिष्ट प्रतिबंध कोड, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, कार्डधारक का लिंग। 1 = पुरुष, 2 = महिला, 9 = निर्दिष्ट नहीं, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, अधिकार क्षेत्र‑विशिष्ट वाहन वर्ग / समूह कोड, DL, V6ANS |

### और देखें

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


