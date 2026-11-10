---
title: "Enum GS1ValidationErrorCode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode enum. एक GS1 तत्व स्ट्रिंग Digital Link URI या मान सत्यापन त्रुटि की पहचान करता है"
type: docs
weight: 430
url: /hi/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

एक GS1 तत्व स्ट्रिंग, डिजिटल लिंक URI या मान सत्यापन त्रुटि की पहचान करता है।

```csharp
public enum GS1ValidationErrorCode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| EmptyElementString | `0` | प्रदान किया गया GS1 तत्व स्ट्रिंग खाली है। |
| MissingOpeningParenthesis | `1` | एक खुला कोष्ठक जो Application Identifier की शुरुआत करना चाहिए था, गायब है। |
| MissingClosingParenthesis | `2` | एक Application Identifier में बंद कोष्ठक नहीं है। |
| InvalidApplicationIdentifier | `3` | एक Application Identifier में दो से चार ASCII अंक नहीं हैं। |
| UnknownApplicationIdentifier | `4` | प्रदान किया गया Application Identifier समर्थित GS1 सिंटैक्स डिक्शनरी द्वारा परिभाषित नहीं है। |
| MissingValue | `5` | एक Application Identifier मान के बिना मौजूद है। |
| InvalidEscapeSequence | `6` | एक मान में असमर्थित एस्केप अनुक्रम है। केवल \\( समर्थित है। |
| ValueTooShort | `7` | एक मान उसके Application Identifier के लिए परिभाषित न्यूनतम लंबाई से छोटा है। |
| ValueTooLong | `8` | एक मान उसके Application Identifier के लिए परिभाषित अधिकतम लंबाई से लंबा है। |
| InvalidCharacter | `9` | एक मान में उसके घटक के लिए अनुमत अक्षर सेट के बाहर का अक्षर है। |
| InvalidChecksum | `10` | एक संख्यात्मक या वर्णात्मक चेकसम अमान्य है। |
| InvalidDate | `11` | एक तिथि घटक उसके Application Identifier के लिए परिभाषित नियमों के तहत अर्थपूर्ण तिथि नहीं है। |
| InvalidTime | `12` | एक समय घटक उसकी अनुमत सीमा से बाहर है या उसकी संरचना अमान्य है। |
| InvalidCodeListValue | `13` | एक घटक मान उसकी अनुमत बंद कोड सूची में मौजूद नहीं है। |
| InvalidComponentLength | `14` | एक घटक उसकी घटक-विशिष्ट लंबाई संरचना को पूरा नहीं करता है। |
| TruncatedComponent | `15` | एक निश्चित-लंबाई वाला घटक सभी आवश्यक अक्षरों के उपस्थित होने से पहले समाप्त हो जाता है। |
| UnexpectedData | `16` | Application Identifier के लिए परिभाषित सभी घटकों को उपभोग करने के बाद डेटा शेष रहता है। |
| InvalidValue | `17` | एक घटक ऐसी सामग्री नियम का उल्लंघन करता है जिसका कोई अधिक विशिष्ट सत्यापन त्रुटि कोड नहीं है। |
| GcpPrefixTooShort | `18` | एक घटक न्यूनतम चार-अंकीय संरचनात्मक GS1 कंपनी प्रीफ़िक्स रखने के लिए बहुत छोटा है। |
| InvalidGcpPrefix | `19` | संरचनात्मक GS1 कंपनी प्रीफ़िक्स में ASCII अंक के अलावा कोई अन्य अक्षर है। |
| InvalidDigitalLinkUri | `20` | प्रदान किया गया मान एक सही ढंग से निर्मित पूर्ण GS1 डिजिटल लिंक URI नहीं है। |
| UnsupportedDigitalLinkScheme | `21` | एक GS1 डिजिटल लिंक URI HTTP या HTTPS के अलावा किसी अन्य स्कीम का उपयोग करता है। |
| MissingDigitalLinkPrimaryKey | `22` | एक GS1 डिजिटल लिंक URI पथ में समर्थित प्राथमिक कुंजी नहीं है। |
| InvalidDigitalLinkPath | `23` | एक GS1 डिजिटल लिंक URI पथ वैध AI और मान जोड़े से बना नहीं है। |
| InvalidDigitalLinkQualifier | `24` | उस स्थिति पर पथ एप्लिकेशन आइडेंटिफ़ायर एक अनुमति प्राप्त क्वालिफ़ायर नहीं है। |
| InvalidDigitalLinkQueryParameter | `25` | एक GS1 डिजिटल लिंक क्वेरी पैरामीटर गलत रूप से बना है। |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | एक एप्लिकेशन आइडेंटिफ़ायर को GS1 डिजिटल लिंक डेटा एट्रिब्यूट के रूप में अनुमति नहीं है। |
| InvalidPercentEncoding | `27` | एक GS1 डिजिटल लिंक URI घटक में गलत प्रतिशत एन्कोडिंग है। |
| MultipleDigitalLinkPrimaryKeys | `28` | एक से अधिक तत्व को GS1 डिजिटल लिंक प्राथमिक कुंजी के रूप में चुना जा सकता है। |
| UnsupportedElementCombination | `29` | प्रदान किया गया GS1 तत्वों का संयोजन चयनित सिम्बोलॉजी या एन्कोडिंग मोड द्वारा समर्थित नहीं है। |

### और देखें

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


