---
title: DataMatrixEncodeMode
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: DataMatrix एन्कोडर का एन्कोडिंग मोड डिफ़ॉल्ट रूप से Auto होता है
type: docs
weight: 83
url: /hi/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

DataMatrix एन्कोडर का एन्कोडिंग मोड, डिफ़ॉल्ट रूप से ऑटो।

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ANSIX12](#ANSIX12) | ANSI X12 एन्कोडिंग का उपयोग करता है। |
| [ASCII](#ASCII) | प्रति बाइट एक अल्फ़ान्यूमेरिक या दो संख्यात्मक अक्षर एन्कोड करता है |
| [AUTO](#AUTO) | Auto मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। |
| [BASE_256](#BASE-256) | 8 बिट मान एन्कोड करें |
| [BINARY](#BINARY) | Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। |
| [BYTES](#BYTES) | 8 बिट मान एन्कोड करें |
| [C40](#C40) | C40 एन्कोडिंग का उपयोग करता है। |
| [ECI](#ECI) | ECI मोड में, संपूर्ण संदेश को ECIEncoding द्वारा निर्दिष्ट एन्कोडिंग में पुनः एन्कोड किया जाता है, जिसमें एक ECI पहचानकर्ता सम्मिलित किया जाता है। |
| [EDIFACT](#EDIFACT) | EDIFACT एन्कोडिंग का उपयोग करता है। |
| [EXTENDED](#EXTENDED) | ExtendedCodetext मोड कोडटेक्स्ट में एन्कोडेशन योजनाओं और ECI एन्कोडिंग को मैन्युअल रूप से स्विच करने की अनुमति देता है। |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | Text एन्कोडिंग का उपयोग करता है। |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


ANSI X12 एन्कोडिंग का उपयोग करता है।

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


प्रति बाइट एक अल्फ़ान्यूमेरिक या दो संख्यात्मक अक्षर एन्कोड करता है

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


Auto मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यूनिकोड अक्षरों को ECIEncoding द्वारा निर्दिष्ट एन्कोडिंग में पुनः एन्कोड किया जाता है, जिसमें एक ECI पहचानकर्ता सम्मिलित किया जाता है। यदि कोई अक्षर मिलता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है।

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


8 बिट मान एन्कोड करें

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यदि कोई यूनिकोड अक्षर मिलता है, तो एक अपवाद फेंका जाता है।

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


8 बिट मान एन्कोड करें

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


C40 एन्कोडिंग का उपयोग करता है। अपर केस अल्फ़ान्यूमेरिक, लोअर केस और विशेष अक्षरों को एन्कोड करता है।

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


ECI मोड में, संपूर्ण संदेश को ECIEncoding द्वारा निर्दिष्ट एन्कोडिंग में पुनः एन्कोड किया जाता है, जिसमें एक ECI पहचानकर्ता सम्मिलित किया जाता है। यदि कोई अक्षर मिलता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है। कृपया ध्यान दें कि कुछ पुराने (2006 से पहले) स्कैनर इस मोड को समर्थन नहीं दे सकते हैं।

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


EDIFACT एन्कोडिंग का उपयोग करता है। प्रत्येक अक्षर के लिए छह बिट्स का उपयोग करता है, अंकों, अपर केस अक्षरों और कई विराम चिह्नों को एन्कोड करता है, लेकिन लोअर केस अक्षरों का समर्थन नहीं करता।

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


ExtendedCodetext मोड कोडटेक्स्ट में एन्कोडेशन योजनाओं और ECI एन्कोडिंग को मैन्युअल रूप से स्विच करने की अनुमति देता है। विस्तारित कोडटेक्स्ट जनरेशन के लिए DataMatrixExtCodetextBuilder का उपयोग करना बेहतर है। दृश्यमान टेक्स्ट सेट करने के लिए Display2DText प्रॉपर्टी का उपयोग करके प्रबंधन अक्षरों को हटाया जाता है। ECI पहचानकर्ता को एकल स्लैश और छह अंकों के पहचानकर्ता "\\000026" - UTF8 ECI पहचानकर्ता के रूप में सेट किया जाता है। ECI पहचानकर्ता के बाद सभी यूनिकोड अक्षर स्वचालित रूप से सही कैरेक्टर कोडसेट में एन्कोड हो जाते हैं। एन्कोडेशन योजनाएँ अगले स्वरूप में सेट की जाती हैं : "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text"। अनुमत एन्कोडेशन योजनाएँ हैं: EDIFACT, ANSIX12, ASCII, C40, Text, Auto। सभी बैकस्लैश (\\) को टेक्स्ट में दोहरा होना चाहिए।

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


ExtendedCodetext मोड कोडटेक्स्ट में एन्कोडेशन योजनाओं और ECI एन्कोडिंग को मैन्युअल रूप से स्विच करने की अनुमति देता है।

विस्तारित कोडटेक्स्ट जनरेशन के लिए DataMatrixExtCodetextBuilder का उपयोग करना बेहतर है।

दृश्यमान टेक्स्ट सेट करने के लिए Display2DText प्रॉपर्टी का उपयोग करके प्रबंधन अक्षरों को हटाया जाता है।

ECI पहचानकर्ता को एकल स्लैश और छह अंकों के पहचानकर्ता "\\000026" - UTF8 ECI पहचानकर्ता के रूप में सेट किया जाता है।

ECI पहचानकर्ता के बाद सभी यूनिकोड अक्षर स्वचालित रूप से सही कैरेक्टर कोडसेट में एन्कोड हो जाते हैं।

एन्कोडेशन योजनाएँ अगले स्वरूप में सेट की जाती हैं : "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text"।

अनुमत एन्कोडेशन योजनाएँ हैं: EDIFACT, ANSIX12, ASCII, C40, Text, Auto।

सभी बैकस्लैश (\\) को टेक्स्ट में दोहरा होना चाहिए।

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Text एन्कोडिंग का उपयोग करता है। लोअर केस अल्फ़ान्यूमेरिक, अपर केस और विशेष अक्षरों को एन्कोड करता है।

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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
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

