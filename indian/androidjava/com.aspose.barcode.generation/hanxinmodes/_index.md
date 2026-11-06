---
title: "HanXinModes"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "Han Xin कोड एन्कोडिंग मोड।"
type: docs
weight: 90
url: /hi/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code एन्कोडिंग मोड। ASCII / चीनी अक्षरों के साथ Auto या Unicode अक्षरों के लिए Unicode का उपयोग करने की सलाह दी जाती है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AUTO](#AUTO) | Numeric, Text, ECI, Binary Bytes और 4 GB18030 मोड्स की क्रमिकता जो स्वतः बदलती है। |
| [BINARY](#BINARY) | Binary byte मोड बाइनरी डेटा को किसी भी रूप में एन्कोड करता है और उन्हें उनके बाइनरी बाइट में एन्कोड करता है। |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Region One में प्रत्येक सामान्य चीनी अक्षर 12 बिट्स द्वारा दर्शाया जाता है। |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Region Two में प्रत्येक सामान्य चीनी अक्षर 12 बिट्स द्वारा दर्शाया जाता है। |
| [ECI](#ECI) | Extended Channel Interpretation (ECI) मोड |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | प्रत्येक GB18030 4-बाइट Region अक्षर 21 बिट्स द्वारा दर्शाया जाता है। |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | प्रत्येक GB18030 2-बाइट Region अक्षर 15 बिट्स द्वारा दर्शाया जाता है। |
| [GS_1](#GS-1) | GS1 मोड दर्शाता है कि Han Xin Code में प्रतिनिधित्व किया गया डेटा GS1 जनरल स्पेसिफिकेशन द्वारा परिभाषित GS1 सिस्टम का GS1 डेटा है। |
| [NUMERIC](#NUMERIC) | Numeric मोड दशमलव अंक सेट (अंक 0-9, बाइट मान 30HEX से 39HEX) से डेटा को एन्कोड करता है। |
| [TEXT](#TEXT) | Text मोड ISO/IEC 646 में परिभाषित सामान्य प्रतीकों से डेटा को एन्कोड करता है, अर्थात्। |
| [UNICODE](#UNICODE) | Unicode मोड Han Xin Code में UTF8 एन्कोडिंग/कैरेक्टरसेट के संदर्भ में किसी भी टेक्स्ट डेटा को प्रदर्शित करने का तरीका बनाता है। |
| [URI](#URI) | URI मोड दर्शाता है कि Han Xin Code में प्रतिनिधित्व किया गया डेटा RFC 3986 के Uniform Resource Identifier (URI) संदर्भ है। |
## Methods

| Method | विवरण |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
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
public static final HanXinModes AUTO
```


Numeric, Text, ECI, Binary Bytes और 4 GB18030 मोड्स की क्रमिकता जो स्वतः बदलती है।

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Binary byte मोड बाइनरी डेटा को किसी भी रूप में एन्कोड करता है और उन्हें उनके बाइनरी बाइट में एन्कोड करता है। Binary Byte मोड में प्रत्येक बाइट 8 बिट्स द्वारा दर्शाया जाता है।

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


क्षेत्र एक में प्रत्येक सामान्य चीनी अक्षर 12 बिट्स द्वारा दर्शाया जाता है। क्षेत्र एक में सामान्य चीनी अक्षरों में वे अक्षर शामिल हैं जिनका पहला बाइट मान B0HEX से D7HEX की सीमा में है और दूसरा बाइट मान A1HEX से FEHEX की सीमा में है (3760 अक्षर), और वे अक्षर जिनका पहला बाइट मान A1HEX से A3HEX की सीमा में है, और दूसरा बाइट मान A1HEX से FEHEX की सीमा में है (282 अक्षर), और वे अक्षर जिनके बाइट मान A8A1HEX से A8C0HEX की सीमा में हैं (32 अक्षर)।

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


क्षेत्र दो में प्रत्येक सामान्य चीनी अक्षर 12 बिट्स द्वारा दर्शाया जाता है। क्षेत्र दो में सामान्य चीनी अक्षरों में वे अक्षर शामिल हैं जिनका पहला बाइट मान D8HEX से F7HEX की सीमा में है, और दूसरा बाइट मान A1HEX से FEHEX की सीमा में है।

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Extended Channel Interpretation (ECI) मोड

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


GB18030 4-बाइट क्षेत्र का प्रत्येक अक्षर 21 बिट्स द्वारा दर्शाया जाता है। GB18030 4-बाइट क्षेत्र GB18030 चार-बाइट क्षेत्र के सभी अक्षरों से डेटा एन्कोड करता है (अर्थात, वे अक्षर जिनका पहला बाइट मान 81HEX से FEHEX की सीमा में है, दूसरा बाइट मान 30HEX से 39HEX की सीमा में है, तीसरा बाइट मान 81HEX से FEHEX की सीमा में है, और चौथा बाइट मान 30HEX से 39HEX की सीमा में है)।

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


GB18030 2-बाइट क्षेत्र का प्रत्येक अक्षर 15 बिट्स द्वारा दर्शाया जाता है। GB18030 2-बाइट क्षेत्र GB18030 दो-बाइट क्षेत्र के सभी अक्षरों (क्षेत्र एक और दो में सामान्य चीनी अक्षरों सहित) से डेटा एन्कोड करता है, (अर्थात, वे चीनी अक्षर जिनका पहला बाइट मान 81HEX से FEHEX की सीमा में है और दूसरा बाइट मान 40HEX से 7EHEX या 80HEX से FEHEX की सीमा में है)।

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1 मोड दर्शाता है कि हान शिन कोड में प्रतिनिधित्व किया गया डेटा GS1 सिस्टम द्वारा परिभाषित GS1 जनरल स्पेसिफिकेशन के अनुसार GS1 डेटा है। इनपुट स्ट्रिंग का उदाहरण: "(01)03453120000011(17)191125(10)ABCD1234(21)10"।

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


न्यूमेरिक मोड दशमलव अंक सेट (अंक 0-9, बाइट मान 30HEX से 39HEX) से डेटा एन्कोड करता है। सामान्यतः, 3 डेटा अक्षरों को 10 बिट्स द्वारा दर्शाया जाता है।

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


टेक्स्ट मोड ISO/IEC 646 में परिभाषित सामान्य प्रतीकों से डेटा एन्कोड करता है, अर्थात बाइट मान 00 HEX से 1B HEX और 20 HEX से 7F HEX।

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode मोड Han Xin Code में UTF8 एन्कोडिंग/कैरेक्टरसेट के संदर्भ में किसी भी टेक्स्ट डेटा को प्रदर्शित करने का तरीका बनाता है।

### URI {#URI}
```
public static final HanXinModes URI
```


URI मोड दर्शाता है कि Han Xin Code में प्रतिनिधित्व किया गया डेटा RFC 3986 के Uniform Resource Identifier (URI) संदर्भ है।

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
### fromValue(int value) {#fromValue-int-}
```
public static HanXinModes fromValue(int value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
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
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

