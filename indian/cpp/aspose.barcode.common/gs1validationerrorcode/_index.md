---
title: "enum"
linktitle: "GS1ValidationErrorCode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " enum. C++ में एक GS1 तत्व स्ट्रिंग, डिजिटल लिंक URI या मान सत्यापन त्रुटि की पहचान करता है।"
type: docs
weight: 600
url: /hi/cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


एक GS1 तत्व स्ट्रिंग, डिजिटल लिंक URI या मान वैलिडेशन त्रुटि की पहचान करता है।

```cpp
enum class GS1ValidationErrorCode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| EmptyElementString | 0 | प्रदान किया गया GS1 तत्व स्ट्रिंग खाली है। |
| MissingOpeningParenthesis | 1 | एक खुली कोष्ठक जो एक Application Identifier की शुरुआत करनी चाहिए, गायब है। |
| MissingClosingParenthesis | 2 | एक Application Identifier में बंद कोष्ठक नहीं है। |
| InvalidApplicationIdentifier | 3 | एक Application Identifier में दो से चार ASCII अंक नहीं होते हैं। |
| UnknownApplicationIdentifier | 4 | प्रदान किया गया Application Identifier समर्थित GS1 सिंटैक्स शब्दकोश द्वारा परिभाषित नहीं है। |
| MissingValue | 5 | एक Application Identifier मान के बिना मौजूद है। |
| InvalidEscapeSequence | 6 | एक मान में असमर्थित एस्केप अनुक्रम है। केवल ( समर्थित है। |
| ValueTooShort | 7 | एक मान अपने Application Identifier के लिए परिभाषित न्यूनतम लंबाई से छोटा है। |
| ValueTooLong | 8 | एक मान उसके एप्लिकेशन पहचानकर्ता के लिए परिभाषित अधिकतम लंबाई से अधिक लंबा है। |
| InvalidCharacter | 9 | एक मान में ऐसा अक्षर है जो उसके घटक के लिए अनुमत वर्ण सेट के बाहर है। |
| InvalidChecksum | 10 | एक संख्यात्मक या वर्णात्मक चेकसम अमान्य है। |
| InvalidDate | 11 | एक तिथि घटक उसके एप्लिकेशन पहचानकर्ता के लिए परिभाषित नियमों के तहत एक सार्थक तिथि नहीं है। |
| InvalidTime | 12 | एक समय घटक उसकी अनुमत सीमा के बाहर है या उसकी संरचना अमान्य है। |
| InvalidCodeListValue | 13 | एक घटक मान उसकी अनुमत बंद कोड सूची में उपस्थित नहीं है। |
| InvalidComponentLength | 14 | एक घटक उसकी घटक-विशिष्ट लंबाई संरचना को पूरा नहीं करता है। |
| TruncatedComponent | 15 | एक निश्चित-लंबाई वाला घटक सभी आवश्यक अक्षरों के उपस्थित होने से पहले समाप्त हो जाता है। |
| UnexpectedData | 16 | एप्लिकेशन पहचानकर्ता के लिए परिभाषित सभी घटकों को उपभोग करने के बाद डेटा शेष रहता है। |
| InvalidValue | 17 | एक घटक ऐसी सामग्री नियम का उल्लंघन करता है जिसके पास कोई अधिक विशिष्ट सत्यापन त्रुटि कोड नहीं है। |
| GcpPrefixTooShort | 18 | एक घटक बहुत छोटा है ताकि वह न्यूनतम चार-अंकीय संरचनात्मक GS1 कंपनी प्रीफ़िक्स शामिल न कर सके। |
| InvalidGcpPrefix | 19 | संरचनात्मक GS1 कंपनी प्रीफ़िक्स में ASCII अंक के अलावा कोई अन्य अक्षर है। |
| InvalidDigitalLinkUri | 20 | प्रदान किया गया मान एक सही ढंग से निर्मित पूर्ण GS1 डिजिटल लिंक URI नहीं है। |
| UnsupportedDigitalLinkScheme | 21 | एक GS1 डिजिटल लिंक URI HTTP या HTTPS के अलावा किसी अन्य योजना का उपयोग करता है। |
| MissingDigitalLinkPrimaryKey | 22 | एक GS1 डिजिटल लिंक URI पथ में समर्थित प्राथमिक कुंजी नहीं है। |
| InvalidDigitalLinkPath | 23 | एक GS1 डिजिटल लिंक URI पथ वैध AI और मान जोड़े से बना नहीं है। |
| InvalidDigitalLinkQualifier | 24 | एक पथ एप्लिकेशन आइडेंटिफ़ायर उस स्थिति में अनुमत क्वालिफ़ायर नहीं है। |
| InvalidDigitalLinkQueryParameter | 25 | एक GS1 Digital Link क्वेरी पैरामीटर विकृत है। |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | एक Application Identifier को GS1 Digital Link डेटा एट्रिब्यूट के रूप में अनुमति नहीं है। |
| InvalidPercentEncoding | 27 | एक GS1 Digital Link URI घटक में विकृत प्रतिशत एन्कोडिंग है। |
| MultipleDigitalLinkPrimaryKeys | 28 | एक से अधिक तत्व को GS1 Digital Link प्राथमिक कुंजी के रूप में चुना जा सकता है। |
| UnsupportedElementCombination | 29 | प्रदान किया गया GS1 तत्वों का संयोजन चयनित सिम्बोलॉजी या एन्कोडिंग मोड द्वारा समर्थित नहीं है। |

## और देखें

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
