---
title: ECIEncodings
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: معرفات تفسير القناة الموسعة.
type: docs
weight: 37
url: /ar/androidjava/com.aspose.barcode.generation/eciencodings/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ECIEncodings extends System.Enum
```

معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز.

--------------------

> ```
> Example how to use ECI encoding
>  
>      BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>      generator.setCodeText("12345TEXT");
>      generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECIEncoding);
>      generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.png");
> ```
## الحقول

| حقل | الوصف |
| --- | --- |
| [BINARY](#BINARY) | 8-bit binary data. |
| [Big5](#Big5) | Big 5 (Taiwan) Chinese Character Set encoding. |
| [EUC_KR](#EUC-KR) | Korean Character Set encoding. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [GB18030](#GB18030) | GGB18030 Chinese Character Set encoding. |
| [GB2312](#GB2312) | GB2312 Chinese Character Set encoding. |
| [GBK](#GBK) | GBK (extension of GB2312 for Simplified Chinese) encoding. |
| [INVARIANT](#INVARIANT) | ISO/IEC 646: ISO 7-bit coded character set - Invariant Characters set encoding. |
| [ISO_8859_1](#ISO-8859-1) | ISO/IEC 8859-1 Latin alphabet No. |
| [ISO_8859_10](#ISO-8859-10) | ISO/IEC 8859-10 Latin alphabet No. |
| [ISO_8859_11](#ISO-8859-11) | ISO/IEC 8859-11 Latin/Thai alphabet encoding. |
| [ISO_8859_13](#ISO-8859-13) | ISO/IEC 8859-13 Latin alphabet No. |
| [ISO_8859_14](#ISO-8859-14) | ISO/IEC 8859-14 Latin alphabet No. |
| [ISO_8859_15](#ISO-8859-15) | ISO/IEC 8859-15 Latin alphabet No. |
| [ISO_8859_16](#ISO-8859-16) | ISO/IEC 8859-16 Latin alphabet No. |
| [ISO_8859_2](#ISO-8859-2) | ISO/IEC 8859-2 Latin alphabet No. |
| [ISO_8859_3](#ISO-8859-3) | ISO/IEC 8859-3 Latin alphabet No. |
| [ISO_8859_4](#ISO-8859-4) | ISO/IEC 8859-4 Latin alphabet No. |
| [ISO_8859_5](#ISO-8859-5) | ISO/IEC 8859-5 Latin/Cyrillic alphabet encoding. |
| [ISO_8859_6](#ISO-8859-6) | ISO/IEC 8859-6 Latin/Arabic alphabet encoding. |
| [ISO_8859_7](#ISO-8859-7) | ISO/IEC 8859-7 Latin/Greek alphabet encoding. |
| [ISO_8859_8](#ISO-8859-8) | ISO/IEC 8859-8 Latin/Hebrew alphabet encoding. |
| [ISO_8859_9](#ISO-8859-9) | ISO/IEC 8859-9 Latin alphabet No. |
| [NONE](#NONE) | No Extended Channel Interpretation/p> |
| [Shift_JIS](#Shift-JIS) | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) encoding. |
| [US_ASCII](#US-ASCII) | ISO/IEC 646:1991 International Reference Version of ISO 7-bit coded character set encoding. |
| [UTF16BE](#UTF16BE) | ISO/IEC 10646 UCS-2 (البايت الأعلى أولاً) ترميز. |
| [UTF16LE](#UTF16LE) | ISO/IEC 10646 UTF-16LE ترميز. |
| [UTF32BE](#UTF32BE) | ISO/IEC 10646 UTF-32BE ترميز. |
| [UTF32LE](#UTF32LE) | ISO/IEC 10646 UTF-32LE ترميز. |
| [UTF8](#UTF8) | ISO/IEC 10646 UTF-8 ترميز. |
| [Win1250](#Win1250) | Windows 1250 Latin 2 (أوروبا الوسطى) ترميز. |
| [Win1251](#Win1251) | Windows 1251 سيريلي ترميز. |
| [Win1252](#Win1252) | Windows 1252 Latin 1 ترميز. |
| [Win1256](#Win1256) | Windows 1256 عربي ترميز. |
## Methods

| Method | الوصف |
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


بيانات ثنائية 8-بت. معرف ECI:\"\\\\000899\"

### Big5 {#Big5}
```
public static final int Big5
```


Big 5 (تايوان) مجموعة أحرف صينية ترميز. معرف ECI:\"\\\\000028\"

### EUC_KR {#EUC-KR}
```
public static final int EUC_KR
```


مجموعة أحرف كورية ترميز. معرف ECI:\"\\\\000030\"

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### GB18030 {#GB18030}
```
public static final int GB18030
```


GGB18030 مجموعة أحرف صينية ترميز. معرف ECI:\"\\\\000032\"

### GB2312 {#GB2312}
```
public static final int GB2312
```


GB2312 مجموعة أحرف صينية ترميز. معرف ECI:\"\\\\000029\"

### GBK {#GBK}
```
public static final int GBK
```


GBK (امتداد GB2312 للصينية المبسطة) ترميز. معرف ECI:\"\\\\000031\"

### INVARIANT {#INVARIANT}
```
public static final int INVARIANT
```


ISO/IEC 646: مجموعة أحرف مشفرة ب7-بت ISO - ترميز مجموعة الأحرف الثابتة. معرف ECI:\"\\\\000170\"

### ISO_8859_1 {#ISO-8859-1}
```
public static final int ISO_8859_1
```


ISO/IEC 8859-1 أبجدية لاتينية رقم 1 ترميز. معرف ECI:\"\\\\000003\"

### ISO_8859_10 {#ISO-8859-10}
```
public static final int ISO_8859_10
```


ISO/IEC 8859-10 أبجدية لاتينية رقم 6 ترميز. معرف ECI:\"\\\\000012\"

### ISO_8859_11 {#ISO-8859-11}
```
public static final int ISO_8859_11
```


ISO/IEC 8859-11 أبجدية لاتينية/تايلاندية ترميز. معرف ECI:\"\\\\000013\"

### ISO_8859_13 {#ISO-8859-13}
```
public static final int ISO_8859_13
```


ISO/IEC 8859-13 أبجدية لاتينية رقم 7 (حافة البلطيق) ترميز. معرف ECI:\"\\\\000015\"

### ISO_8859_14 {#ISO-8859-14}
```
public static final int ISO_8859_14
```


ISO/IEC 8859-14 أبجدية لاتينية رقم 8 (سلتية) ترميز. معرف ECI:\"\\\\000016\"

### ISO_8859_15 {#ISO-8859-15}
```
public static final int ISO_8859_15
```


ISO/IEC 8859-15 أبجدية لاتينية رقم 9 ترميز. معرف ECI:\"\\\\000017\"

### ISO_8859_16 {#ISO-8859-16}
```
public static final int ISO_8859_16
```


ISO/IEC 8859-16 أبجدية لاتينية رقم 10 ترميز. معرف ECI:\"\\\\000018\"

### ISO_8859_2 {#ISO-8859-2}
```
public static final int ISO_8859_2
```


ISO/IEC 8859-2 أبجدية لاتينية رقم 2 ترميز. معرف ECI:\"\\\\000004\"

### ISO_8859_3 {#ISO-8859-3}
```
public static final int ISO_8859_3
```


ISO/IEC 8859-3 أبجدية لاتينية رقم 3 ترميز. معرف ECI:\"\\\\000005\"

### ISO_8859_4 {#ISO-8859-4}
```
public static final int ISO_8859_4
```


ISO/IEC 8859-4 ترميز أبجدية لاتينية رقم 4. معرف ECI:\"\\\\000006\"

### ISO_8859_5 {#ISO-8859-5}
```
public static final int ISO_8859_5
```


ISO/IEC 8859-5 ترميز أبجدية لاتينية/سيريلية. معرف ECI:\"\\\\000007\"

### ISO_8859_6 {#ISO-8859-6}
```
public static final int ISO_8859_6
```


ISO/IEC 8859-6 ترميز أبجدية لاتينية/عربية. معرف ECI:\"\\\\000008\"

### ISO_8859_7 {#ISO-8859-7}
```
public static final int ISO_8859_7
```


ISO/IEC 8859-7 ترميز أبجدية لاتينية/يونانية. معرف ECI:\"\\\\000009\"

### ISO_8859_8 {#ISO-8859-8}
```
public static final int ISO_8859_8
```


ISO/IEC 8859-8 ترميز أبجدية لاتينية/عبرية. معرف ECI:\"\\\\000010\"

### ISO_8859_9 {#ISO-8859-9}
```
public static final int ISO_8859_9
```


ISO/IEC 8859-9 ترميز أبجدية لاتينية رقم 5. معرف ECI:\"\\\\000011\"

### NONE {#NONE}
```
public static final int NONE
```


No Extended Channel Interpretation/p>

### Shift_JIS {#Shift-JIS}
```
public static final int Shift_JIS
```


Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) ترميز. معرف ECI:\"\\\\000020\"

### US_ASCII {#US-ASCII}
```
public static final int US_ASCII
```


ISO/IEC 646:1991 النسخة المرجعية الدولية من ترميز مجموعة الأحرف المشفرة 7-بت ISO. معرف ECI:\"\\\\000027\"

### UTF16BE {#UTF16BE}
```
public static final int UTF16BE
```


ISO/IEC 10646 UCS-2 (البت الأعلى أولاً) ترميز. معرف ECI:\"\\\\000025\"

### UTF16LE {#UTF16LE}
```
public static final int UTF16LE
```


ISO/IEC 10646 ترميز UTF-16LE. معرف ECI:\"\\\\000033\"

### UTF32BE {#UTF32BE}
```
public static final int UTF32BE
```


ISO/IEC 10646 ترميز UTF-32BE. معرف ECI:\"\\\\000034\"

### UTF32LE {#UTF32LE}
```
public static final int UTF32LE
```


ISO/IEC 10646 ترميز UTF-32LE. معرف ECI:\"\\\\000035\"

### UTF8 {#UTF8}
```
public static final int UTF8
```


ISO/IEC 10646 ترميز UTF-8. معرف ECI:\"\\\\000026\"

### Win1250 {#Win1250}
```
public static final int Win1250
```


Windows 1250 ترميز لاتيني 2 (وسط أوروبا). معرف ECI:\"\\\\000021\"

### Win1251 {#Win1251}
```
public static final int Win1251
```


Windows 1251 ترميز سيريلية. معرف ECI:\"\\\\000022\"

### Win1252 {#Win1252}
```
public static final int Win1252
```


Windows 1252 ترميز لاتيني 1. معرف ECI:\"\\\\000023\"

### Win1256 {#Win1256}
```
public static final int Win1256
```


Windows 1256 ترميز عربية. معرف ECI:\"\\\\000024\"

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| ذلك | T |  |

### CloneTo(System.Enum that) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum that)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| ذلك | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type enumType, Object value, String format) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type enumType, Object value, String format)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| القيمة | java.lang.Object |  |
| تنسيق | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> enumType, long value, String format) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> enumType, long value, String format)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| القيمة | long |  |
| تنسيق | java.lang.String |  |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| القيمة | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> enumType, long value) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| القيمة | long |  |

**Returns:**
java.lang.String
### getNames(System.Type enumType) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type enumType)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> enumType) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type enumType) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type enumType)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> enumType) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> enumType, String name) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> enumType, String name)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| الاسم | java.lang.String |  |

**Returns:**
long
### getValues(System.Type enumType) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type enumType)
```




**Parameters:**
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| القيمة | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type enumType, String value) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type enumType, String value)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| القيمة | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type enumType, long value) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type enumType, long value)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| القيمة | long |  |

**Returns:**
boolean
### isDefined(Class<?> enumType, long value) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| القيمة | long |  |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| القيمة | java.lang.String |  |

**Returns:**
long
### parse(System.Type enumType, String value, Boolean ignoreCase) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| القيمة | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> enumType, String value) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> enumType, String value)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| القيمة | java.lang.String |  |

**Returns:**
long
### parse(Class<?> enumType, String value, Boolean ignoreCase) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| القيمة | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum e) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum e)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| e | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type enumType, Object value) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type enumType, Object value)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| القيمة | java.lang.Object |  |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| القيمة | long |  |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

