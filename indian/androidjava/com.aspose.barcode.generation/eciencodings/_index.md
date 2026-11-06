---
title: "ECIEncodings"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "Extended Channel Interpretation पहचानकर्ता।"
type: docs
weight: 36
url: /hi/androidjava/com.aspose.barcode.generation/eciencodings/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ECIEncodings extends System.Enum
```

एक्सटेंडेड चैनल इंटरप्रिटेशन आइडेंटिफायर्स। इसका उपयोग बारकोड रीडर को यह बताने के लिए किया जाता है कि प्रतीक में डेटा एन्कोड करने के लिए कौन से संदर्भ उपयोग किए गए हैं।

--------------------

> ```
> Example how to use ECI encoding
>  
>      BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>      generator.setCodeText("12345TEXT");
>      generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECIEncoding);
>      generator.getParameters().getBarcode().getQR().setECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.png");
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [BINARY](#BINARY) | 8-बिट बाइनरी डेटा। |
| [Big5](#Big5) | बिग 5 (ताइवान) चीनी कैरेक्टर सेट एन्कोडिंग। |
| [EUC_KR](#EUC-KR) | कोरियन कैरेक्टर सेट एन्कोडिंग। |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [GB18030](#GB18030) | GGB18030 चीनी कैरेक्टर सेट एन्कोडिंग। |
| [GB2312](#GB2312) | GB2312 चीनी कैरेक्टर सेट एन्कोडिंग। |
| [GBK](#GBK) | GBK (सरलीकृत चीनी के लिए GB2312 का विस्तार) एन्कोडिंग। |
| [INVARIANT](#INVARIANT) | ISO/IEC 646: ISO 7-बिट कोडेड कैरेक्टर सेट - इनवेरिएंट कैरेक्टर सेट एन्कोडिंग। |
| [ISO_8859_1](#ISO-8859-1) | ISO/IEC 8859-1 लैटिन वर्णमाला No. |
| [ISO_8859_10](#ISO-8859-10) | ISO/IEC 8859-10 लैटिन वर्णमाला No. |
| [ISO_8859_11](#ISO-8859-11) | ISO/IEC 8859-11 लैटिन/थाई वर्णमाला एन्कोडिंग। |
| [ISO_8859_13](#ISO-8859-13) | ISO/IEC 8859-13 लैटिन वर्णमाला No. |
| [ISO_8859_14](#ISO-8859-14) | ISO/IEC 8859-14 लैटिन वर्णमाला No. |
| [ISO_8859_15](#ISO-8859-15) | ISO/IEC 8859-15 लैटिन वर्णमाला No. |
| [ISO_8859_16](#ISO-8859-16) | ISO/IEC 8859-16 लैटिन वर्णमाला No। |
| [ISO_8859_2](#ISO-8859-2) | ISO/IEC 8859-2 लैटिन वर्णमाला संख्या। |
| [ISO_8859_3](#ISO-8859-3) | ISO/IEC 8859-3 लैटिन वर्णमाला संख्या। |
| [ISO_8859_4](#ISO-8859-4) | ISO/IEC 8859-4 लैटिन वर्णमाला संख्या। |
| [ISO_8859_5](#ISO-8859-5) | ISO/IEC 8859-5 लैटिन/सिरिलिक वर्णमाला एन्कोडिंग। |
| [ISO_8859_6](#ISO-8859-6) | ISO/IEC 8859-6 लैटिन/अरबी वर्णमाला एन्कोडिंग। |
| [ISO_8859_7](#ISO-8859-7) | ISO/IEC 8859-7 लैटिन/ग्रीक वर्णमाला एन्कोडिंग। |
| [ISO_8859_8](#ISO-8859-8) | ISO/IEC 8859-8 लैटिन/हिब्रू वर्णमाला एन्कोडिंग। |
| [ISO_8859_9](#ISO-8859-9) | ISO/IEC 8859-9 लैटिन वर्णमाला संख्या। |
| [NONE](#NONE) | कोई विस्तारित चैनल व्याख्या नहीं/p> |
| [Shift_JIS](#Shift-JIS) | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) एन्कोडिंग। |
| [US_ASCII](#US-ASCII) | ISO/IEC 646:1991 अंतर्राष्ट्रीय संदर्भ संस्करण ISO 7-बिट कोडेड कैरेक्टर सेट एन्कोडिंग का। |
| [UTF16BE](#UTF16BE) | ISO/IEC 10646 UCS-2 (उच्च क्रम बाइट पहले) एन्कोडिंग। |
| [UTF16LE](#UTF16LE) | ISO/IEC 10646 UTF-16LE एन्कोडिंग। |
| [UTF32BE](#UTF32BE) | ISO/IEC 10646 UTF-32BE एन्कोडिंग। |
| [UTF32LE](#UTF32LE) | ISO/IEC 10646 UTF-32LE एन्कोडिंग। |
| [UTF8](#UTF8) | ISO/IEC 10646 UTF-8 एन्कोडिंग। |
| [Win1250](#Win1250) | Windows 1250 लैटिन 2 (मध्य यूरोप) एन्कोडिंग। |
| [Win1251](#Win1251) | Windows 1251 सिरिलिक एन्कोडिंग। |
| [Win1252](#Win1252) | Windows 1252 लैटिन 1 एन्कोडिंग। |
| [Win1256](#Win1256) | Windows 1256 अरबी एन्कोडिंग। |
## Methods

| Method | विवरण |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T that)](#CloneTo-T-) |  |
| [CloneTo(System.Enum that)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type enumType, Object value, String format)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> enumType, long value, String format)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type enumType, Object value)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> enumType, long value)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type enumType)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> enumType)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type enumType)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> enumType)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> enumType, String name)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type enumType)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type enumType, Object value)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type enumType, String value)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type enumType, long value)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> enumType, long value)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type enumType, String value)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type enumType, String value, Boolean ignoreCase)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> enumType, String value)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> enumType, String value, Boolean ignoreCase)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum e)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type enumType, Object value)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> enumType, long value)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BINARY {#BINARY}
```
public static final int BINARY
```


8-बिट बाइनरी डेटा। ECI Id:"\\000899"

### Big5 {#Big5}
```
public static final int Big5
```


Big 5 (ताइवान) चीनी कैरेक्टर सेट एन्कोडिंग। ECI Id:"\\000028"

### EUC_KR {#EUC-KR}
```
public static final int EUC_KR
```


कोरियाई कैरेक्टर सेट एन्कोडिंग। ECI Id:"\\000030"

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### GB18030 {#GB18030}
```
public static final int GB18030
```


GGB18030 चीनी कैरेक्टर सेट एन्कोडिंग। ECI Id:"\\000032"

### GB2312 {#GB2312}
```
public static final int GB2312
```


GB2312 चीनी कैरेक्टर सेट एन्कोडिंग। ECI Id:"\\000029"

### GBK {#GBK}
```
public static final int GBK
```


GBK (सरलीकृत चीनी के लिए GB2312 का विस्तार) एन्कोडिंग। ECI Id:"\\000031"

### INVARIANT {#INVARIANT}
```
public static final int INVARIANT
```


ISO/IEC 646: ISO 7-बिट कोडेड कैरेक्टर सेट - अपरिवर्तनीय कैरेक्टर सेट एन्कोडिंग। ECI Id:"\\000170"

### ISO_8859_1 {#ISO-8859-1}
```
public static final int ISO_8859_1
```


ISO/IEC 8859-1 लैटिन वर्णमाला संख्या 1 एन्कोडिंग। ECI Id:"\\000003"

### ISO_8859_10 {#ISO-8859-10}
```
public static final int ISO_8859_10
```


ISO/IEC 8859-10 लैटिन वर्णमाला संख्या 6 एन्कोडिंग। ECI Id:"\\000012"

### ISO_8859_11 {#ISO-8859-11}
```
public static final int ISO_8859_11
```


ISO/IEC 8859-11 लैटिन/थाई वर्णमाला एन्कोडिंग। ECI Id:"\\000013"

### ISO_8859_13 {#ISO-8859-13}
```
public static final int ISO_8859_13
```


ISO/IEC 8859-13 लैटिन वर्णमाला संख्या 7 (बाल्टिक रिम) एन्कोडिंग। ECI Id:"\\000015"

### ISO_8859_14 {#ISO-8859-14}
```
public static final int ISO_8859_14
```


ISO/IEC 8859-14 लैटिन वर्णमाला संख्या 8 (सेल्टिक) एन्कोडिंग। ECI Id:"\\000016"

### ISO_8859_15 {#ISO-8859-15}
```
public static final int ISO_8859_15
```


ISO/IEC 8859-15 लैटिन वर्णमाला संख्या 9 एन्कोडिंग। ECI Id:"\\000017"

### ISO_8859_16 {#ISO-8859-16}
```
public static final int ISO_8859_16
```


ISO/IEC 8859-16 लैटिन वर्णमाला संख्या 10 एन्कोडिंग। ECI Id:"\\000018"

### ISO_8859_2 {#ISO-8859-2}
```
public static final int ISO_8859_2
```


ISO/IEC 8859-2 लैटिन वर्णमाला संख्या 2 एन्कोडिंग। ECI Id:"\\000004"

### ISO_8859_3 {#ISO-8859-3}
```
public static final int ISO_8859_3
```


ISO/IEC 8859-3 लैटिन वर्णमाला संख्या 3 एन्कोडिंग। ECI Id:"\\000005"

### ISO_8859_4 {#ISO-8859-4}
```
public static final int ISO_8859_4
```


ISO/IEC 8859-4 लैटिन वर्णमाला संख्या 4 एन्कोडिंग। ECI Id:"\\000006"

### ISO_8859_5 {#ISO-8859-5}
```
public static final int ISO_8859_5
```


ISO/IEC 8859-5 लैटिन/सिरिलिक वर्णमाला एन्कोडिंग। ECI Id:"\\000007"

### ISO_8859_6 {#ISO-8859-6}
```
public static final int ISO_8859_6
```


ISO/IEC 8859-6 लैटिन/अरबी वर्णमाला एन्कोडिंग। ECI Id:"\\000008"

### ISO_8859_7 {#ISO-8859-7}
```
public static final int ISO_8859_7
```


ISO/IEC 8859-7 लैटिन/ग्रीक वर्णमाला एन्कोडिंग। ECI Id:"\\000009"

### ISO_8859_8 {#ISO-8859-8}
```
public static final int ISO_8859_8
```


ISO/IEC 8859-8 लैटिन/हिब्रू वर्णमाला एन्कोडिंग। ECI Id:"\\000010"

### ISO_8859_9 {#ISO-8859-9}
```
public static final int ISO_8859_9
```


ISO/IEC 8859-9 लैटिन वर्णमाला संख्या 5 एन्कोडिंग। ECI Id:"\\000011"

### NONE {#NONE}
```
public static final int NONE
```


कोई विस्तारित चैनल व्याख्या नहीं/p>

### Shift_JIS {#Shift-JIS}
```
public static final int Shift_JIS
```


Shift JIS (JIS X 0208 परिशिष्ट 1 + JIS X 0201) एन्कोडिंग। ECI Id:"\\000020"

### US_ASCII {#US-ASCII}
```
public static final int US_ASCII
```


ISO/IEC 646:1991 ISO 7-बिट कोडेड कैरेक्टर सेट एन्कोडिंग का अंतर्राष्ट्रीय रेफ़रेंस संस्करण। ECI Id:"\\000027"

### UTF16BE {#UTF16BE}
```
public static final int UTF16BE
```


ISO/IEC 10646 UCS-2 (हाई ऑर्डर बाइट पहले) एन्कोडिंग। ECI Id:"\\000025"

### UTF16LE {#UTF16LE}
```
public static final int UTF16LE
```


ISO/IEC 10646 UTF-16LE एन्कोडिंग। ECI Id:"\\000033"

### UTF32BE {#UTF32BE}
```
public static final int UTF32BE
```


ISO/IEC 10646 UTF-32BE एन्कोडिंग। ECI Id:"\\000034"

### UTF32LE {#UTF32LE}
```
public static final int UTF32LE
```


ISO/IEC 10646 UTF-32LE एन्कोडिंग। ECI Id:"\\000035"

### UTF8 {#UTF8}
```
public static final int UTF8
```


ISO/IEC 10646 UTF-8 एन्कोडिंग। ECI Id:"\\000026"

### Win1250 {#Win1250}
```
public static final int Win1250
```


Windows 1250 लैटिन 2 (सेंट्रल यूरोप) एन्कोडिंग। ECI Id:"\\000021"

### Win1251 {#Win1251}
```
public static final int Win1251
```


Windows 1251 सायरिलिक एन्कोडिंग। ECI Id:"\\000022"

### Win1252 {#Win1252}
```
public static final int Win1252
```


Windows 1252 लैटिन 1 एन्कोडिंग। ECI Id:"\\000023"

### Win1256 {#Win1256}
```
public static final int Win1256
```


Windows 1256 अरबी एन्कोडिंग। ECI Id:"\\000024"

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T that) {#CloneTo-T-}
```
public abstract void CloneTo(T that)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| वह | T |  |

### CloneTo(System.Enum that) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum that)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| वह | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type enumType, Object value, String format) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type enumType, Object value, String format)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.Object |  |
| फ़ॉर्मेट | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> enumType, long value, String format) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> enumType, long value, String format)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | long |  |
| फ़ॉर्मेट | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type enumType, Object value) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type enumType, Object value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> enumType, long value) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | long |  |

**Returns:**
java.lang.String
### getNames(System.Type enumType) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type enumType)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> enumType) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type enumType) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type enumType)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> enumType) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> enumType, String name) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> enumType, String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| नाम | java.lang.String |  |

**Returns:**
long
### getValues(System.Type enumType) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type enumType)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type enumType, Object value) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type enumType, Object value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type enumType, String value) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type enumType, String value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type enumType, long value) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type enumType, long value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | long |  |

**Returns:**
boolean
### isDefined(Class<?> enumType, long value) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | long |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(System.Type enumType, String value) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type enumType, String value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.String |  |

**Returns:**
long
### parse(System.Type enumType, String value, Boolean ignoreCase) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> enumType, String value) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> enumType, String value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | java.lang.String |  |

**Returns:**
long
### parse(Class<?> enumType, String value, Boolean ignoreCase) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum e) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum e)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| e | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type enumType, Object value) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type enumType, Object value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> enumType, long value) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | long |  |

**Returns:**
java.lang.String
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

