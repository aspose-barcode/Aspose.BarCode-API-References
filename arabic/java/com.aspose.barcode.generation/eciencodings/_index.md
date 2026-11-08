---
title: "ECIEncodings"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "معرفات تفسير القناة الموسعة."
type: docs
weight: 35
url: /ar/java/com.aspose.barcode.generation/eciencodings/
---
**Inheritance:**
باركود Mailmark رباعي الحالة C
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
>      generator.getParameters().getBarcode().getQR().setECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.png");
> ```
## الحقول

| حقل | الوصف |
| --- | --- |
| [BINARY](#BINARY) | بيانات ثنائية 8-بت. |
| [Big5](#Big5) | ترميز مجموعة الأحرف الصينية Big 5 (تايوان). |
| [EUC_KR](#EUC-KR) | ترميز مجموعة الأحرف الكورية. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [GB18030](#GB18030) | ترميز مجموعة الأحرف الصينية GGB18030. |
| [GB2312](#GB2312) | ترميز مجموعة الأحرف الصينية GB2312. |
| [GBK](#GBK) | ترميز GBK (امتداد GB2312 للصينية المبسطة). |
| [INVARIANT](#INVARIANT) | ISO/IEC 646: مجموعة أحرف مشفرة بسبعة بتات وفق ISO - ترميز مجموعة الأحرف الثابتة. |
| [ISO_8859_1](#ISO-8859-1) | ISO/IEC 8859-1: الأبجدية اللاتينية رقم. |
| [ISO_8859_10](#ISO-8859-10) | ISO/IEC 8859-10: الأبجدية اللاتينية رقم. |
| [ISO_8859_11](#ISO-8859-11) | ISO/IEC 8859-11: ترميز الأبجدية اللاتينية/التايلاندية. |
| [ISO_8859_13](#ISO-8859-13) | ISO/IEC 8859-13 الأبجدية اللاتينية رقم. |
| [ISO_8859_14](#ISO-8859-14) | ISO/IEC 8859-14 الأبجدية اللاتينية رقم. |
| [ISO_8859_15](#ISO-8859-15) | ISO/IEC 8859-15 الأبجدية اللاتينية رقم. |
| [ISO_8859_16](#ISO-8859-16) | ISO/IEC 8859-16 الأبجدية اللاتينية رقم. |
| [ISO_8859_2](#ISO-8859-2) | ISO/IEC 8859-2 الأبجدية اللاتينية رقم. |
| [ISO_8859_3](#ISO-8859-3) | ISO/IEC 8859-3 الأبجدية اللاتينية رقم. |
| [ISO_8859_4](#ISO-8859-4) | ISO/IEC 8859-4 الأبجدية اللاتينية رقم. |
| [ISO_8859_5](#ISO-8859-5) | ISO/IEC 8859-5 ترميز الأبجدية اللاتينية/السيريلية. |
| [ISO_8859_6](#ISO-8859-6) | ISO/IEC 8859-6 ترميز الأبجدية اللاتينية/العربية. |
| [ISO_8859_7](#ISO-8859-7) | ISO/IEC 8859-7 ترميز الأبجدية اللاتينية/اليونانية. |
| [ISO_8859_8](#ISO-8859-8) | ISO/IEC 8859-8 ترميز الأبجدية اللاتينية/العبرية. |
| [ISO_8859_9](#ISO-8859-9) | ISO/IEC 8859-9 الأبجدية اللاتينية رقم. |
| [NONE](#NONE) | لا تفسير قناة موسعة/p> |
| [Shift_JIS](#Shift-JIS) | ترميز Shift JIS (JIS X 0208 Annex 1 + JIS X 0201). |
| [US_ASCII](#US-ASCII) | ISO/IEC 646:1991 النسخة المرجعية الدولية لمجموعة الأحرف المشفرة ب7 بت من ISO ترميز. |
| [UTF16BE](#UTF16BE) | ISO/IEC 10646 UCS-2 (البايت الأعلى أولاً) ترميز. |
| [UTF16LE](#UTF16LE) | ISO/IEC 10646 UTF-16LE ترميز. |
| [UTF32BE](#UTF32BE) | ISO/IEC 10646 UTF-32BE ترميز. |
| [UTF32LE](#UTF32LE) | ISO/IEC 10646 UTF-32LE ترميز. |
| [UTF8](#UTF8) | ISO/IEC 10646 UTF-8 ترميز. |
| [Win1250](#Win1250) | Windows 1250 اللاتينية 2 (وسط أوروبا) ترميز. |
| [Win1251](#Win1251) | Windows 1251 ترميز السيريلية. |
| [Win1252](#Win1252) | Windows 1252 ترميز اللاتينية 1. |
| [Win1256](#Win1256) | Windows 1256 ترميز العربية. |
## الدوال

| دالة | الوصف |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BINARY {#BINARY}
```
public static final int BINARY
```


بيانات ثنائية 8-بت. ECI Id:"\\000899"

### Big5 {#Big5}
```
public static final int Big5
```


ترميز مجموعة الأحرف الصينية Big 5 (تايوان). ECI Id:"\\000028"

### EUC_KR {#EUC-KR}
```
public static final int EUC_KR
```


ترميز مجموعة الأحرف الكورية. ECI Id:"\\000030"

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### GB18030 {#GB18030}
```
public static final int GB18030
```


ترميز مجموعة الأحرف الصينية GGB18030. ECI Id:"\\000032"

### GB2312 {#GB2312}
```
public static final int GB2312
```


ترميز مجموعة الأحرف الصينية GB2312. ECI Id:"\\000029"

### GBK {#GBK}
```
public static final int GBK
```


ترميز GBK (امتداد GB2312 للغة الصينية المبسطة). ECI Id:"\\000031"

### INVARIANT {#INVARIANT}
```
public static final int INVARIANT
```


ترميز مجموعة الأحرف المشفرة 7-بت ISO/IEC 646 - مجموعة الأحرف الثابتة. ECI Id:"\\000170"

### ISO_8859_1 {#ISO-8859-1}
```
public static final int ISO_8859_1
```


ترميز الأبجدية اللاتينية رقم 1 ISO/IEC 8859-1. ECI Id:"\\000003"

### ISO_8859_10 {#ISO-8859-10}
```
public static final int ISO_8859_10
```


ترميز الأبجدية اللاتينية رقم 6 ISO/IEC 8859-10. ECI Id:"\\000012"

### ISO_8859_11 {#ISO-8859-11}
```
public static final int ISO_8859_11
```


ترميز الأبجدية اللاتينية/التايلاندية ISO/IEC 8859-11. ECI Id:"\\000013"

### ISO_8859_13 {#ISO-8859-13}
```
public static final int ISO_8859_13
```


ترميز الأبجدية اللاتينية رقم 7 (حافة البلطيق) ISO/IEC 8859-13. ECI Id:"\\000015"

### ISO_8859_14 {#ISO-8859-14}
```
public static final int ISO_8859_14
```


ترميز الأبجدية اللاتينية رقم 8 (السلتية) ISO/IEC 8859-14. ECI Id:"\\000016"

### ISO_8859_15 {#ISO-8859-15}
```
public static final int ISO_8859_15
```


ترميز الأبجدية اللاتينية رقم 9 ISO/IEC 8859-15. ECI Id:"\\000017"

### ISO_8859_16 {#ISO-8859-16}
```
public static final int ISO_8859_16
```


ترميز الأبجدية اللاتينية رقم 10 ISO/IEC 8859-16. ECI Id:"\\000018"

### ISO_8859_2 {#ISO-8859-2}
```
public static final int ISO_8859_2
```


ترميز الأبجدية اللاتينية رقم 2 ISO/IEC 8859-2. ECI Id:"\\000004"

### ISO_8859_3 {#ISO-8859-3}
```
public static final int ISO_8859_3
```


ترميز الأبجدية اللاتينية رقم 3 ISO/IEC 8859-3. ECI Id:"\\000005"

### ISO_8859_4 {#ISO-8859-4}
```
public static final int ISO_8859_4
```


ترميز الأبجدية اللاتينية رقم 4 ISO/IEC 8859-4. ECI Id:"\\000006"

### ISO_8859_5 {#ISO-8859-5}
```
public static final int ISO_8859_5
```


ترميز الأبجدية اللاتينية/السيريلية ISO/IEC 8859-5. ECI Id:"\\000007"

### ISO_8859_6 {#ISO-8859-6}
```
public static final int ISO_8859_6
```


ترميز الأبجدية اللاتينية/العربية ISO/IEC 8859-6. ECI Id:"\\000008"

### ISO_8859_7 {#ISO-8859-7}
```
public static final int ISO_8859_7
```


ترميز الأبجدية اللاتينية/اليونانية ISO/IEC 8859-7. ECI Id:"\\000009"

### ISO_8859_8 {#ISO-8859-8}
```
public static final int ISO_8859_8
```


ترميز الأبجدية اللاتينية/العبرية ISO/IEC 8859-8. ECI Id:"\\000010"

### ISO_8859_9 {#ISO-8859-9}
```
public static final int ISO_8859_9
```


ترميز الأبجدية اللاتينية رقم 5 ISO/IEC 8859-9. ECI Id:"\\000011"

### NONE {#NONE}
```
public static final int NONE
```


لا تفسير قناة موسعة/p>

### Shift_JIS {#Shift-JIS}
```
public static final int Shift_JIS
```


ترميز Shift JIS (JIS X 0208 ملحق 1 + JIS X 0201). ECI Id:"\\000020"

### US_ASCII {#US-ASCII}
```
public static final int US_ASCII
```


ترميز النسخة المرجعية الدولية ISO/IEC 646:1991 لمجموعة الأحرف المشفرة 7-بت ISO. ECI Id:"\\000027"

### UTF16BE {#UTF16BE}
```
public static final int UTF16BE
```


ترميز UCS-2 (البايت الأعلى أولاً) ISO/IEC 10646. ECI Id:"\\000025"

### UTF16LE {#UTF16LE}
```
public static final int UTF16LE
```


ترميز UTF-16LE ISO/IEC 10646. ECI Id:"\\000033"

### UTF32BE {#UTF32BE}
```
public static final int UTF32BE
```


ترميز ISO/IEC 10646 UTF-32BE. معرف ECI:"\\000034"

### UTF32LE {#UTF32LE}
```
public static final int UTF32LE
```


ترميز ISO/IEC 10646 UTF-32LE. معرف ECI:"\\000035"

### UTF8 {#UTF8}
```
public static final int UTF8
```


ترميز ISO/IEC 10646 UTF-8. معرف ECI:"\\000026"

### Win1250 {#Win1250}
```
public static final int Win1250
```


ترميز Windows 1250 Latin 2 (أوروبا الوسطى). معرف ECI:"\\000021"

### Win1251 {#Win1251}
```
public static final int Win1251
```


ترميز Windows 1251 Cyrillic. معرف ECI:"\\000022"

### Win1252 {#Win1252}
```
public static final int Win1252
```


ترميز Windows 1252 Latin 1. معرف ECI:"\\000023"

### Win1256 {#Win1256}
```
public static final int Win1256
```


ترميز Windows 1256 Arabic. معرف ECI:"\\000024"

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Type
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |
| arg1 | java.lang.Object |  |
| java.lang.String[] | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| java.lang.String[] | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |

**Returns:**
java.util.Collection<java.lang.String>
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |

**Returns:**
arg2
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
com.aspose.ms.System.Array
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |

**Returns:**
java.lang.Boolean
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
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |
| arg1 | java.lang.String |  |
| java.lang.String[] | com.aspose.ms.System.Enum.AbstractEnum |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| java.lang.String[] | com.aspose.ms.System.Enum.AbstractEnum |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | SecondaryAndAdditionalData |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | arg2 |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

