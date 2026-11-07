---
title: "विधि"
linktitle: "get_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में Aspose::BarCode::Generation::QrParameters क्लास की get_EncodeGS1SeparatorInByteMode मेथड का उपयोग कैसे करें।"
type: docs
weight: 1700
url: /hi/cpp/aspose.barcode.generation/qrparameters/get_encodegs1separatorinbytemode/
---
## QrParameters::get_EncodeGS1SeparatorInByteMode method




```cpp
bool Aspose::BarCode::Generation::QrParameters::get_EncodeGS1SeparatorInByteMode() const
```

## टिप्पणियाँ


एक मान प्राप्त करता है जो दर्शाता है कि QR और RectMicroQR बारकोड के लिए GS1 विशेष अक्षरों को बाइट मोड में एन्कोड किया जाना चाहिए या नहीं।

यदि false है, तो QR विनिर्देशन के अनुसार GS1 सेपरेटर अल्फ़ान्यूमेरिक मोड में '' के रूप में एन्कोड हो सकते हैं।

यदि true है, तो GS1 समूह सेपरेटर बाइट मोड में 0x1D अक्षर के रूप में एन्कोड होते हैं, और '' अक्षर भी डेटा के रूप में संरक्षित रखने के लिए बाइट मोड में एन्कोड होते हैं।

यह विकल्प डिकोडरों के साथ संगतता को सुधार सकता है जो बाइट-लेवल GS1 समूह सेपरेटर की अपेक्षा करते हैं और '' डेटा अक्षरों को GS1 सेपरेटर के रूप में व्याख्या होने से रोकता है।
## और देखें

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
