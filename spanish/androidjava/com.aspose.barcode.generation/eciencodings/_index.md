---
title: ECIEncodings
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Identificadores de Interpretación de Canal Extendido.
type: docs
weight: 37
url: /es/androidjava/com.aspose.barcode.generation/eciencodings/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ECIEncodings extends System.Enum
```

Identificadores de Interpretación de Canal Extendido. Se utiliza para informar al lector de códigos de barras sobre los detalles de las referencias usadas para codificar los datos en el símbolo.

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
## Campos

| Campo | Descripción |
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
| [UTF16BE](#UTF16BE) | Codificación ISO/IEC 10646 UCS-2 (byte de orden alto primero). |
| [UTF16LE](#UTF16LE) | Codificación ISO/IEC 10646 UTF-16LE. |
| [UTF32BE](#UTF32BE) | Codificación ISO/IEC 10646 UTF-32BE. |
| [UTF32LE](#UTF32LE) | Codificación ISO/IEC 10646 UTF-32LE. |
| [UTF8](#UTF8) | Codificación ISO/IEC 10646 UTF-8. |
| [Win1250](#Win1250) | Codificación Windows 1250 Latin 2 (Europa Central). |
| [Win1251](#Win1251) | Codificación Windows 1251 Cirilí. |
| [Win1252](#Win1252) | Codificación Windows 1252 Latin 1. |
| [Win1256](#Win1256) | Codificación Windows 1256 Árabe. |
## Methods

| Method | Descripción |
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


Datos binarios de 8 bits. ECI Id:"\\000899"

### Big5 {#Big5}
```
public static final int Big5
```


Codificación Big 5 (Taiwán) Conjunto de caracteres chino. ECI Id:"\\000028"

### EUC_KR {#EUC-KR}
```
public static final int EUC_KR
```


Codificación del conjunto de caracteres coreano. ECI Id:"\\000030"

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### GB18030 {#GB18030}
```
public static final int GB18030
```


Codificación GGB18030 Conjunto de caracteres chino. ECI Id:"\\000032"

### GB2312 {#GB2312}
```
public static final int GB2312
```


Codificación GB2312 Conjunto de caracteres chino. ECI Id:"\\000029"

### GBK {#GBK}
```
public static final int GBK
```


Codificación GBK (extensión de GB2312 para chino simplificado). ECI Id:"\\000031"

### INVARIANT {#INVARIANT}
```
public static final int INVARIANT
```


Codificación ISO/IEC 646: conjunto de caracteres codificado ISO de 7 bits - conjunto de caracteres invariantes. ECI Id:"\\000170"

### ISO_8859_1 {#ISO-8859-1}
```
public static final int ISO_8859_1
```


Codificación ISO/IEC 8859-1 alfabeto latino n.º 1. ECI Id:"\\000003"

### ISO_8859_10 {#ISO-8859-10}
```
public static final int ISO_8859_10
```


Codificación ISO/IEC 8859-10 alfabeto latino n.º 6. ECI Id:"\\000012"

### ISO_8859_11 {#ISO-8859-11}
```
public static final int ISO_8859_11
```


Codificación ISO/IEC 8859-11 alfabeto latino/tailandés. ECI Id:"\\000013"

### ISO_8859_13 {#ISO-8859-13}
```
public static final int ISO_8859_13
```


Codificación ISO/IEC 8859-13 alfabeto latino n.º 7 (cinturón báltico). ECI Id:"\\000015"

### ISO_8859_14 {#ISO-8859-14}
```
public static final int ISO_8859_14
```


Codificación ISO/IEC 8859-14 alfabeto latino n.º 8 (célta). ECI Id:"\\000016"

### ISO_8859_15 {#ISO-8859-15}
```
public static final int ISO_8859_15
```


Codificación ISO/IEC 8859-15 alfabeto latino n.º 9. ECI Id:"\\000017"

### ISO_8859_16 {#ISO-8859-16}
```
public static final int ISO_8859_16
```


Codificación ISO/IEC 8859-16 alfabeto latino n.º 10. ECI Id:"\\000018"

### ISO_8859_2 {#ISO-8859-2}
```
public static final int ISO_8859_2
```


Codificación ISO/IEC 8859-2 alfabeto latino n.º 2. ECI Id:"\\000004"

### ISO_8859_3 {#ISO-8859-3}
```
public static final int ISO_8859_3
```


Codificación ISO/IEC 8859-3 alfabeto latino n.º 3. ECI Id:"\\000005"

### ISO_8859_4 {#ISO-8859-4}
```
public static final int ISO_8859_4
```


Codificación ISO/IEC 8859-4 alfabeto latino n.º 4. Id ECI:"\\000006"

### ISO_8859_5 {#ISO-8859-5}
```
public static final int ISO_8859_5
```


Codificación ISO/IEC 8859-5 alfabeto latino/cirílico. Id ECI:"\\000007"

### ISO_8859_6 {#ISO-8859-6}
```
public static final int ISO_8859_6
```


Codificación ISO/IEC 8859-6 alfabeto latino/árabe. Id ECI:"\\000008"

### ISO_8859_7 {#ISO-8859-7}
```
public static final int ISO_8859_7
```


Codificación ISO/IEC 8859-7 alfabeto latino/greco. Id ECI:"\\000009"

### ISO_8859_8 {#ISO-8859-8}
```
public static final int ISO_8859_8
```


Codificación ISO/IEC 8859-8 alfabeto latino/hebreo. Id ECI:"\\000010"

### ISO_8859_9 {#ISO-8859-9}
```
public static final int ISO_8859_9
```


Codificación ISO/IEC 8859-9 alfabeto latino n.º 5. Id ECI:"\\000011"

### NONE {#NONE}
```
public static final int NONE
```


No Extended Channel Interpretation/p>

### Shift_JIS {#Shift-JIS}
```
public static final int Shift_JIS
```


Codificación Shift JIS (JIS X 0208 Anexo 1 + JIS X 0201). Id ECI:"\\000020"

### US_ASCII {#US-ASCII}
```
public static final int US_ASCII
```


Codificación ISO/IEC 646:1991 Versión de referencia internacional del conjunto de caracteres codificado ISO de 7 bits. Id ECI:"\\000027"

### UTF16BE {#UTF16BE}
```
public static final int UTF16BE
```


Codificación ISO/IEC 10646 UCS-2 (byte de orden alto primero). Id ECI:"\\000025"

### UTF16LE {#UTF16LE}
```
public static final int UTF16LE
```


Codificación ISO/IEC 10646 UTF-16LE. Id ECI:"\\000033"

### UTF32BE {#UTF32BE}
```
public static final int UTF32BE
```


Codificación ISO/IEC 10646 UTF-32BE. Id ECI:"\\000034"

### UTF32LE {#UTF32LE}
```
public static final int UTF32LE
```


Codificación ISO/IEC 10646 UTF-32LE. Id ECI:"\\000035"

### UTF8 {#UTF8}
```
public static final int UTF8
```


Codificación ISO/IEC 10646 UTF-8. Id ECI:"\\000026"

### Win1250 {#Win1250}
```
public static final int Win1250
```


Codificación Windows 1250 Latin 2 (Europa Central). Id ECI:"\\000021"

### Win1251 {#Win1251}
```
public static final int Win1251
```


Codificación Windows 1251 cirílico. Id ECI:"\\000022"

### Win1252 {#Win1252}
```
public static final int Win1252
```


Codificación Windows 1252 Latin 1. Id ECI:"\\000023"

### Win1256 {#Win1256}
```
public static final int Win1256
```


Codificación Windows 1256 árabe. Id ECI:"\\000024"

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| eso | T |  |

### CloneTo(System.Enum that) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum that)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| eso | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type enumType, Object value, String format) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type enumType, Object value, String format)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valor | java.lang.Object |  |
| formato | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> enumType, long value, String format) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> enumType, long value, String format)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valor | largo |  |
| formato | java.lang.String |  |

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valor | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> enumType, long value) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valor | largo |  |

**Returns:**
java.lang.String
### getNames(System.Type enumType) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type enumType)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> enumType) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type enumType) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type enumType)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> enumType) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> enumType, String name) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> enumType, String name)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| nombre | java.lang.String |  |

**Returns:**
largo
### getValues(System.Type enumType) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type enumType)
```




**Parameters:**
| Parameter | Type | Descripción |
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
largo
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
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valor | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type enumType, String value) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type enumType, String value)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valor | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type enumType, long value) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type enumType, long value)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valor | largo |  |

**Returns:**
boolean
### isDefined(Class<?> enumType, long value) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valor | largo |  |

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valor | java.lang.String |  |

**Returns:**
largo
### parse(System.Type enumType, String value, Boolean ignoreCase) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valor | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
largo
### parse(Class<?> enumType, String value) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> enumType, String value)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valor | java.lang.String |  |

**Returns:**
largo
### parse(Class<?> enumType, String value, Boolean ignoreCase) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valor | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
largo
### register(System.Enum.AbstractEnum e) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum e)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| e | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type enumType, Object value) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type enumType, Object value)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valor | java.lang.Object |  |

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valor | largo |  |

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

