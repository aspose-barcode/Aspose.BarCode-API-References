---
title: "विधि"
linktitle: "set_RotationAngle"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। BarCode छवि का घूर्णन कोण, डिग्री में मापा जाता है, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0 C++ में।"
type: docs
weight: 800
url: /hi/cpp/aspose.barcode.generation/basegenerationparameters/set_rotationangle/
---
## BaseGenerationParameters::set_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
void Aspose::BarCode::Generation::BaseGenerationParameters::set_RotationAngle(float value)
```

## टिप्पणियाँ


यह नमूना दिखाता है कि कैसे एक [BarCode](../../../aspose.barcode/) छवि बनाएं और सहेजें।
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## और देखें

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
