---
title: "QrParametersUI.EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "QrParametersUI प्रॉपर्टी। प्राप्त करता है या सेट करता है एक मान जो दर्शाता है कि GS1 विशेष अक्षर QR और RectMicroQR बारकोड के लिए बाइट मोड में एन्कोड किए जाने चाहिए या नहीं"
type: docs
weight: 30
url: /hi/net/aspose.barcode.windows.forms/qrparametersui/encodegs1separatorinbytemode/
---
## QrParametersUI.EncodeGS1SeparatorInByteMode property

QR और RectMicroQR बारकोड के लिए बाइट मोड में GS1 विशेष अक्षरों को एन्कोड करने चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

यदि false है, तो QR विनिर्देश के अनुसार GS1 विभाजक अल्फ़ान्यूमेरिक मोड में '%' के रूप में एन्कोड हो सकते हैं।

यदि true है, तो GS1 समूह विभाजक बाइट मोड में 0x1D अक्षर के रूप में एन्कोड होते हैं, और '%' अक्षर भी डेटा के रूप में संरक्षित रखने के लिए बाइट मोड में एन्कोड होते हैं।

यह विकल्प डिकोडर जो बाइट-स्तर GS1 समूह विभाजकों की अपेक्षा करते हैं, के साथ संगतता को सुधार सकता है और '%' डेटा अक्षरों को GS1 विभाजक के रूप में व्याख्या होने से रोकता है।

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### और देखें

* class [QrParametersUI](../)
* namespace [Aspose.BarCode.Windows.Forms](../../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../../)


