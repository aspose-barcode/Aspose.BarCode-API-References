---
title: ECIEncodings
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 扩展通道解释标识符。
type: docs
weight: 37
url: /zh/androidjava/com.aspose.barcode.generation/eciencodings/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ECIEncodings extends System.Enum
```

扩展信道解释标识符。它用于向条码阅读器提供有关在符号中用于编码数据的引用的详细信息。

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
## 字段

| 字段 | 描述 |
| --- | --- |
| [BINARY](#BINARY) | 8 位二进制数据。 |
| [Big5](#Big5) | Big 5（台湾）中文字符集编码。 |
| [EUC_KR](#EUC-KR) | 韩文字符集编码。 |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [GB18030](#GB18030) | GGB18030 中文字符集编码。 |
| [GB2312](#GB2312) | GB2312 中文字符集编码。 |
| [GBK](#GBK) | GBK（GB2312 的简体中文扩展）编码。 |
| [INVARIANT](#INVARIANT) | ISO/IEC 646：ISO 7 位编码字符集 - 不变字符集编码。 |
| [ISO_8859_1](#ISO-8859-1) | ISO/IEC 8859-1 拉丁字母 No。 |
| [ISO_8859_10](#ISO-8859-10) | ISO/IEC 8859-10 拉丁字母 No。 |
| [ISO_8859_11](#ISO-8859-11) | ISO/IEC 8859-11 拉丁/泰文字母编码。 |
| [ISO_8859_13](#ISO-8859-13) | ISO/IEC 8859-13 拉丁字母 No。 |
| [ISO_8859_14](#ISO-8859-14) | ISO/IEC 8859-14 拉丁字母 No。 |
| [ISO_8859_15](#ISO-8859-15) | ISO/IEC 8859-15 拉丁字母 No。 |
| [ISO_8859_16](#ISO-8859-16) | ISO/IEC 8859-16 拉丁字母 No。 |
| [ISO_8859_2](#ISO-8859-2) | ISO/IEC 8859-2 拉丁字母 No。 |
| [ISO_8859_3](#ISO-8859-3) | ISO/IEC 8859-3 拉丁字母 No。 |
| [ISO_8859_4](#ISO-8859-4) | ISO/IEC 8859-4 拉丁字母 No。 |
| [ISO_8859_5](#ISO-8859-5) | ISO/IEC 8859-5 拉丁/西里尔字母编码。 |
| [ISO_8859_6](#ISO-8859-6) | ISO/IEC 8859-6 拉丁/阿拉伯字母编码。 |
| [ISO_8859_7](#ISO-8859-7) | ISO/IEC 8859-7 拉丁/希腊字母编码。 |
| [ISO_8859_8](#ISO-8859-8) | ISO/IEC 8859-8 拉丁/希伯来字母编码。 |
| [ISO_8859_9](#ISO-8859-9) | ISO/IEC 8859-9 拉丁字母 No。 |
| [NONE](#NONE) | 无扩展通道解释/p> |
| [Shift_JIS](#Shift-JIS) | Shift JIS（JIS X 0208 附件 1 + JIS X 0201）编码。 |
| [US_ASCII](#US-ASCII) | ISO/IEC 646:1991 国际参考版 ISO 7 位编码字符集编码。 |
| [UTF16BE](#UTF16BE) | ISO/IEC 10646 UCS-2（高位字节在前）编码。 |
| [UTF16LE](#UTF16LE) | ISO/IEC 10646 UTF-16LE 编码。 |
| [UTF32BE](#UTF32BE) | ISO/IEC 10646 UTF-32BE 编码。 |
| [UTF32LE](#UTF32LE) | ISO/IEC 10646 UTF-32LE 编码。 |
| [UTF8](#UTF8) | ISO/IEC 10646 UTF-8 编码。 |
| [Win1250](#Win1250) | Windows 1250 拉丁文 2（中欧）编码。 |
| [Win1251](#Win1251) | Windows 1251 西里尔文编码。 |
| [Win1252](#Win1252) | Windows 1252 拉丁文 1 编码。 |
| [Win1256](#Win1256) | Windows 1256 阿拉伯文编码。 |
## Methods

| Method | 描述 |
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


8 位二进制数据。 ECI Id:"\000899"

### Big5 {#Big5}
```
public static final int Big5
```


Big 5（台湾）中文字符集编码。 ECI Id:"\000028"

### EUC_KR {#EUC-KR}
```
public static final int EUC_KR
```


韩文字符集编码。 ECI Id:"\000030"

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### GB18030 {#GB18030}
```
public static final int GB18030
```


GGB18030 中文字符集编码。 ECI Id:"\000032"

### GB2312 {#GB2312}
```
public static final int GB2312
```


GB2312 中文字符集编码。 ECI Id:"\000029"

### GBK {#GBK}
```
public static final int GBK
```


GBK（GB2312 对简体中文的扩展）编码。 ECI Id:"\000031"

### INVARIANT {#INVARIANT}
```
public static final int INVARIANT
```


ISO/IEC 646：ISO 7 位编码字符集 - 不变字符集 编码。 ECI Id:"\000170"

### ISO_8859_1 {#ISO-8859-1}
```
public static final int ISO_8859_1
```


ISO/IEC 8859-1 拉丁字母表第 1 号编码。 ECI Id:"\000003"

### ISO_8859_10 {#ISO-8859-10}
```
public static final int ISO_8859_10
```


ISO/IEC 8859-10 拉丁字母表第 6 号编码。 ECI Id:"\000012"

### ISO_8859_11 {#ISO-8859-11}
```
public static final int ISO_8859_11
```


ISO/IEC 8859-11 拉丁/泰文字母表编码。 ECI Id:"\000013"

### ISO_8859_13 {#ISO-8859-13}
```
public static final int ISO_8859_13
```


ISO/IEC 8859-13 拉丁字母表第 7 号（波罗的海沿岸）编码。 ECI Id:"\000015"

### ISO_8859_14 {#ISO-8859-14}
```
public static final int ISO_8859_14
```


ISO/IEC 8859-14 拉丁字母表第 8 号（凯尔特）编码。 ECI Id:"\000016"

### ISO_8859_15 {#ISO-8859-15}
```
public static final int ISO_8859_15
```


ISO/IEC 8859-15 拉丁字母表第 9 号编码。 ECI Id:"\000017"

### ISO_8859_16 {#ISO-8859-16}
```
public static final int ISO_8859_16
```


ISO/IEC 8859-16 拉丁字母表第 10 号编码。 ECI Id:"\000018"

### ISO_8859_2 {#ISO-8859-2}
```
public static final int ISO_8859_2
```


ISO/IEC 8859-2 拉丁字母表第 2 号编码。 ECI Id:"\000004"

### ISO_8859_3 {#ISO-8859-3}
```
public static final int ISO_8859_3
```


ISO/IEC 8859-3 拉丁字母表第 3 号编码。 ECI Id:"\000005"

### ISO_8859_4 {#ISO-8859-4}
```
public static final int ISO_8859_4
```


ISO/IEC 8859-4 拉丁字母表第4号 编码。ECI 标识:"\\000006"

### ISO_8859_5 {#ISO-8859-5}
```
public static final int ISO_8859_5
```


ISO/IEC 8859-5 拉丁/西里尔字母表 编码。ECI 标识:"\\000007"

### ISO_8859_6 {#ISO-8859-6}
```
public static final int ISO_8859_6
```


ISO/IEC 8859-6 拉丁/阿拉伯字母表 编码。ECI 标识:"\\000008"

### ISO_8859_7 {#ISO-8859-7}
```
public static final int ISO_8859_7
```


ISO/IEC 8859-7 拉丁/希腊字母表 编码。ECI 标识:"\\000009"

### ISO_8859_8 {#ISO-8859-8}
```
public static final int ISO_8859_8
```


ISO/IEC 8859-8 拉丁/希伯来字母表 编码。ECI 标识:"\\000010"

### ISO_8859_9 {#ISO-8859-9}
```
public static final int ISO_8859_9
```


ISO/IEC 8859-9 拉丁字母表第5号 编码。ECI 标识:"\\000011"

### NONE {#NONE}
```
public static final int NONE
```


无扩展通道解释/p>

### Shift_JIS {#Shift-JIS}
```
public static final int Shift_JIS
```


Shift JIS (JIS X 0208 附件1 + JIS X 0201) 编码。ECI 标识:"\\000020"

### US_ASCII {#US-ASCII}
```
public static final int US_ASCII
```


ISO/IEC 646:1991 ISO 7 位编码字符集的国际参考版 编码。ECI 标识:"\\000027"

### UTF16BE {#UTF16BE}
```
public static final int UTF16BE
```


ISO/IEC 10646 UCS-2（高位字节在前） 编码。ECI 标识:"\\000025"

### UTF16LE {#UTF16LE}
```
public static final int UTF16LE
```


ISO/IEC 10646 UTF-16LE 编码。ECI 标识:"\\000033"

### UTF32BE {#UTF32BE}
```
public static final int UTF32BE
```


ISO/IEC 10646 UTF-32BE 编码。ECI 标识:"\\000034"

### UTF32LE {#UTF32LE}
```
public static final int UTF32LE
```


ISO/IEC 10646 UTF-32LE 编码。ECI 标识:"\\000035"

### UTF8 {#UTF8}
```
public static final int UTF8
```


ISO/IEC 10646 UTF-8 编码。ECI 标识:"\\000026"

### Win1250 {#Win1250}
```
public static final int Win1250
```


Windows 1250 拉丁2（中欧） 编码。ECI 标识:"\\000021"

### Win1251 {#Win1251}
```
public static final int Win1251
```


Windows 1251 西里尔 编码。ECI 标识:"\\000022"

### Win1252 {#Win1252}
```
public static final int Win1252
```


Windows 1252 拉丁1 编码。ECI 标识:"\\000023"

### Win1256 {#Win1256}
```
public static final int Win1256
```


Windows 1256 阿拉伯 编码。ECI 标识:"\\000024"

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| 那 | T |  |

### CloneTo(System.Enum that) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum that)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 那 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type enumType, Object value, String format) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type enumType, Object value, String format)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| 值 | java.lang.Object |  |
| 格式 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> enumType, long value, String format) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> enumType, long value, String format)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| 值 | long |  |
| 格式 | java.lang.String |  |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| 值 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> enumType, long value) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| 值 | long |  |

**Returns:**
java.lang.String
### getNames(System.Type enumType) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type enumType)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> enumType) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type enumType) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type enumType)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> enumType) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> enumType, String name) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> enumType, String name)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| 名称 | java.lang.String |  |

**Returns:**
long
### getValues(System.Type enumType) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type enumType)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type enumType, String value) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type enumType, String value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| 值 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type enumType, long value) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type enumType, long value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| 值 | long |  |

**Returns:**
boolean
### isDefined(Class<?> enumType, long value) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| 值 | long |  |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| 值 | java.lang.String |  |

**Returns:**
long
### parse(System.Type enumType, String value, Boolean ignoreCase) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| 值 | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> enumType, String value) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> enumType, String value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| 值 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> enumType, String value, Boolean ignoreCase) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| 值 | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum e) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum e)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| e | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type enumType, Object value) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type enumType, Object value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| 值 | java.lang.Object |  |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| 值 | long |  |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

