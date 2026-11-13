---
title: "HanXinEncodeMode"
second_title: "Aspose.Sildes for Python via .NET API संदर्भ"
description: 
type: docs
url: /hi/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Han Xin Code एन्कोडिंग मोड। ASCII / चीनी अक्षरों के साथ Auto या Unicode अक्षरों के लिए Unicode का उपयोग करने की सलाह दी जाती है।

## Members
| सदस्य नाम | विवरण |
| :- | :- |
| AUTO | ऑटो मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। <br/>            यूनिकोड अक्षरों को HanXin बारकोड विनिर्देश के अनुसार GB18030 एन्कोडिंग का उपयोग करके एन्कोड किया जाता है। |
| BINARY | बाइनरी मोड में, CodeText को अधिकतम डेटा संपीड़न के साथ एन्कोड किया जाता है। <br/>            यदि कोई Unicode अक्षर पाया जाता है, तो एक अपवाद फेंका जाता है। |
| ECI | ECI मोड में, संपूर्ण संदेश को निर्दिष्ट ECIEncoding एन्कोडिंग में ECI पहचानकर्ता के सम्मिलन के साथ पुनः एन्कोड किया जाता है।<br/>            यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है।<br/>            कृपया ध्यान दें कि कुछ पुराने (2006 से पूर्व) स्कैनर इस मोड का समर्थन नहीं कर सकते हैं। |
| UNICODE | Unicode मोड UTF8 एन्कोडिंग/कैरेक्टर सेट को Han Xin कोड में किसी भी टेक्स्ट डेटा को दर्शाने का तरीका प्रदान करता है। |
| URI | URI मोड दर्शाता है कि Han Xin कोड में प्रस्तुत डेटा यूनिफ़ॉर्म रिसोर्स आइडेंटिफ़ायर (URI) है<br/>            RFC 3986 का संदर्भ। |
| EXTENDED | Extended मोड आंतरिक मोडों के संयोजन की अनुमति देता है: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            कोडटेक्स्ट को प्रीफ़िक्स और दोहरी बैकस्लैश के साथ मैन्युअल रूप से बनाया जा सकता है, उदाहरण के लिए: @\"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c\" या HanXinExtCodetextBuilder का उपयोग करके।<br/>            यदि कोडटेक्स्ट में ECI फ्रैगमेंट है, तो ECI फ्रैगमेंट के बाद केवल निम्नलिखित मोड कोडटेक्स्ट में हो सकते हैं:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### संबंधित देखें

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

