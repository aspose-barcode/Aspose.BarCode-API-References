---
title: HanXinModes
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Han Xin कोड एन्कोडिंग मोड।
type: docs
weight: 91
url: /hi/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code एन्कोडिंग मोड। अनुशंसा की जाती है कि ASCII/चीनी अक्षरों के साथ Auto या Unicode अक्षरों के लिए Unicode का उपयोग किया जाए।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AUTO](#AUTO) | Numeric, Text, ECI, Binary Bytes और 4 GB18030 मोड्स का क्रम स्वचालित रूप से बदलता रहता है। |
| [BINARY](#BINARY) | Binary byte मोड किसी भी रूप में बाइनरी डेटा को एन्कोड करता है और उन्हें उनके बाइनरी बाइट में एन्कोड करता है। |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Region One में प्रत्येक सामान्य चीनी अक्षर 12 बिट्स द्वारा दर्शाया जाता है। |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Region Two में प्रत्येक सामान्य चीनी अक्षर 12 बिट्स द्वारा दर्शाया जाता है। |
| [ECI](#ECI) | Extended Channel Interpretation (ECI) मोड |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | GB18030 4-बाइट Region के प्रत्येक अक्षर को 21 बिट्स द्वारा दर्शाया जाता है। |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | GB18030 2-बाइट Region के प्रत्येक अक्षर को 15 बिट्स द्वारा दर्शाया जाता है। |
| [GS_1](#GS-1) | GS1 मोड दर्शाता है कि Han Xin Code में प्रस्तुत डेटा GS1 जनरल स्पेसिफिकेशन द्वारा परिभाषित GS1 सिस्टम का GS1 डेटा है। |
| [NUMERIC](#NUMERIC) | Numeric मोड दशमलव अंक सेट (अंक 0-9, बाइट मान 30HEX से 39HEX) से डेटा को एन्कोड करता है। |
| [TEXT](#TEXT) | Text मोड ISO/IEC 646 में परिभाषित सामान्य प्रतीकों (जैसे) से डेटा को एन्कोड करता है। |
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
public static final HanXinModes AUTO
```


Numeric, Text, ECI, Binary Bytes और 4 GB18030 मोड्स का क्रम स्वचालित रूप से बदलता रहता है।

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Binary byte मोड किसी भी रूप में बाइनरी डेटा को एन्कोड करता है और उन्हें उनके बाइनरी बाइट में एन्कोड करता है। Binary Byte मोड में प्रत्येक बाइट 8 बिट्स द्वारा दर्शाया जाता है।

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Region One में प्रत्येक सामान्य चीनी अक्षर 12 बिट्स द्वारा दर्शाया जाता है। Region One के सामान्य चीनी अक्षरों में वे अक्षर शामिल हैं जिनका पहला बाइट मान B0HEX से D7HEX की सीमा में है और दूसरा बाइट मान A1HEX से FEHEX की सीमा में है (3760 अक्षर), तथा वे अक्षर जिनका पहला बाइट मान A1HEX से A3HEX की सीमा में है और दूसरा बाइट मान A1HEX से FEHEX की सीमा में है (282 अक्षर), और वे अक्षर जिनके बाइट मान A8A1HEX से A8C0HEX की सीमा में हैं (32 अक्षर)।

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Region Two में प्रत्येक सामान्य चीनी अक्षर 12 बिट्स द्वारा दर्शाया जाता है। Region Two के सामान्य चीनी अक्षरों में वे अक्षर शामिल हैं जिनका पहला बाइट मान D8HEX से F7HEX की सीमा में है और दूसरा बाइट मान A1HEX से FEHEX की सीमा में है।

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Extended Channel Interpretation (ECI) मोड

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


GB18030 4-बाइट Region के प्रत्येक अक्षर को 21 बिट्स द्वारा दर्शाया जाता है। GB18030 4-बाइट Region GB18030 चार-बाइट क्षेत्र के सभी अक्षरों से डेटा को एन्कोड करता है (उदाहरण के लिए, वे अक्षर जिनका पहला बाइट मान 81HEX से FEHEX की सीमा में है, दूसरा बाइट मान 30HEX से 39HEX की सीमा में है, तीसरा बाइट मान 81HEX से FEHEX की सीमा में है, और चौथा बाइट मान 30HEX से 39HEX की सीमा में है)।

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


GB18030 2-बाइट Region के प्रत्येक अक्षर को 15 बिट्स द्वारा दर्शाया जाता है। GB18030 2-बाइट Region GB18030 डबल-बाइट क्षेत्र के सभी अक्षरों (जिसमें Region One और Two के सामान्य चीनी अक्षर शामिल हैं) से डेटा को एन्कोड करता है (उदाहरण के लिए, वे चीनी अक्षर जिनका पहला बाइट मान 81HEX से FEHEX की सीमा में है और दूसरा बाइट मान 40HEX से 7EHEX या 80HEX से FEHEX की सीमा में है)।

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1 मोड दर्शाता है कि Han Xin Code में प्रस्तुत डेटा GS1 जनरल स्पेसिफिकेशन द्वारा परिभाषित GS1 सिस्टम का GS1 डेटा है। इनपुट स्ट्रिंग का उदाहरण: "(01)03453120000011(17)191125(10)ABCD1234(21)10"।

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Numeric मोड दशमलव अंक सेट (अंक 0-9, बाइट मान 30HEX से 39HEX) से डेटा को एन्कोड करता है। सामान्यतः, 3 डेटा अक्षरों को 10 बिट्स द्वारा दर्शाया जाता है।

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Text मोड ISO/IEC 646 में परिभाषित सामान्य प्रतीकों (बाइट मान 00 HEX से 1B HEX और 20 HEX से 7F HEX) से डेटा को एन्कोड करता है।

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode मोड Han Xin Code में UTF8 एन्कोडिंग/कैरेक्टरसेट के संदर्भ में किसी भी टेक्स्ट डेटा को प्रदर्शित करने का तरीका बनाता है।

### URI {#URI}
```
public static final HanXinModes URI
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
public static HanXinModes valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
### values() {#values--}
```
public static HanXinModes[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinModes[]
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

