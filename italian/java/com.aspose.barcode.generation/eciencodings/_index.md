---
title: "ECIEncodings"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Identificatori di Interpretazione del Canale Esteso."
type: docs
weight: 35
url: /it/java/com.aspose.barcode.generation/eciencodings/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ECIEncodings extends System.Enum
```

Extended Channel Interpretation Identifiers. Viene utilizzato per informare il lettore di codici a barre sui dettagli delle referenze utilizzate per codificare i dati nel simbolo.

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
## Campi

| Campo | Descrizione |
| --- | --- |
| [BINARY](#BINARY) | Dati binari a 8 bit. |
| [Big5](#Big5) | Codifica del set di caratteri cinese Big 5 (Taiwan). |
| [EUC_KR](#EUC-KR) | Codifica del set di caratteri coreano. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [GB18030](#GB18030) | Codifica del set di caratteri cinese GGB18030. |
| [GB2312](#GB2312) | Codifica del set di caratteri cinese GB2312. |
| [GBK](#GBK) | Codifica GBK (estensione di GB2312 per il cinese semplificato). |
| [INVARIANT](#INVARIANT) | ISO/IEC 646: set di caratteri codificato a 7 bit ISO - codifica del set di caratteri invarianti. |
| [ISO_8859_1](#ISO-8859-1) | ISO/IEC 8859-1 alfabeto latino n. |
| [ISO_8859_10](#ISO-8859-10) | ISO/IEC 8859-10 alfabeto latino n. |
| [ISO_8859_11](#ISO-8859-11) | Codifica dell'alfabeto latino/Thai ISO/IEC 8859-11. |
| [ISO_8859_13](#ISO-8859-13) | ISO/IEC 8859-13 alfabeto latino No. |
| [ISO_8859_14](#ISO-8859-14) | ISO/IEC 8859-14 alfabeto latino No. |
| [ISO_8859_15](#ISO-8859-15) | ISO/IEC 8859-15 alfabeto latino No. |
| [ISO_8859_16](#ISO-8859-16) | ISO/IEC 8859-16 alfabeto latino No. |
| [ISO_8859_2](#ISO-8859-2) | ISO/IEC 8859-2 alfabeto latino No. |
| [ISO_8859_3](#ISO-8859-3) | ISO/IEC 8859-3 alfabeto latino No. |
| [ISO_8859_4](#ISO-8859-4) | ISO/IEC 8859-4 alfabeto latino No. |
| [ISO_8859_5](#ISO-8859-5) | ISO/IEC 8859-5 codifica alfabeto latino/cirillico. |
| [ISO_8859_6](#ISO-8859-6) | ISO/IEC 8859-6 codifica alfabeto latino/arabo. |
| [ISO_8859_7](#ISO-8859-7) | ISO/IEC 8859-7 codifica alfabeto latino/greco. |
| [ISO_8859_8](#ISO-8859-8) | ISO/IEC 8859-8 codifica alfabeto latino/ebraico. |
| [ISO_8859_9](#ISO-8859-9) | ISO/IEC 8859-9 alfabeto latino No. |
| [NONE](#NONE) | Nessuna interpretazione estesa del canale/p> |
| [Shift_JIS](#Shift-JIS) | Shift JIS (JIS X 0208 Allegato 1 + JIS X 0201) codifica. |
| [US_ASCII](#US-ASCII) | ISO/IEC 646:1991 versione di riferimento internazionale della codifica del set di caratteri a 7 bit ISO. |
| [UTF16BE](#UTF16BE) | ISO/IEC 10646 UCS-2 (byte di ordine più alto per primo) codifica. |
| [UTF16LE](#UTF16LE) | ISO/IEC 10646 codifica UTF-16LE. |
| [UTF32BE](#UTF32BE) | ISO/IEC 10646 codifica UTF-32BE. |
| [UTF32LE](#UTF32LE) | ISO/IEC 10646 codifica UTF-32LE. |
| [UTF8](#UTF8) | ISO/IEC 10646 codifica UTF-8. |
| [Win1250](#Win1250) | Windows 1250 latino 2 (Europa centrale) codifica. |
| [Win1251](#Win1251) | Windows 1251 codifica cirillica. |
| [Win1252](#Win1252) | Windows 1252 codifica latino 1. |
| [Win1256](#Win1256) | Windows 1256 codifica araba. |
## Metodi

| Metodo | Descrizione |
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


Dati binari a 8 bit. ID ECI:"\\000899"

### Big5 {#Big5}
```
public static final int Big5
```


Codifica del set di caratteri cinese Big 5 (Taiwan). ECI Id:"\\000028"

### EUC_KR {#EUC-KR}
```
public static final int EUC_KR
```


Codifica del set di caratteri coreano. ECI Id:"\\000030"

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### GB18030 {#GB18030}
```
public static final int GB18030
```


Codifica del set di caratteri cinese GGB18030. ECI Id:"\\000032"

### GB2312 {#GB2312}
```
public static final int GB2312
```


Codifica del set di caratteri cinese GB2312. ECI Id:"\\000029"

### GBK {#GBK}
```
public static final int GBK
```


Codifica GBK (estensione di GB2312 per il cinese semplificato). ECI Id:"\\000031"

### INVARIANT {#INVARIANT}
```
public static final int INVARIANT
```


ISO/IEC 646: set di caratteri codificato a 7 bit ISO - codifica del set di caratteri invarianti. ECI Id:"\\000170"

### ISO_8859_1 {#ISO-8859-1}
```
public static final int ISO_8859_1
```


Codifica ISO/IEC 8859-1 alfabeto latino n. 1. ECI Id:"\\000003"

### ISO_8859_10 {#ISO-8859-10}
```
public static final int ISO_8859_10
```


Codifica ISO/IEC 8859-10 alfabeto latino n. 6. ECI Id:"\\000012"

### ISO_8859_11 {#ISO-8859-11}
```
public static final int ISO_8859_11
```


Codifica ISO/IEC 8859-11 alfabeto latino/thailandese. ECI Id:"\\000013"

### ISO_8859_13 {#ISO-8859-13}
```
public static final int ISO_8859_13
```


Codifica ISO/IEC 8859-13 alfabeto latino n. 7 (Bordo baltico). ECI Id:"\\000015"

### ISO_8859_14 {#ISO-8859-14}
```
public static final int ISO_8859_14
```


Codifica ISO/IEC 8859-14 alfabeto latino n. 8 (Celtico). ECI Id:"\\000016"

### ISO_8859_15 {#ISO-8859-15}
```
public static final int ISO_8859_15
```


Codifica ISO/IEC 8859-15 alfabeto latino n. 9. ECI Id:"\\000017"

### ISO_8859_16 {#ISO-8859-16}
```
public static final int ISO_8859_16
```


Codifica ISO/IEC 8859-16 alfabeto latino n. 10. ECI Id:"\\000018"

### ISO_8859_2 {#ISO-8859-2}
```
public static final int ISO_8859_2
```


Codifica ISO/IEC 8859-2 alfabeto latino n. 2. ECI Id:"\\000004"

### ISO_8859_3 {#ISO-8859-3}
```
public static final int ISO_8859_3
```


Codifica ISO/IEC 8859-3 alfabeto latino n. 3. ECI Id:"\\000005"

### ISO_8859_4 {#ISO-8859-4}
```
public static final int ISO_8859_4
```


Codifica ISO/IEC 8859-4 alfabeto latino n. 4. ECI Id:"\\000006"

### ISO_8859_5 {#ISO-8859-5}
```
public static final int ISO_8859_5
```


Codifica ISO/IEC 8859-5 alfabeto latino/cirillico. ECI Id:"\\000007"

### ISO_8859_6 {#ISO-8859-6}
```
public static final int ISO_8859_6
```


Codifica ISO/IEC 8859-6 alfabeto latino/arabo. ECI Id:"\\000008"

### ISO_8859_7 {#ISO-8859-7}
```
public static final int ISO_8859_7
```


Codifica ISO/IEC 8859-7 alfabeto latino/greco. ECI Id:"\\000009"

### ISO_8859_8 {#ISO-8859-8}
```
public static final int ISO_8859_8
```


Codifica ISO/IEC 8859-8 alfabeto latino/ebraico. ECI Id:"\\000010"

### ISO_8859_9 {#ISO-8859-9}
```
public static final int ISO_8859_9
```


Codifica ISO/IEC 8859-9 alfabeto latino n. 5. ECI Id:"\\000011"

### NONE {#NONE}
```
public static final int NONE
```


Nessuna interpretazione estesa del canale/p>

### Shift_JIS {#Shift-JIS}
```
public static final int Shift_JIS
```


Codifica Shift JIS (JIS X 0208 Allegato 1 + JIS X 0201). ECI Id:"\\000020"

### US_ASCII {#US-ASCII}
```
public static final int US_ASCII
```


ISO/IEC 646:1991 Versione di riferimento internazionale del set di caratteri codificato a 7 bit ISO. ECI Id:"\\000027"

### UTF16BE {#UTF16BE}
```
public static final int UTF16BE
```


Codifica ISO/IEC 10646 UCS-2 (byte di ordine più alto per primo). ECI Id:"\\000025"

### UTF16LE {#UTF16LE}
```
public static final int UTF16LE
```


Codifica ISO/IEC 10646 UTF-16LE. ECI Id:"\\000033"

### UTF32BE {#UTF32BE}
```
public static final int UTF32BE
```


Codifica ISO/IEC 10646 UTF-32BE. ID ECI:"\\000034"

### UTF32LE {#UTF32LE}
```
public static final int UTF32LE
```


Codifica ISO/IEC 10646 UTF-32LE. ID ECI:"\\000035"

### UTF8 {#UTF8}
```
public static final int UTF8
```


Codifica ISO/IEC 10646 UTF-8. ID ECI:"\\000026"

### Win1250 {#Win1250}
```
public static final int Win1250
```


Codifica Windows 1250 Latin 2 (Europa Centrale). ID ECI:"\\000021"

### Win1251 {#Win1251}
```
public static final int Win1251
```


Codifica Windows 1251 Cirillico. ID ECI:"\\000022"

### Win1252 {#Win1252}
```
public static final int Win1252
```


Codifica Windows 1252 Latin 1. ID ECI:"\\000023"

### Win1256 {#Win1256}
```
public static final int Win1256
```


Codifica Windows 1256 Arabo. ID ECI:"\\000024"

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

