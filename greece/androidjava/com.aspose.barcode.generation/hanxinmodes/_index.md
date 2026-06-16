---
title: HanXinModes
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Λειτουργία κωδικοποίησης Han Xin Code.
type: docs
weight: 91
url: /el/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Λειτουργία κωδικοποίησης Han Xin Code. Συνιστάται η χρήση Auto με χαρακτήρες ASCII / Κινέζικους ή Unicode για χαρακτήρες Unicode.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [AUTO](#AUTO) | Ακολουθία των λειτουργιών Numeric, Text, ECI, Binary Bytes και 4 GB18030 που αλλάζει αυτόματα. |
| [BINARY](#BINARY) | Η λειτουργία Binary byte κωδικοποιεί δυαδικά δεδομένα σε οποιαδήποτε μορφή και τα κωδικοποιεί στο δυαδικό byte τους. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Κάθε κοινός Κινέζικος χαρακτήρας στην Περιοχή Ένα αντιπροσωπεύεται με 12 bits. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Κάθε κοινός Κινέζικος χαρακτήρας στην Περιοχή Δύο αντιπροσωπεύεται με 12 bits. |
| [ECI](#ECI) | Λειτουργία Extended Channel Interpretation (ECI) |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Κάθε χαρακτήρας της περιοχής GB18030 4-byte αντιπροσωπεύεται με 21 bits. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Κάθε χαρακτήρας της περιοχής GB18030 2-byte αντιπροσωπεύεται με 15 bits. |
| [GS_1](#GS-1) | Η λειτουργία GS1 υποδεικνύει ότι τα δεδομένα που αντιπροσωπεύονται στο Han Xin Code είναι δεδομένα GS1 του συστήματος GS1 που ορίζονται από το GS1 General Specification. |
| [NUMERIC](#NUMERIC) | Η λειτουργία Numeric κωδικοποιεί δεδομένα από το σύνολο δεκαδικών ψηφίων (ψηφία 0-9, τιμές byte 30HEX έως 39HEX). |
| [TEXT](#TEXT) | Η λειτουργία Text κωδικοποιεί δεδομένα από κοινά σύμβολα που ορίζονται στο ISO/IEC 646, δηλαδή. |
| [UNICODE](#UNICODE) | Η λειτουργία Unicode σχεδιάζει έναν τρόπο για την αναπαράσταση οποιουδήποτε κειμενικού δεδομένου που αναφέρεται στην κωδικοποίηση/σύνολο χαρακτήρων UTF8 στο Han Xin Code. |
| [URI](#URI) | Η λειτουργία URI υποδεικνύει ότι τα δεδομένα που αντιπροσωπεύονται στο Han Xin Code είναι αναφορά Uniform Resource Identifier (URI) στο RFC 3986. |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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


Ακολουθία των λειτουργιών Numeric, Text, ECI, Binary Bytes και 4 GB18030 που αλλάζει αυτόματα.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Η λειτουργία Binary byte κωδικοποιεί δυαδικά δεδομένα σε οποιαδήποτε μορφή και τα κωδικοποιεί στο δυαδικό byte τους. Κάθε byte στη λειτουργία Binary Byte αντιπροσωπεύεται με 8 bits.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Κάθε κοινός Κινέζικος χαρακτήρας στην Περιοχή Ένα αντιπροσωπεύεται με 12 bits. Οι κοινοί Κινέζικοί χαρακτήρες στην Περιοχή Ένα περιλαμβάνουν χαρακτήρες των οποίων η πρώτη τιμή byte βρίσκεται στο εύρος B0HEX έως D7HEX και η δεύτερη τιμή byte στο εύρος A1HEX έως FEHEX (3760 χαρακτήρες), καθώς και χαρακτήρες των οποίων η πρώτη τιμή byte βρίσκεται στο εύρος A1HEX έως A3HEX και η δεύτερη τιμή byte στο εύρος A1HEX έως FEHEX (282 χαρακτήρες), και χαρακτήρες των οποίων οι τιμές byte βρίσκονται στο εύρος A8A1HEX έως A8C0HEX (32 χαρακτήρες).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Κάθε κοινός Κινέζικος χαρακτήρας στην Περιοχή Δύο αντιπροσωπεύεται με 12 bits. Οι κοινοί Κινέζικοί χαρακτήρες στην Περιοχή Δύο περιλαμβάνουν χαρακτήρες των οποίων η πρώτη τιμή byte βρίσκεται στο εύρος D8HEX έως F7HEX και η δεύτερη τιμή byte στο εύρος A1HEX έως FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Λειτουργία Extended Channel Interpretation (ECI)

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Κάθε χαρακτήρας της περιοχής GB18030 4-byte αντιπροσωπεύεται με 21 bits. Η περιοχή GB18030 4-byte κωδικοποιεί δεδομένα από όλους τους χαρακτήρες στην περιοχή GB18030 τετραψήφια (δηλαδή, χαρακτήρες των οποίων η πρώτη τιμή byte βρίσκεται στο εύρος 81HEX έως FEHEX, η δεύτερη τιμή byte στο εύρος 30HEX έως 39HEX, η τρίτη τιμή byte στο εύρος 81HEX έως FEHEX και η τέταρτη τιμή byte στο εύρος 30HEX έως 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Κάθε χαρακτήρας της περιοχής GB18030 2-byte αντιπροσωπεύεται με 15 bits. Η περιοχή GB18030 2-byte κωδικοποιεί δεδομένα από όλους τους χαρακτήρες (συμπεριλαμβανομένων των κοινών Κινέζικων χαρακτήρων στις Περιοχές Ένα και Δύο) στην περιοχή GB18030 διπλού byte (δηλαδή, Κινέζικοί χαρακτήρες των οποίων η πρώτη τιμή byte βρίσκεται στο εύρος 81HEX έως FEHEX και η δεύτερη τιμή byte στο εύρος 40HEX έως 7EHEX ή 80HEX έως FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


Η λειτουργία GS1 υποδεικνύει ότι τα δεδομένα που αντιπροσωπεύονται στο Han Xin Code είναι δεδομένα GS1 του συστήματος GS1 που ορίζονται από το GS1 General Specification. Παράδειγμα εισαγωγικής συμβολοσειράς: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Η λειτουργία Numeric κωδικοποιεί δεδομένα από το σύνολο δεκαδικών ψηφίων (ψηφία 0-9, τιμές byte 30HEX έως 39HEX). Κανονικά, 3 χαρακτήρες δεδομένων αντιπροσωπεύονται με 10 bits.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Η λειτουργία Text κωδικοποιεί δεδομένα από κοινά σύμβολα που ορίζονται στο ISO/IEC 646, δηλαδή τιμές byte 00 HEX έως 1B HEX και 20 HEX έως 7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Η λειτουργία Unicode σχεδιάζει έναν τρόπο για την αναπαράσταση οποιουδήποτε κειμενικού δεδομένου που αναφέρεται στην κωδικοποίηση/σύνολο χαρακτήρων UTF8 στο Han Xin Code.

### URI {#URI}
```
public static final HanXinModes URI
```


Η λειτουργία URI υποδεικνύει ότι τα δεδομένα που αντιπροσωπεύονται στο Han Xin Code είναι αναφορά Uniform Resource Identifier (URI) στο RFC 3986.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
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
| Parameter | Type | Περιγραφή |
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

