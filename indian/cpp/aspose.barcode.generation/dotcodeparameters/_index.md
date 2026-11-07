---
title: "Aspose::BarCode::Generation::DotCodeParameters क्लास"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::DotCodeParameters क्लास। C++ में DotCode पैरामीटर।"
type: docs
weight: 2200
url: /hi/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


डॉटकोड पैरामीटर।

```cpp
class DotCodeParameters : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [get_Columns](./get_columns/)() const | कॉलम की संख्या की पहचान करता है। एक DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। कॉलम की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI एन्कोडिंग की पहचान करता है। जब DotCodeEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | DotCode एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है। |
| [get_Rows](./get_rows/)() const | पंक्तियों की संख्या की पहचान करता है। एक DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। पंक्तियों की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड का ID पहचानता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है। |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड की संख्या की पहचान करता है। डिफ़ॉल्ट मान -1 है। संख्या 1 से 35 के बीच होनी चाहिए। |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [set_Columns](./set_columns/)(int32_t) | कॉलम की संख्या की पहचान करता है। एक DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। कॉलम की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECI एन्कोडिंग की पहचान करता है। जब DotCodeEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | DotCode एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है। |
| [set_Rows](./set_rows/)(int32_t) | पंक्तियों की संख्या की पहचान करता है। एक DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। पंक्तियों की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड का ID पहचानता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है। |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड की संख्या की पहचान करता है। डिफ़ॉल्ट मान -1 है। संख्या 1 से 35 के बीच होनी चाहिए। |
| [ToString](./tostring/)() const override | इस [DotCodeParameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
