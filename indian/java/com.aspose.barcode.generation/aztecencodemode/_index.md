---
title: "AztecEncodeMode"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "Aztec बारकोड के लिए एन्कोडिंग मोड।"
type: docs
weight: 71
url: /hi/java/com.aspose.barcode.generation/aztecencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AztecEncodeMode extends Enum<AztecEncodeMode>
```

Aztec बारकोड के लिए एन्कोडिंग मोड।

--------------------

> ```
> String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
>  generator.getParameters().getBarcode().getAztec().setECIEncoding(ECIEncodings.UTF_8);
>  generator.save("test.bmp");
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getAztec().setAztecEncodeMode(AztecEncodeMode.BINARY);
>  generator.save("test.bmp");
> 
>  //Extended mode
>  //create codetext
>  AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
>  generator.getParameters().getBarcode().getAztec().setAztecEncodeMode(AztecEncodeMode.EXTENDED);
>  generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>  generator.save("test.bmp");
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AUTO](#AUTO) | Auto मोड में, CodeText को अधिकतम डेटा संपीड़न के साथ एन्कोड किया जाता है। |
| [BINARY](#BINARY) | Binary मोड में, CodeText को अधिकतम डेटा संपीड़न के साथ एन्कोड किया जाता है। |
| [ECI](#ECI) | ECI मोड में, संपूर्ण संदेश को ECIEncoding द्वारा निर्दिष्ट एन्कोडिंग में पुनः एन्कोड किया जाता है और एक ECI पहचानकर्ता सम्मिलित किया जाता है। |
| [EXTENDED](#EXTENDED) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
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
public static final AztecEncodeMode AUTO
```


Auto मोड में, CodeText को अधिकतम डेटा संपीड़न के साथ एन्कोड किया जाता है। यूनिकोड अक्षरों को ECIEncoding द्वारा निर्दिष्ट एन्कोडिंग में पुनः एन्कोड किया जाता है और एक ECI पहचानकर्ता सम्मिलित किया जाता है। यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद उत्पन्न होता है।

### BINARY {#BINARY}
```
public static final AztecEncodeMode BINARY
```


Binary मोड में, CodeText को अधिकतम डेटा संपीड़न के साथ एन्कोड किया जाता है। यदि कोई यूनिकोड अक्षर पाया जाता है, तो एक अपवाद उत्पन्न होता है।

### ECI {#ECI}
```
public static final AztecEncodeMode ECI
```


ECI मोड में, संपूर्ण संदेश को ECIEncoding द्वारा निर्दिष्ट एन्कोडिंग में पुनः एन्कोड किया जाता है और एक ECI पहचानकर्ता सम्मिलित किया जाता है। यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद उत्पन्न होता है। कृपया ध्यान दें कि कुछ पुराने (2006 से पहले) स्कैनर इस मोड का समर्थन नहीं कर सकते हैं।

### EXTENDED {#EXTENDED}
```
public static final AztecEncodeMode EXTENDED
```


विस्तारित मोड जो कई ECI मोड्स का समर्थन करता है।

विस्तारित कोडटेक्स्ट जनरेशन के लिए AztecExtCodetextBuilder का उपयोग करना बेहतर है।

दिखाने योग्य टेक्स्ट को सेट करने के लिए Display2DText प्रॉपर्टी का उपयोग करें, जिससे प्रबंधन अक्षरों को हटाया जा सके।

ECI पहचानकर्ता को एकल स्लैश और छह अंकों के पहचानकर्ता "\\000026" के रूप में सेट किया जाता है - UTF8 ECI पहचानकर्ता।

ECI पहचानकर्ता के बाद सभी यूनिकोड अक्षर स्वचालित रूप से सही कैरेक्टर कोडसेट में एन्कोड हो जाते हैं।

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static AztecEncodeMode fromValue(int value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode
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
public static AztecEncodeMode valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode
### values() {#values--}
```
public static AztecEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.AztecEncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

