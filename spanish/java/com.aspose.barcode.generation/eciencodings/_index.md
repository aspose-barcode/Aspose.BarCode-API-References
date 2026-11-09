---
title: "ECIEncodings"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Identificadores de Interpretación de Canal Extendido."
type: docs
weight: 35
url: /es/java/com.aspose.barcode.generation/eciencodings/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ECIEncodings extends System.Enum
```

Identificadores de Interpretación de Canal Extendido. Se utiliza para informar al lector de códigos de barras los detalles sobre las referencias usadas para codificar los datos en el símbolo.

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
## Campos

| Campo | Descripción |
| --- | --- |
| [BINARY](#BINARY) | Datos binarios de 8 bits. |
| [Big5](#Big5) | Codificación del conjunto de caracteres chino Big 5 (Taiwán). |
| [EUC_KR](#EUC-KR) | Codificación del conjunto de caracteres coreano. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [GB18030](#GB18030) | Codificación del conjunto de caracteres chino GGB18030. |
| [GB2312](#GB2312) | Codificación del conjunto de caracteres chino GB2312. |
| [GBK](#GBK) | Codificación GBK (extensión de GB2312 para chino simplificado). |
| [INVARIANT](#INVARIANT) | ISO/IEC 646: conjunto de caracteres codificado de 7 bits ISO - codificación del conjunto de caracteres invariantes. |
| [ISO_8859_1](#ISO-8859-1) | ISO/IEC 8859-1 alfabeto latino No. |
| [ISO_8859_10](#ISO-8859-10) | ISO/IEC 8859-10 alfabeto latino No. |
| [ISO_8859_11](#ISO-8859-11) | Codificación del alfabeto latino/tailandés ISO/IEC 8859-11. |
| [ISO_8859_13](#ISO-8859-13) | ISO/IEC 8859-13 alfabeto latino N.º. |
| [ISO_8859_14](#ISO-8859-14) | ISO/IEC 8859-14 alfabeto latino N.º. |
| [ISO_8859_15](#ISO-8859-15) | ISO/IEC 8859-15 alfabeto latino N.º. |
| [ISO_8859_16](#ISO-8859-16) | ISO/IEC 8859-16 alfabeto latino N.º. |
| [ISO_8859_2](#ISO-8859-2) | ISO/IEC 8859-2 alfabeto latino N.º. |
| [ISO_8859_3](#ISO-8859-3) | ISO/IEC 8859-3 alfabeto latino N.º. |
| [ISO_8859_4](#ISO-8859-4) | ISO/IEC 8859-4 alfabeto latino N.º. |
| [ISO_8859_5](#ISO-8859-5) | ISO/IEC 8859-5 codificación del alfabeto latino/cirílico. |
| [ISO_8859_6](#ISO-8859-6) | ISO/IEC 8859-6 codificación del alfabeto latino/árabe. |
| [ISO_8859_7](#ISO-8859-7) | ISO/IEC 8859-7 codificación del alfabeto latino/griego. |
| [ISO_8859_8](#ISO-8859-8) | ISO/IEC 8859-8 codificación del alfabeto latino/hebreo. |
| [ISO_8859_9](#ISO-8859-9) | ISO/IEC 8859-9 alfabeto latino N.º. |
| [NONE](#NONE) | Sin interpretación de canal extendida/p> |
| [Shift_JIS](#Shift-JIS) | Codificación Shift JIS (JIS X 0208 Anexo 1 + JIS X 0201). |
| [US_ASCII](#US-ASCII) | Codificación ISO/IEC 646:1991 Versión de referencia internacional del conjunto de caracteres codificado de 7 bits ISO. |
| [UTF16BE](#UTF16BE) | Codificación ISO/IEC 10646 UCS-2 (byte de orden alto primero). |
| [UTF16LE](#UTF16LE) | Codificación ISO/IEC 10646 UTF-16LE. |
| [UTF32BE](#UTF32BE) | Codificación ISO/IEC 10646 UTF-32BE. |
| [UTF32LE](#UTF32LE) | Codificación ISO/IEC 10646 UTF-32LE. |
| [UTF8](#UTF8) | Codificación ISO/IEC 10646 UTF-8. |
| [Win1250](#Win1250) | Codificación Windows 1250 Latin 2 (Europa Central). |
| [Win1251](#Win1251) | Codificación Windows 1251 Cirílico. |
| [Win1252](#Win1252) | Codificación Windows 1252 Latin 1. |
| [Win1256](#Win1256) | Codificación Windows 1256 Árabe. |
## Métodos

| Método | Descripción |
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


Datos binarios de 8 bits. ECI Id:"\\000899"

### Big5 {#Big5}
```
public static final int Big5
```


Codificación del conjunto de caracteres chino Big 5 (Taiwan). ECI Id:"\\000028"

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


Codificación del conjunto de caracteres chino GGB18030. ECI Id:"\\000032"

### GB2312 {#GB2312}
```
public static final int GB2312
```


Codificación del conjunto de caracteres chino GB2312. ECI Id:"\\000029"

### GBK {#GBK}
```
public static final int GBK
```


Codificación GBK (extensión de GB2312 para chino simplificado). ECI Id:"\\000031"

### INVARIANT {#INVARIANT}
```
public static final int INVARIANT
```


ISO/IEC 646: conjunto de caracteres codificado ISO de 7 bits - codificación del conjunto de caracteres invariantes. ECI Id:"\\000170"

### ISO_8859_1 {#ISO-8859-1}
```
public static final int ISO_8859_1
```


Codificación del alfabeto latino n.º 1 ISO/IEC 8859-1. ECI Id:"\\000003"

### ISO_8859_10 {#ISO-8859-10}
```
public static final int ISO_8859_10
```


Codificación del alfabeto latino n.º 6 ISO/IEC 8859-10. ECI Id:"\\000012"

### ISO_8859_11 {#ISO-8859-11}
```
public static final int ISO_8859_11
```


Codificación del alfabeto latino/tailandés ISO/IEC 8859-11. ECI Id:"\\000013"

### ISO_8859_13 {#ISO-8859-13}
```
public static final int ISO_8859_13
```


Codificación del alfabeto latino n.º 7 (Ribera del Báltico) ISO/IEC 8859-13. ECI Id:"\\000015"

### ISO_8859_14 {#ISO-8859-14}
```
public static final int ISO_8859_14
```


Codificación del alfabeto latino n.º 8 (Céltico) ISO/IEC 8859-14. ECI Id:"\\000016"

### ISO_8859_15 {#ISO-8859-15}
```
public static final int ISO_8859_15
```


Codificación del alfabeto latino n.º 9 ISO/IEC 8859-15. ECI Id:"\\000017"

### ISO_8859_16 {#ISO-8859-16}
```
public static final int ISO_8859_16
```


Codificación del alfabeto latino n.º 10 ISO/IEC 8859-16. ECI Id:"\\000018"

### ISO_8859_2 {#ISO-8859-2}
```
public static final int ISO_8859_2
```


Codificación del alfabeto latino n.º 2 ISO/IEC 8859-2. ECI Id:"\\000004"

### ISO_8859_3 {#ISO-8859-3}
```
public static final int ISO_8859_3
```


Codificación del alfabeto latino n.º 3 ISO/IEC 8859-3. ECI Id:"\\000005"

### ISO_8859_4 {#ISO-8859-4}
```
public static final int ISO_8859_4
```


Codificación del alfabeto latino n.º 4 ISO/IEC 8859-4. ECI Id:"\\000006"

### ISO_8859_5 {#ISO-8859-5}
```
public static final int ISO_8859_5
```


Codificación del alfabeto latino/cirílico ISO/IEC 8859-5. ECI Id:"\\000007"

### ISO_8859_6 {#ISO-8859-6}
```
public static final int ISO_8859_6
```


Codificación del alfabeto latino/árabe ISO/IEC 8859-6. ECI Id:"\\000008"

### ISO_8859_7 {#ISO-8859-7}
```
public static final int ISO_8859_7
```


Codificación del alfabeto latino/greco ISO/IEC 8859-7. ECI Id:"\\000009"

### ISO_8859_8 {#ISO-8859-8}
```
public static final int ISO_8859_8
```


Codificación del alfabeto latino/hebreo ISO/IEC 8859-8. ECI Id:"\\000010"

### ISO_8859_9 {#ISO-8859-9}
```
public static final int ISO_8859_9
```


Codificación del alfabeto latino n.º 5 ISO/IEC 8859-9. ECI Id:"\\000011"

### NONE {#NONE}
```
public static final int NONE
```


Sin interpretación de canal extendida/p>

### Shift_JIS {#Shift-JIS}
```
public static final int Shift_JIS
```


Codificación Shift JIS (Anexo 1 JIS X 0208 + JIS X 0201). ECI Id:"\\000020"

### US_ASCII {#US-ASCII}
```
public static final int US_ASCII
```


ISO/IEC 646:1991 Versión de referencia internacional del conjunto de caracteres codificado ISO de 7 bits. ECI Id:"\\000027"

### UTF16BE {#UTF16BE}
```
public static final int UTF16BE
```


Codificación UCS-2 (byte de orden alto primero) ISO/IEC 10646. ECI Id:"\\000025"

### UTF16LE {#UTF16LE}
```
public static final int UTF16LE
```


Codificación UTF-16LE ISO/IEC 10646. ECI Id:"\\000033"

### UTF32BE {#UTF32BE}
```
public static final int UTF32BE
```


Codificación ISO/IEC 10646 UTF-32BE. ID ECI:"\\000034"

### UTF32LE {#UTF32LE}
```
public static final int UTF32LE
```


Codificación ISO/IEC 10646 UTF-32LE. ID ECI:"\\000035"

### UTF8 {#UTF8}
```
public static final int UTF8
```


Codificación ISO/IEC 10646 UTF-8. ID ECI:"\\000026"

### Win1250 {#Win1250}
```
public static final int Win1250
```


Codificación Windows 1250 Latin 2 (Europa Central). ID ECI:"\\000021"

### Win1251 {#Win1251}
```
public static final int Win1251
```


Codificación Windows 1251 Cirilí. ID ECI:"\\000022"

### Win1252 {#Win1252}
```
public static final int Win1252
```


Codificación Windows 1252 Latin 1. ID ECI:"\\000023"

### Win1256 {#Win1256}
```
public static final int Win1256
```


Codificación Windows 1256 Árabe. ID ECI:"\\000024"

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

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
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

