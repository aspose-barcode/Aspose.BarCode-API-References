---
title: "License.SetLicense"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "License मेथड। लाइब्रेरी को लाइसेंस देता है"
type: docs
weight: 20
url: /hi/net/aspose.barcode/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

लाइब्रेरी को लाइसेंस करता है।

```csharp
public void SetLicense(string licenseName)
```

## टिप्पणियाँ

लाइसेंस को निम्नलिखित स्थानों में खोजने का प्रयास करता है:

1. स्पष्ट पथ।

2. वह फ़ोल्डर जिसमें Aspose घटक असेंबली शामिल है।

3. वह फ़ोल्डर जिसमें क्लाइंट की कॉलिंग असेंबली शामिल है।

4. वह फ़ोल्डर जिसमें एंट्री (स्टार्टअप) असेंबली शामिल है।

5. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. स्पष्ट पथ।

2. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।

## उदाहरण

इस उदाहरण में, घटक को शामिल करने वाले फ़ोल्डर में, कॉलिंग असेंबली को शामिल करने वाले फ़ोल्डर में, एंट्री असेंबली के फ़ोल्डर में, और फिर कॉलिंग असेंबली के एम्बेडेड संसाधनों में, MyLicense.lic नामक लाइसेंस फ़ाइल को खोजने का प्रयास किया जाएगा।

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

पूरा या छोटा फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है।

### और देखें

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)

---

## SetLicense(Stream) {#setlicense}

लाइब्रेरी को लाइसेंस करता है।

```csharp
public void SetLicense(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

## टिप्पणियाँ

स्ट्रीम से लाइसेंस लोड करने के लिए इस मेथड का उपयोग करें।

## उदाहरण

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### और देखें

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)


