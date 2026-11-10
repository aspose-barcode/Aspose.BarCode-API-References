---
title: "क्लास License"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.License क्लास। घटक को लाइसेंस करने के लिए विधियाँ प्रदान करती है।"
type: docs
weight: 1760
url: /hi/net/aspose.barcode/license/
---
## License class

घटक को लाइसेंस करने के लिए विधियां प्रदान करता है।

```csharp
public class License
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [License](license/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense)(Stream) | लाइब्रेरी को लाइसेंस करता है। |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense_1)(string) | लाइब्रेरी को लाइसेंस करता है। |

## उदाहरण

इस उदाहरण में, घटक को शामिल करने वाले फ़ोल्डर में, कॉलिंग असेंबली को शामिल करने वाले फ़ोल्डर में, एंट्री असेंबली के फ़ोल्डर में, और फिर कॉलिंग असेंबली के एम्बेडेड संसाधनों में, MyLicense.lic नामक लाइसेंस फ़ाइल को खोजने का प्रयास किया जाएगा।

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### और देखें

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


