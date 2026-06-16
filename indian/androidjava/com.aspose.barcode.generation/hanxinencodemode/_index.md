---
title: HanXinEncodeMode
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Han Xin कोड एन्कोडिंग मोड।
type: docs
weight: 89
url: /hi/androidjava/com.aspose.barcode.generation/hanxinencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinEncodeMode extends Enum<HanXinEncodeMode>
```

Han Xin Code एन्कोडिंग मोड। अनुशंसा की जाती है कि ASCII/चीनी अक्षरों के साथ Auto या Unicode अक्षरों के लिए Unicode का उपयोग किया जाए।

--------------------

> ```
> // Auto mode
>   String codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.save("test.bmp");
> 
> 
>  // Binary mode
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN)
>  generator.setCodeText(encodedArr);
>  generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.BINARY);
>  generator.save("test.bmp");
> 
>   // ECI mode
>   String codetext = "\u0391\u0392\u0393\u0394\u0395";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.ECI);
>   generator.getParameters().getBarcode().getHanXin().setHanXinECIEncoding(ECIEncodings.ISO_8859_7);
>   generator.save("test.bmp");
> 
>   // URI mode
>   String codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.URI);
>   generator.save("test.bmp");
> 
> 
>   // Extended mode
>   String str = "\\gb180302b:\u6f04\\gb180304b:\u3401\\region1:\u5168\\region2:\u8785\\numeric:123\\text:qwe\\\\unicode:\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l" +
>       "\\000009:\u0391\u0392\u0393\u0394\u0395\\auto:abc\\binary:abc\\\\uri:backslashes_should_be_doubled\\\\000555:test";
> 
>   String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test";
> 
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HanXin, str);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>   generator.save("test.bmp");
> 
>   // Using HanXinExtCodetextBuilder for Extended mode (same codetext as in previous example)
>   //create codetext
>   HanXinExtCodetextBuilder codeTextBuilder = new HanXinExtCodetextBuilder();
>   codeTextBuilder.addGB18030TwoByte("\u6f04");
>   codeTextBuilder.addGB18030FourByte("\u3401");
>   codeTextBuilder.addCommonChineseRegionOne("\u5168");
>   codeTextBuilder.addCommonChineseRegionTwo("\u8785");
>   codeTextBuilder.addNumeric("123");
>   codeTextBuilder.addText("qwe");
>   codeTextBuilder.addUnicode("\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l");
>   codeTextBuilder.addECI("\u0391\u0392\u0393\u0394\u0395", 9);
>   codeTextBuilder.addAuto("abc");
>   codeTextBuilder.addBinary("abc");
>   codeTextBuilder.addURI("backslashes_should_be_doubled\\000555:test");
> 
>   String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test";
> 
>   //generate codetext
>   String str = codeTextBuilder.getExtendedCodetext();
> 
>   //generate
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HanXin, str);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>   generator.save("test.bmp");
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AUTO](#AUTO) | Auto मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। |
| [BINARY](#BINARY) | Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। |
| [ECI](#ECI) | ECI मोड में, संपूर्ण संदेश को ECIEncoding द्वारा निर्दिष्ट एन्कोडिंग में पुनः एन्कोड किया जाता है, जिसमें एक ECI पहचानकर्ता सम्मिलित किया जाता है। |
| [EXTENDED](#EXTENDED) | विस्तारित मोड आंतरिक मोडों के संयोजन की अनुमति देता है: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte। |
| [UNICODE](#UNICODE) | Unicode मोड Han Xin Code में UTF8 एन्कोडिंग/कैरेक्टरसेट के संदर्भ में किसी भी टेक्स्ट डेटा को प्रदर्शित करने का तरीका बनाता है। |
| [URI](#URI) | URI मोड दर्शाता है कि Han Xin Code में प्रस्तुत डेटा RFC 3986 के अनुसार Uniform Resource Identifier (URI) संदर्भ है। |
## Methods

| Method | विवरण |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final HanXinEncodeMode AUTO
```


Auto मोड में, CodeText को अधिकतम डेटा संपीड़न के साथ एन्कोड किया जाता है। Unicode अक्षरों को HanXin बारकोड विनिर्देश के अनुसार GB18030 एन्कोडिंग का उपयोग करके एन्कोड किया जाता है।

### BINARY {#BINARY}
```
public static final HanXinEncodeMode BINARY
```


Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यदि कोई यूनिकोड अक्षर मिलता है, तो एक अपवाद फेंका जाता है।

### ECI {#ECI}
```
public static final HanXinEncodeMode ECI
```


ECI मोड में, संपूर्ण संदेश को ECIEncoding द्वारा निर्दिष्ट एन्कोडिंग में पुनः एन्कोड किया जाता है, जिसमें एक ECI पहचानकर्ता सम्मिलित किया जाता है। यदि कोई अक्षर मिलता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है। कृपया ध्यान दें कि कुछ पुराने (2006 से पहले) स्कैनर इस मोड को समर्थन नहीं दे सकते हैं।

### EXTENDED {#EXTENDED}
```
public static final HanXinEncodeMode EXTENDED
```


विस्तारित मोड आंतरिक मोडों के संयोजन की अनुमति देता है: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte। Codetext को मैन्युअली प्रीफ़िक्स और डबल बैकस्लैश के साथ बनाया जा सकता है, उदाहरण के लिए: @\"\\\\auto:abc\\\\000009:\\u0391\\\\u0392\\\\u0393\\\\u0394\\\\u0395\\\\auto:ab\\\\\\\\c\" या HanXinExtCodetextBuilder का उपयोग करके। यदि codetext में एक ECI फ्रैगमेंट है, तो ECI फ्रैगमेंट के बाद केवल निम्नलिखित मोड कोडटेक्स्ट में हो सकते हैं: Auto, Binary, Text, Numeric, URI, ECI।

### UNICODE {#UNICODE}
```
public static final HanXinEncodeMode UNICODE
```


Unicode मोड Han Xin Code में UTF8 एन्कोडिंग/कैरेक्टरसेट के संदर्भ में किसी भी टेक्स्ट डेटा को प्रदर्शित करने का तरीका बनाता है।

### URI {#URI}
```
public static final HanXinEncodeMode URI
```


URI मोड दर्शाता है कि Han Xin Code में प्रस्तुत डेटा RFC 3986 के अनुसार Uniform Resource Identifier (URI) संदर्भ है।

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static HanXinEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### values() {#values--}
```
public static HanXinEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinEncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

