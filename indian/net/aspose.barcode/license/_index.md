---
title: License
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: घटक क लइसेंस देने के तरके प्रदन करत है
type: docs
weight: 1280
url: /hi/net/aspose.barcode/license/
---
## License class

घटक को लाइसेंस देने के तरीके प्रदान करता है।

```csharp
public class License
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [License](license/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense)(Stream) | लाइब्रेरी को लाइसेंस देता है। |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense_1)(string) | लाइब्रेरी को लाइसेंस देता है। |

### उदाहरण

इस उदाहरण में, MyLicense.lic नामक लाइसेंस फ़ाइल को उस फ़ोल्डर में खोजने का प्रयास किया जाएगा जिसमें घटक शामिल है, उस फ़ोल्डर में जिसमें कॉलिंग असेंबली, प्रविष्टि असेंबली के फ़ोल्डर में और फिर एम्बेडेड में है कॉलिंग असेंबली के संसाधन।

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### यह सभी देखें

* नाम स्थान [Aspose.BarCode](../../aspose.barcode/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
