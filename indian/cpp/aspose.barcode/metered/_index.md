---
title: "Aspose::BarCode::Metered क्लास"
linktitle: "Metered"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Metered क्लास। C++ में मीटरड कुंजी सेट करने के लिए मेथड प्रदान करता है।"
type: docs
weight: 500
url: /hi/cpp/aspose.barcode/metered/
---
## Metered class


मीटर की कुंजी सेट करने के लिए मेथड प्रदान करता है।

```cpp
class Metered : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | उपभोग क्रेडिट प्राप्त करता है |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | उपभोग फ़ाइल आकार प्राप्त करता है |
| [GetProductName](./getproductname/)() | लाइसेंस प्राप्त उत्पाद का नाम प्राप्त करता है |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | जाँचें कि मीटरड लाइसेंस प्राप्त है या नहीं |
| [Metered](./metered/)() | इस क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | मीटरड सार्वजनिक और निजी कुंजी सेट करता है। यदि आप मीटरड लाइसेंस खरीदते हैं, तो एप्लिकेशन शुरू करने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त है। हालांकि, यदि उपभोग डेटा अपलोड करने में लगातार विफल रहता है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को मूल्यांकन स्थिति में सेट किया जाएगा; ऐसी स्थिति से बचने के लिए आपको नियमित रूप से लाइसेंस स्थिति की जाँच करनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस API को फिर से कॉल करें। |
## टिप्पणियाँ


इस उदाहरण में, मीटरड सार्वजनिक और निजी कुंजी सेट करने का प्रयास किया जाएगा

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> घटक जार फ़ाइल:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## और देखें

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
