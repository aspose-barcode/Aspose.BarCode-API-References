---
title: "GS1ValidationErrorCode"
second_title: "Aspose.Sildes for Python via .NET API संदर्भ"
description: 
type: docs
url: /hi/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

एक GS1 एलिमेंट स्ट्रिंग, डिजिटल लिंक URI या मान सत्यापन त्रुटि की पहचान करता है।

## Members
| सदस्य नाम | विवरण |
| :- | :- |
| EMPTY_ELEMENT_STRING | प्रदान किया गया GS1 element string खाली है। |
| MISSING_OPENING_PARENTHESIS | एक opening parenthesis जो Application Identifier की शुरुआत करनी चाहिए, गायब है। |
| MISSING_CLOSING_PARENTHESIS | एक Application Identifier के पास closing parenthesis नहीं है। |
| INVALID_APPLICATION_IDENTIFIER | एक Application Identifier में दो से चार ASCII अंक नहीं होते हैं। |
| UNKNOWN_APPLICATION_IDENTIFIER | प्रदान किया गया Application Identifier समर्थित GS1 Syntax Dictionary द्वारा परिभाषित नहीं है। |
| MISSING_VALUE | एक Application Identifier मान के बिना मौजूद है। |
| INVALID_ESCAPE_SEQUENCE | एक value में असमर्थित escape sequence है। केवल \\( समर्थित है। |
| VALUE_TOO_SHORT | एक value अपने Application Identifier के लिए परिभाषित न्यूनतम लंबाई से छोटी है। |
| VALUE_TOO_LONG | एक value अपने Application Identifier के लिए परिभाषित अधिकतम लंबाई से लंबी है। |
| INVALID_CHARACTER | एक value में ऐसा character है जो उसके component के लिए अनुमत character set से बाहर है। |
| INVALID_CHECKSUM | एक numeric या alphabetic checksum अमान्य है। |
| INVALID_DATE | एक date component अपने Application Identifier के लिए परिभाषित नियमों के तहत अर्थपूर्ण तिथि नहीं है। |
| INVALID_TIME | एक समय घटक अपनी अनुमत सीमा के बाहर है या उसकी संरचना अमान्य है। |
| INVALID_CODE_LIST_VALUE | एक घटक मान अपनी अनुमत बंद कोड सूची में मौजूद नहीं है। |
| INVALID_COMPONENT_LENGTH | एक घटक अपनी घटक-विशिष्ट लंबाई संरचना को पूरा नहीं करता है। |
| TRUNCATED_COMPONENT | एक निश्चित-लंबाई वाला घटक सभी आवश्यक अक्षरों के उपस्थित होने से पहले समाप्त हो जाता है। |
| UNEXPECTED_DATA | डेटा तब भी शेष रहता है जब एप्लिकेशन पहचानकर्ता के लिए परिभाषित सभी घटकों का उपयोग कर लिया गया हो। |
| INVALID_VALUE | एक घटक ऐसी सामग्री नियम का उल्लंघन करता है जिसके लिए कोई अधिक विशिष्ट सत्यापन त्रुटि कोड नहीं है। |
| GCP_PREFIX_TOO_SHORT | एक घटक बहुत छोटा है ताकि वह न्यूनतम चार-अंकीय संरचनात्मक GS1 कंपनी प्रीफ़िक्स को समाहित कर सके। |
| INVALID_GCP_PREFIX | संरचनात्मक GS1 कंपनी प्रीफ़िक्स में ASCII अंक के अलावा कोई अन्य अक्षर शामिल है। |
| INVALID_DIGITAL_LINK_URI | प्रदान किया गया मान एक सही ढंग से निर्मित पूर्ण GS1 डिजिटल लिंक URI नहीं है। |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | एक GS1 डिजिटल लिंक URI HTTP या HTTPS के अलावा किसी अन्य योजना का उपयोग करता है। |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | एक GS1 डिजिटल लिंक URI पथ में कोई समर्थित प्राथमिक कुंजी नहीं है। |
| INVALID_DIGITAL_LINK_PATH | एक GS1 डिजिटल लिंक URI पथ वैध AI और मान जोड़े से बना नहीं है। |
| INVALID_DIGITAL_LINK_QUALIFIER | एक पथ एप्लिकेशन पहचानकर्ता उस स्थिति में अनुमत क्वालिफायर नहीं है। |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | एक GS1 Digital Link क्वेरी पैरामीटर विकृत है। |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | एक Application Identifier को GS1 Digital Link डेटा एट्रिब्यूट के रूप में अनुमति नहीं है। |
| INVALID_PERCENT_ENCODING | एक GS1 Digital Link URI घटक में गलत प्रतिशत एन्कोडिंग है। |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | एक से अधिक तत्व को GS1 Digital Link प्राथमिक कुंजी के रूप में चुना जा सकता है। |
| UNSUPPORTED_ELEMENT_COMBINATION | प्रदान की गई GS1 तत्वों की संयोजन चयनित सिम्बोलॉजी या एन्कोडिंग मोड द्वारा समर्थित नहीं है। |

### संबंधित देखें

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

