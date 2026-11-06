---
title: "ECIEncodings"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού."
type: docs
weight: 36
url: /el/androidjava/com.aspose.barcode.generation/eciencodings/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ECIEncodings extends System.Enum
```

Extended Channel Interpretation Identifiers. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο.

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
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [BINARY](#BINARY) | Δεδομένα δυαδικά 8-bit. |
| [Big5](#Big5) | Κωδικοποίηση συνόλου χαρακτήρων Big 5 (Ταϊβάν) Chinese. |
| [EUC_KR](#EUC-KR) | Κωδικοποίηση συνόλου χαρακτήρων Korean. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [GB18030](#GB18030) | Κωδικοποίηση συνόλου χαρακτήρων GGB18030 Chinese. |
| [GB2312](#GB2312) | Κωδικοποίηση συνόλου χαρακτήρων GB2312 Chinese. |
| [GBK](#GBK) | Κωδικοποίηση GBK (επέκταση του GB2312 για Απλοποιημένα Κινέζικα). |
| [INVARIANT](#INVARIANT) | ISO/IEC 646: ISO 7-bit κωδικοποιημένο σύνολο χαρακτήρων - Κωδικοποίηση αμετάβλητου συνόλου χαρακτήρων. |
| [ISO_8859_1](#ISO-8859-1) | ISO/IEC 8859-1 Λατινικό αλφάβητο Νο. |
| [ISO_8859_10](#ISO-8859-10) | ISO/IEC 8859-10 Λατινικό αλφάβητο Νο. |
| [ISO_8859_11](#ISO-8859-11) | ISO/IEC 8859-11 Κωδικοποίηση λατινικού/Ταϊλανδικού αλφαβήτου. |
| [ISO_8859_13](#ISO-8859-13) | ISO/IEC 8859-13 Λατινικό αλφάβητο Νο. |
| [ISO_8859_14](#ISO-8859-14) | ISO/IEC 8859-14 Λατινικό αλφάβητο Νο. |
| [ISO_8859_15](#ISO-8859-15) | ISO/IEC 8859-15 Λατινικό αλφάβητο Νο. |
| [ISO_8859_16](#ISO-8859-16) | ISO/IEC 8859-16 Λατινικό αλφάβητο Νο. |
| [ISO_8859_2](#ISO-8859-2) | ISO/IEC 8859-2 Λατινικό αλφάβητο No. |
| [ISO_8859_3](#ISO-8859-3) | ISO/IEC 8859-3 Λατινικό αλφάβητο No. |
| [ISO_8859_4](#ISO-8859-4) | ISO/IEC 8859-4 Λατινικό αλφάβητο No. |
| [ISO_8859_5](#ISO-8859-5) | ISO/IEC 8859-5 Κωδικοποίηση λατινικού/κυριλλικού αλφαβήτου. |
| [ISO_8859_6](#ISO-8859-6) | ISO/IEC 8859-6 Κωδικοποίηση λατινικού/αραβικού αλφαβήτου. |
| [ISO_8859_7](#ISO-8859-7) | ISO/IEC 8859-7 Κωδικοποίηση λατινικού/ελληνικού αλφαβήτου. |
| [ISO_8859_8](#ISO-8859-8) | ISO/IEC 8859-8 Κωδικοποίηση λατινικού/εβραϊκού αλφαβήτου. |
| [ISO_8859_9](#ISO-8859-9) | ISO/IEC 8859-9 Λατινικό αλφάβητο No. |
| [NONE](#NONE) | Καμία εκτεταμένη ερμηνεία καναλιού/p> |
| [Shift_JIS](#Shift-JIS) | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) κωδικοποίηση. |
| [US_ASCII](#US-ASCII) | ISO/IEC 646:1991 Διεθνής αναφορά έκδοση του 7-bit κωδικοποιημένου συνόλου χαρακτήρων ISO. |
| [UTF16BE](#UTF16BE) | ISO/IEC 10646 UCS-2 (High order byte first) κωδικοποίηση. |
| [UTF16LE](#UTF16LE) | ISO/IEC 10646 UTF-16LE κωδικοποίηση. |
| [UTF32BE](#UTF32BE) | ISO/IEC 10646 UTF-32BE κωδικοποίηση. |
| [UTF32LE](#UTF32LE) | ISO/IEC 10646 UTF-32LE κωδικοποίηση. |
| [UTF8](#UTF8) | ISO/IEC 10646 UTF-8 κωδικοποίηση. |
| [Win1250](#Win1250) | Windows 1250 Λατινικό 2 (Κεντρική Ευρώπη) κωδικοποίηση. |
| [Win1251](#Win1251) | Windows 1251 Κυριλλική κωδικοποίηση. |
| [Win1252](#Win1252) | Windows 1252 Λατινικό 1 κωδικοποίηση. |
| [Win1256](#Win1256) | Windows 1256 Αραβική κωδικοποίηση. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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


Δεκαοκτά-bit δυαδικά δεδομένα. ECI Id:"\000899"

### Big5 {#Big5}
```
public static final int Big5
```


Big 5 (Taiwan) Κωδικοποίηση κινεζικού συνόλου χαρακτήρων. ECI Id:"\000028"

### EUC_KR {#EUC-KR}
```
public static final int EUC_KR
```


Κωδικοποίηση κορεατικού συνόλου χαρακτήρων. ECI Id:"\000030"

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### GB18030 {#GB18030}
```
public static final int GB18030
```


GGB18030 Κωδικοποίηση κινεζικού συνόλου χαρακτήρων. ECI Id:"\000032"

### GB2312 {#GB2312}
```
public static final int GB2312
```


GB2312 Κωδικοποίηση κινεζικού συνόλου χαρακτήρων. ECI Id:"\000029"

### GBK {#GBK}
```
public static final int GBK
```


GBK (επέκταση του GB2312 για Απλοποιημένα Κινέζικα) κωδικοποίηση. ECI Id:"\\000031"

### INVARIANT {#INVARIANT}
```
public static final int INVARIANT
```


ISO/IEC 646: σύνολο κωδικοποιημένων χαρακτήρων ISO 7-bit - κωδικοποίηση αμετάβλητου συνόλου χαρακτήρων. ECI Id:"\\000170"

### ISO_8859_1 {#ISO-8859-1}
```
public static final int ISO_8859_1
```


ISO/IEC 8859-1 κωδικοποίηση λατινικού αλφαβήτου αριθ. 1. ECI Id:"\\000003"

### ISO_8859_10 {#ISO-8859-10}
```
public static final int ISO_8859_10
```


ISO/IEC 8859-10 κωδικοποίηση λατινικού αλφαβήτου αριθ. 6. ECI Id:"\\000012"

### ISO_8859_11 {#ISO-8859-11}
```
public static final int ISO_8859_11
```


ISO/IEC 8859-11 κωδικοποίηση λατινικού/ταϊλανδικού αλφαβήτου. ECI Id:"\\000013"

### ISO_8859_13 {#ISO-8859-13}
```
public static final int ISO_8859_13
```


ISO/IEC 8859-13 κωδικοποίηση λατινικού αλφαβήτου αριθ. 7 (Βαλτική περιοχή). ECI Id:"\\000015"

### ISO_8859_14 {#ISO-8859-14}
```
public static final int ISO_8859_14
```


ISO/IEC 8859-14 κωδικοποίηση λατινικού αλφαβήτου αριθ. 8 (Κέλτικα). ECI Id:"\\000016"

### ISO_8859_15 {#ISO-8859-15}
```
public static final int ISO_8859_15
```


ISO/IEC 8859-15 κωδικοποίηση λατινικού αλφαβήτου αριθ. 9. ECI Id:"\\000017"

### ISO_8859_16 {#ISO-8859-16}
```
public static final int ISO_8859_16
```


ISO/IEC 8859-16 κωδικοποίηση λατινικού αλφαβήτου αριθ. 10. ECI Id:"\\000018"

### ISO_8859_2 {#ISO-8859-2}
```
public static final int ISO_8859_2
```


ISO/IEC 8859-2 κωδικοποίηση λατινικού αλφαβήτου αριθ. 2. ECI Id:"\\000004"

### ISO_8859_3 {#ISO-8859-3}
```
public static final int ISO_8859_3
```


ISO/IEC 8859-3 κωδικοποίηση λατινικού αλφαβήτου αριθ. 3. ECI Id:"\\000005"

### ISO_8859_4 {#ISO-8859-4}
```
public static final int ISO_8859_4
```


ISO/IEC 8859-4 κωδικοποίηση λατινικού αλφαβήτου αριθ. 4. ECI Id:"\\000006"

### ISO_8859_5 {#ISO-8859-5}
```
public static final int ISO_8859_5
```


ISO/IEC 8859-5 κωδικοποίηση λατινικού/κυριλλικού αλφαβήτου. ECI Id:"\\000007"

### ISO_8859_6 {#ISO-8859-6}
```
public static final int ISO_8859_6
```


ISO/IEC 8859-6 κωδικοποίηση λατινικού/αραβικού αλφαβήτου. ECI Id:"\\000008"

### ISO_8859_7 {#ISO-8859-7}
```
public static final int ISO_8859_7
```


ISO/IEC 8859-7 κωδικοποίηση λατινικού/ελληνικού αλφαβήτου. ECI Id:"\\000009"

### ISO_8859_8 {#ISO-8859-8}
```
public static final int ISO_8859_8
```


ISO/IEC 8859-8 κωδικοποίηση λατινικού/εβραϊκού αλφαβήτου. ECI Id:"\\000010"

### ISO_8859_9 {#ISO-8859-9}
```
public static final int ISO_8859_9
```


ISO/IEC 8859-9 κωδικοποίηση λατινικού αλφαβήτου αριθ. 5. ECI Id:"\\000011"

### NONE {#NONE}
```
public static final int NONE
```


Καμία εκτεταμένη ερμηνεία καναλιού/p>

### Shift_JIS {#Shift-JIS}
```
public static final int Shift_JIS
```


Shift JIS (JIS X 0208 Παράρτημα 1 + JIS X 0201) κωδικοποίηση. ECI Id:"\\000020"

### US_ASCII {#US-ASCII}
```
public static final int US_ASCII
```


ISO/IEC 646:1991 Διεθνής Αναφορά Έκδοσης του ISO 7-bit συνόλου κωδικοποιημένων χαρακτήρων κωδικοποίηση. ECI Id:"\\000027"

### UTF16BE {#UTF16BE}
```
public static final int UTF16BE
```


ISO/IEC 10646 UCS-2 (Πρώτο το υψηλότερο byte) κωδικοποίηση. ECI Id:"\\000025"

### UTF16LE {#UTF16LE}
```
public static final int UTF16LE
```


ISO/IEC 10646 κωδικοποίηση UTF-16LE. ECI Id:"\\000033"

### UTF32BE {#UTF32BE}
```
public static final int UTF32BE
```


ISO/IEC 10646 κωδικοποίηση UTF-32BE. ECI Id:"\\000034"

### UTF32LE {#UTF32LE}
```
public static final int UTF32LE
```


ISO/IEC 10646 κωδικοποίηση UTF-32LE. ECI Id:"\\000035"

### UTF8 {#UTF8}
```
public static final int UTF8
```


ISO/IEC 10646 κωδικοποίηση UTF-8. ECI Id:"\\000026"

### Win1250 {#Win1250}
```
public static final int Win1250
```


Windows 1250 Λατινικό 2 (Κεντρική Ευρώπη) κωδικοποίηση. ECI Id:"\\000021"

### Win1251 {#Win1251}
```
public static final int Win1251
```


Windows 1251 Κιριλλική κωδικοποίηση. ECI Id:"\\000022"

### Win1252 {#Win1252}
```
public static final int Win1252
```


Windows 1252 Latin 1 κωδικοποίηση. ECI Id:"\\000023"

### Win1256 {#Win1256}
```
public static final int Win1256
```


Windows 1256 Αραβική κωδικοποίηση. ECI Id:"\\000024"

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αυτό | T |  |

### CloneTo(System.Enum that) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αυτό | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type enumType, Object value, String format) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type enumType, Object value, String format)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| τιμή | java.lang.Object |  |
| μορφή | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> enumType, long value, String format) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> enumType, long value, String format)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| τιμή | long |  |
| μορφή | java.lang.String |  |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| τιμή | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> enumType, long value) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> enumType, long value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| τιμή | long |  |

**Returns:**
java.lang.String
### getNames(System.Type enumType) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type enumType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> enumType) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> enumType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type enumType) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type enumType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> enumType) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> enumType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> enumType, String name) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> enumType, String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| name | java.lang.String |  |

**Returns:**
long
### getValues(System.Type enumType) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type enumType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type enumType, String value) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type enumType, String value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| τιμή | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type enumType, long value) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type enumType, long value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| τιμή | long |  |

**Returns:**
boolean
### isDefined(Class<?> enumType, long value) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> enumType, long value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| τιμή | long |  |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| τιμή | java.lang.String |  |

**Returns:**
long
### parse(System.Type enumType, String value, Boolean ignoreCase) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| τιμή | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> enumType, String value) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> enumType, String value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| τιμή | java.lang.String |  |

**Returns:**
long
### parse(Class<?> enumType, String value, Boolean ignoreCase) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| τιμή | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum e) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum e)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| e | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type enumType, Object value) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type enumType, Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| τιμή | java.lang.Object |  |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| τιμή | long |  |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

