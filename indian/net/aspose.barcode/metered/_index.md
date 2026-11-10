---
title: "क्लास Metered"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Metered क्लास। मीटर की सेट करने के लिए मेथड प्रदान करता है।"
type: docs
weight: 1770
url: /hi/net/aspose.barcode/metered/
---
## Metered class

मीटर कुंजी सेट करने के लिए विधियां प्रदान करता है।

```csharp
public class Metered
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [Metered](metered/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetProductName](../../aspose.barcode/metered/getproductname/)() | लाइसेंस प्राप्त उत्पाद का नाम प्राप्त करता है |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey/)(string, string) | मीटर सार्वजनिक और निजी कुंजी सेट करता है। यदि आप मीटर लाइसेंस खरीदते हैं, तो एप्लिकेशन शुरू करने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त है। हालांकि, यदि हमेशा उपभोग डेटा अपलोड करने में विफल रहता है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को मूल्यांकन स्थिति में सेट कर दिया जाएगा; ऐसे मामले से बचने के लिए आपको नियमित रूप से लाइसेंस स्थिति जांचनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस API को फिर से कॉल करें। |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit/)() | उपभोग क्रेडिट प्राप्त करता है |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity/)() | उपभोग फ़ाइल आकार प्राप्त करता है |
| static [IsMeteredLicensed](../../aspose.barcode/metered/ismeteredlicensed/)() | जाँचें कि मीटरयुक्त लाइसेंस प्राप्त है या नहीं |

## उदाहरण

इस उदाहरण में, मीटरयुक्त सार्वजनिक और निजी कुंजी सेट करने का प्रयास किया जाएगा

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### और देखें

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


