---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "Han Xin कोड के विस्तारित मोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर //Extended codetext mode //create codetext let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /hi/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Extended codetext generator for Han Xin Code for Extended Mode of HanXinEncodeMode //Extended codetext mode //create codetext let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //generate codetext let str = codeTextBuilder.getExtendedCodetext(); //generate let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addAuto(text)](#addauto) | ऑटो मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addBinary(text)](#addbinary) | बाइनरी मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | कॉमन चाइनीज़ रीजन वन मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | कॉमन चाइनीज़ रीजन टू मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addECI(text, encoding)](#addeci) | ECI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | GB18030 फ़ोर बाइट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | GB18030 टू बाइट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addGS1(text)](#addgs1) | GS1 मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addNumeric(text)](#addnumeric) | न्यूमेरिक मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addText(text)](#addtext) | टेक्स्ट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addUnicode(text)](#addunicode) | यूनिकोड मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addURI(text)](#adduri) | URI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [getExtendedCodetext()](#getextendedcodetext) | विस्तारित मोड कोडटेक्स्ट बिल्डर से कोडटेक्स्ट लौटाता है |

### addAuto(text) {#addauto}

ऑटो मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### addBinary(text) {#addbinary}

बाइनरी मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

कॉमन चाइनीज़ रीजन वन मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

कॉमन चाइनीज़ रीजन टू मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### addECI(text, encoding) {#addeci}

ECI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |
| एन्कोडिंग | ECI एन्कोडिंग संख्या प्रारूप में |

### addGB18030FourByte(text) {#addgb18030fourbyte}

GB18030 फ़ोर बाइट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### addGB18030TwoByte(text) {#addgb18030twobyte}

GB18030 टू बाइट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### addGS1(text) {#addgs1}

GS1 मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### addNumeric(text) {#addnumeric}

न्यूमेरिक मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### addText(text) {#addtext}

टेक्स्ट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### addUnicode(text) {#addunicode}

यूनिकोड मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### addURI(text) {#adduri}

URI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| पाठ | Codetext स्ट्रिंग |

### getExtendedCodetext() {#getextendedcodetext}

विस्तारित मोड कोडटेक्स्ट बिल्डर से कोडटेक्स्ट लौटाता है

**Returns:** Codetext in Extended mode
