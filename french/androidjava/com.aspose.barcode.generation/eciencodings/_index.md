---
title: ECIEncodings
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Identifiants d'interprétation de canal étendu.
type: docs
weight: 37
url: /fr/androidjava/com.aspose.barcode.generation/eciencodings/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ECIEncodings extends System.Enum
```

Identifiants d'interprétation de canal étendu. Il est utilisé pour informer le lecteur de code-barres des détails concernant les références utilisées pour encoder les données dans le symbole.

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
## Champs

| Champ | Description |
| --- | --- |
| [BINARY](#BINARY) | Données binaires 8 bits. |
| [Big5](#Big5) | Encodage du jeu de caractères chinois Big 5 (Taïwan). |
| [EUC_KR](#EUC-KR) | Encodage du jeu de caractères coréen. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [GB18030](#GB18030) | Encodage du jeu de caractères chinois GGB18030. |
| [GB2312](#GB2312) | Encodage du jeu de caractères chinois GB2312. |
| [GBK](#GBK) | Encodage GBK (extension de GB2312 pour le chinois simplifié). |
| [INVARIANT](#INVARIANT) | ISO/IEC 646: jeu de caractères codé ISO 7 bits - encodage du jeu de caractères invariants. |
| [ISO_8859_1](#ISO-8859-1) | ISO/IEC 8859-1 alphabet latin n°. |
| [ISO_8859_10](#ISO-8859-10) | ISO/IEC 8859-10 alphabet latin n°. |
| [ISO_8859_11](#ISO-8859-11) | ISO/IEC 8859-11 encodage de l'alphabet latin/thai. |
| [ISO_8859_13](#ISO-8859-13) | ISO/IEC 8859-13 alphabet latin n°. |
| [ISO_8859_14](#ISO-8859-14) | ISO/IEC 8859-14 alphabet latin n°. |
| [ISO_8859_15](#ISO-8859-15) | ISO/IEC 8859-15 alphabet latin n°. |
| [ISO_8859_16](#ISO-8859-16) | ISO/IEC 8859-16 alphabet latin n°. |
| [ISO_8859_2](#ISO-8859-2) | ISO/IEC 8859-2 alphabet latin n°. |
| [ISO_8859_3](#ISO-8859-3) | ISO/IEC 8859-3 alphabet latin n°. |
| [ISO_8859_4](#ISO-8859-4) | ISO/IEC 8859-4 alphabet latin n°. |
| [ISO_8859_5](#ISO-8859-5) | Encodage de l'alphabet latin/cyrillique ISO/IEC 8859-5. |
| [ISO_8859_6](#ISO-8859-6) | Encodage de l'alphabet latin/arabe ISO/IEC 8859-6. |
| [ISO_8859_7](#ISO-8859-7) | Encodage de l'alphabet latin/grec ISO/IEC 8859-7. |
| [ISO_8859_8](#ISO-8859-8) | Encodage de l'alphabet latin/hébreu ISO/IEC 8859-8. |
| [ISO_8859_9](#ISO-8859-9) | ISO/IEC 8859-9 alphabet latin n°. |
| [NONE](#NONE) | Pas d'interprétation de canal étendue/p> |
| [Shift_JIS](#Shift-JIS) | Encodage Shift JIS (JIS X 0208 Annexe 1 + JIS X 0201). |
| [US_ASCII](#US-ASCII) | ISO/IEC 646:1991 version de référence internationale du jeu de caractères codé ISO 7 bits encodage. |
| [UTF16BE](#UTF16BE) | Encodage ISO/IEC 10646 UCS-2 (octet de poids fort en premier). |
| [UTF16LE](#UTF16LE) | Encodage ISO/IEC 10646 UTF-16LE. |
| [UTF32BE](#UTF32BE) | Encodage ISO/IEC 10646 UTF-32BE. |
| [UTF32LE](#UTF32LE) | Encodage ISO/IEC 10646 UTF-32LE. |
| [UTF8](#UTF8) | Encodage ISO/IEC 10646 UTF-8. |
| [Win1250](#Win1250) | Encodage Windows 1250 Latin 2 (Europe centrale). |
| [Win1251](#Win1251) | Encodage Windows 1251 cyrillique. |
| [Win1252](#Win1252) | Encodage Windows 1252 Latin 1. |
| [Win1256](#Win1256) | Encodage Windows 1256 arabe. |
## Méthodes

| Méthode | Description |
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


Données binaires 8 bits. ECI Id:"\\000899"

### Big5 {#Big5}
```
public static final int Big5
```


Encodage Big 5 (Taïwan) jeu de caractères chinois. ECI Id:"\\000028"

### EUC_KR {#EUC-KR}
```
public static final int EUC_KR
```


Encodage jeu de caractères coréen. ECI Id:"\\000030"

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### GB18030 {#GB18030}
```
public static final int GB18030
```


Encodage GGB18030 jeu de caractères chinois. ECI Id:"\\000032"

### GB2312 {#GB2312}
```
public static final int GB2312
```


Encodage GB2312 jeu de caractères chinois. ECI Id:"\\000029"

### GBK {#GBK}
```
public static final int GBK
```


Encodage GBK (extension de GB2312 pour le chinois simplifié). ECI Id:"\\000031"

### INVARIANT {#INVARIANT}
```
public static final int INVARIANT
```


Encodage ISO/IEC 646 : jeu de caractères codé ISO 7 bits - jeu de caractères invariants. ECI Id:"\\000170"

### ISO_8859_1 {#ISO-8859-1}
```
public static final int ISO_8859_1
```


Encodage ISO/IEC 8859-1 alphabet latin n° 1. ECI Id:"\\000003"

### ISO_8859_10 {#ISO-8859-10}
```
public static final int ISO_8859_10
```


Encodage ISO/IEC 8859-10 alphabet latin n° 6. ECI Id:"\\000012"

### ISO_8859_11 {#ISO-8859-11}
```
public static final int ISO_8859_11
```


Encodage ISO/IEC 8859-11 alphabet latin/thai. ECI Id:"\\000013"

### ISO_8859_13 {#ISO-8859-13}
```
public static final int ISO_8859_13
```


Encodage ISO/IEC 8859-13 alphabet latin n° 7 (bassin baltique). ECI Id:"\\000015"

### ISO_8859_14 {#ISO-8859-14}
```
public static final int ISO_8859_14
```


Encodage ISO/IEC 8859-14 alphabet latin n° 8 (celtique). ECI Id:"\\000016"

### ISO_8859_15 {#ISO-8859-15}
```
public static final int ISO_8859_15
```


Encodage ISO/IEC 8859-15 alphabet latin n° 9. ECI Id:"\\000017"

### ISO_8859_16 {#ISO-8859-16}
```
public static final int ISO_8859_16
```


Encodage ISO/IEC 8859-16 alphabet latin n° 10. ECI Id:"\\000018"

### ISO_8859_2 {#ISO-8859-2}
```
public static final int ISO_8859_2
```


Encodage ISO/IEC 8859-2 alphabet latin n° 2. ECI Id:"\\000004"

### ISO_8859_3 {#ISO-8859-3}
```
public static final int ISO_8859_3
```


Encodage ISO/IEC 8859-3 alphabet latin n° 3. ECI Id:"\\000005"

### ISO_8859_4 {#ISO-8859-4}
```
public static final int ISO_8859_4
```


ISO/IEC 8859-4 encodage de l'alphabet latin n° 4. ECI Id:"\\000006"

### ISO_8859_5 {#ISO-8859-5}
```
public static final int ISO_8859_5
```


ISO/IEC 8859-5 encodage de l'alphabet latin/cyrillique. ECI Id:"\\000007"

### ISO_8859_6 {#ISO-8859-6}
```
public static final int ISO_8859_6
```


ISO/IEC 8859-6 encodage de l'alphabet latin/arabe. ECI Id:"\\000008"

### ISO_8859_7 {#ISO-8859-7}
```
public static final int ISO_8859_7
```


ISO/IEC 8859-7 encodage de l'alphabet latin/grec. ECI Id:"\\000009"

### ISO_8859_8 {#ISO-8859-8}
```
public static final int ISO_8859_8
```


ISO/IEC 8859-8 encodage de l'alphabet latin/hebreu. ECI Id:"\\000010"

### ISO_8859_9 {#ISO-8859-9}
```
public static final int ISO_8859_9
```


ISO/IEC 8859-9 encodage de l'alphabet latin n° 5. ECI Id:"\\000011"

### NONE {#NONE}
```
public static final int NONE
```


Pas d'interprétation de canal étendue/p>

### Shift_JIS {#Shift-JIS}
```
public static final int Shift_JIS
```


Shift JIS (JIS X 0208 Annexe 1 + JIS X 0201) encodage. ECI Id:"\\000020"

### US_ASCII {#US-ASCII}
```
public static final int US_ASCII
```


ISO/IEC 646:1991 version de référence internationale du jeu de caractères codés ISO 7 bits encodage. ECI Id:"\\000027"

### UTF16BE {#UTF16BE}
```
public static final int UTF16BE
```


ISO/IEC 10646 UCS-2 (octet de poids fort en premier) encodage. ECI Id:"\\000025"

### UTF16LE {#UTF16LE}
```
public static final int UTF16LE
```


ISO/IEC 10646 encodage UTF-16LE. ECI Id:"\\000033"

### UTF32BE {#UTF32BE}
```
public static final int UTF32BE
```


ISO/IEC 10646 encodage UTF-32BE. ECI Id:"\\000034"

### UTF32LE {#UTF32LE}
```
public static final int UTF32LE
```


ISO/IEC 10646 encodage UTF-32LE. ECI Id:"\\000035"

### UTF8 {#UTF8}
```
public static final int UTF8
```


ISO/IEC 10646 encodage UTF-8. ECI Id:"\\000026"

### Win1250 {#Win1250}
```
public static final int Win1250
```


Windows 1250 Latin 2 (Europe centrale) encodage. ECI Id:"\\000021"

### Win1251 {#Win1251}
```
public static final int Win1251
```


Windows 1251 encodage cyrillique. ECI Id:"\\000022"

### Win1252 {#Win1252}
```
public static final int Win1252
```


Windows 1252 encodage Latin 1. ECI Id:"\\000023"

### Win1256 {#Win1256}
```
public static final int Win1256
```


Windows 1256 encodage arabe. ECI Id:"\\000024"

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
| Paramètre | Type | Description |
| --- | --- | --- |
| cela | T |  |

### CloneTo(System.Enum that) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cela | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type enumType, Object value, String format) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type enumType, Object value, String format)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valeur | java.lang.Object |  |
| format | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> enumType, long value, String format) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> enumType, long value, String format)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valeur | long |  |
| format | java.lang.String |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valeur | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> enumType, long value) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> enumType, long value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valeur | long |  |

**Returns:**
java.lang.String
### getNames(System.Type enumType) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type enumType)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> enumType) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> enumType)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type enumType) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type enumType)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> enumType) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> enumType)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> enumType, String name) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> enumType, String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| nom | java.lang.String |  |

**Returns:**
long
### getValues(System.Type enumType) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type enumType)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valeur | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type enumType, String value) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type enumType, String value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valeur | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type enumType, long value) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type enumType, long value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valeur | long |  |

**Returns:**
boolean
### isDefined(Class<?> enumType, long value) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> enumType, long value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valeur | long |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valeur | java.lang.String |  |

**Returns:**
long
### parse(System.Type enumType, String value, Boolean ignoreCase) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valeur | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> enumType, String value) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> enumType, String value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valeur | java.lang.String |  |

**Returns:**
long
### parse(Class<?> enumType, String value, Boolean ignoreCase) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valeur | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum e) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum e)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| e | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type enumType, Object value) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type enumType, Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| valeur | java.lang.Object |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| valeur | long |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

