---
title: "BaseGenerationParameters.RotationAngle"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BaseGenerationParameters property. BarCode छवि का घूर्णन कोण डिग्री में मापा जाता है, उदाहरण के लिए RotationAngle 0 या RotationAngle 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है तो स्कैनर के लिए छवि पढ़ना कठिन हो सकता है। डिफ़ॉल्ट मान 0"
type: docs
weight: 110
url: /hi/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

BarCode छवि का घूर्णन कोण, डिग्री में मापा जाता है, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घुमाव नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0।

```csharp
public float RotationAngle { get; set; }
```

## उदाहरण

यह उदाहरण दिखाता है कि BarCode छवि कैसे बनाएं और सहेजें।

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### और देखें

* class [BaseGenerationParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


