---
title: "QREncodeMode"
second_title: "Aspose.Sildes for Python via .NET API संदर्भ"
description: 
type: docs
url: /hi/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

QR बारकोड के लिए एन्कोडिंग मोड।

## Members
| सदस्य नाम | विवरण |
| :- | :- |
| AUTO | ऑटो मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। <br/>            यदि संभव हो तो Unicode अक्षरों को कंजी मोड में एन्कोड किया जाता है, या उन्हें ECIEncoding द्वारा निर्दिष्ट एन्कोडिंग में पुनः एन्कोड किया जाता है और ECI पहचानकर्ता सम्मिलित किया जाता है।<br/>            यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है। |
| EXTENDED |  |
| BINARY | बाइनरी मोड में, CodeText को अधिकतम डेटा संपीड़न के साथ एन्कोड किया जाता है। <br/>            यदि कोई Unicode अक्षर पाया जाता है, तो एक अपवाद फेंका जाता है। |
| ECI | ECI मोड में, संपूर्ण संदेश को ECIEncoding द्वारा निर्दिष्ट एन्कोडिंग में पुनः एन्कोड किया जाता है और ECI पहचानकर्ता सम्मिलित किया जाता है।<br/>            यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है।<br/>            कृपया ध्यान दें कि कुछ पुराने (2006 से पूर्व) स्कैनर इस मोड को समर्थन नहीं दे सकते हैं।<br/>            यह मोड MicroQR बारकोड द्वारा समर्थित नहीं है। |

### संबंधित देखें

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

