---
title: "QrParameters"
second_title: "Aspose.BarCode Python के लिए .NET API रेफ़रेंस"
description: 
type: docs
url: /hi/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

QR पैरामीटर।

QrParameters प्रकार निम्नलिखित सदस्यों को उजागर करता है:
## गुण
| नाम | विवरण |
| :- | :- |
| eci_encoding | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को विवरण बताने के लिए उपयोग किया जाता है<br/>            प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में।<br/>            वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग को शामिल करता है।<br/>            MicroQR द्वारा समर्थित नहीं है। |
| encode_mode | BarCode की एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार।<br/>            डिफ़ॉल्ट मान: QREncodeMode.Auto. |
| error_level | QR, MicroQR और RectMicroQR बारकोड के लिए रीड़-सोलोमन त्रुटि सुधार का स्तर।<br/>             कम से उच्च: LevelL, LevelM, LevelQ, LevelH। देखें QERrrorLevel. |
| version | QR कोड का संस्करण। Version1 से लेकर Version40 तक।<br/>            डिफ़ॉल्ट मान है QRVersion.Auto. |
| micro_qr_version | MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक।<br/>            डिफ़ॉल्ट मान है MicroQRVersion.Auto. |
| rect_micro_qr_version | RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक।<br/>            डिफ़ॉल्ट मान है RectMicroQRVersion.Auto. |
| aspect_ratio | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| structured_append | QR संरचित जोड़ पैरामीटर।<br/>            संरचित जोड़ मोड MicroQR और RectMicroQR बारकोड द्वारा समर्थित नहीं है। |
| encode_gs1_separator_in_byte_mode |  |

### संबंधित देखें

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

