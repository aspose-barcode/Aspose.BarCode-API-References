---
title: HanXinModes
second_title: Aspose.BarCode per Android via Java API Reference
description: Modalità di codifica Han Xin Code.
type: docs
weight: 91
url: /it/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Modalità di codifica Han Xin Code. Si consiglia di utilizzare Auto con caratteri ASCII / Cinesi o Unicode per i caratteri Unicode.
## Campi

| Campo | Descrizione |
| --- | --- |
| [AUTO](#AUTO) | Sequenza di modalità Numerica, Testo, ECI, Byte Binari e 4 modalità GB18030 che cambiano automaticamente. |
| [BINARY](#BINARY) | La modalità byte binario codifica dati binari in qualsiasi forma e li codifica nel loro byte binario. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Ogni carattere cinese comune nella Regione Uno è rappresentato da 12 bit. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Ogni carattere cinese comune nella Regione Due è rappresentato da 12 bit. |
| [ECI](#ECI) | Modalità Extended Channel Interpretation (ECI) |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Ogni carattere della Regione GB18030 a 4 byte è rappresentato da 21 bit. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Ogni carattere della Regione GB18030 a 2 byte è rappresentato da 15 bit. |
| [GS_1](#GS-1) | La modalità GS1 indica che i dati rappresentati nel Han Xin Code sono dati GS1 del sistema GS1 definiti dalla Specifica Generale GS1. |
| [NUMERIC](#NUMERIC) | La modalità Numerica codifica i dati dal set di cifre decimali (cifre 0-9, valori byte 30HEX a 39HEX). |
| [TEXT](#TEXT) | La modalità Testo codifica i dati dai simboli comuni definiti in ISO/IEC 646, cioè. |
| [UNICODE](#UNICODE) | La modalità Unicode progetta un modo per rappresentare qualsiasi dato testuale facendo riferimento alla codifica/carattere UTF8 nel Han Xin Code. |
| [URI](#URI) | La modalità URI indica che i dati rappresentati nel Han Xin Code sono Uniform Resource Identifier (URI) riferiti al RFC 3986. |
## Methods

| Method | Descrizione |
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


Sequenza di modalità Numerica, Testo, ECI, Byte Binari e 4 modalità GB18030 che cambiano automaticamente.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


La modalità byte binario codifica dati binari in qualsiasi forma e li codifica nel loro byte binario. Ogni byte nella modalità Byte Binario è rappresentato da 8 bit.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Ogni carattere cinese comune nella Regione Uno è rappresentato da 12 bit. I caratteri cinesi comuni nella Regione Uno includono i caratteri il cui primo valore byte è nell'intervallo B0HEX‑D7HEX e il secondo valore byte è nell'intervallo A1HEX‑FEHEX (3760 caratteri), e i caratteri il cui primo valore byte è nell'intervallo A1HEX‑A3HEX e il secondo valore byte è nell'intervallo A1HEX‑FEHEX (282 caratteri), e i caratteri i cui valori byte sono nell'intervallo A8A1HEX‑A8C0HEX (32 caratteri).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Ogni carattere cinese comune nella Regione Due è rappresentato da 12 bit. I caratteri cinesi comuni nella Regione Due includono i caratteri il cui primo valore byte è nell'intervallo D8HEX‑F7HEX e il secondo valore byte è nell'intervallo A1HEX‑FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Modalità Extended Channel Interpretation (ECI)

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Ogni carattere della Regione GB18030 a 4 byte è rappresentato da 21 bit. La Regione GB18030 a 4 byte codifica i dati da tutti i caratteri nella regione a quattro byte GB18030 (cioè, i caratteri il cui primo valore byte è nell'intervallo 81HEX‑FEHEX, il secondo valore byte è nell'intervallo 30HEX‑39HEX, il terzo valore byte è nell'intervallo 81HEX‑FEHEX e il quarto valore byte è nell'intervallo 30HEX‑39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Ogni carattere della Regione GB18030 a 2 byte è rappresentato da 15 bit. La Regione GB18030 a 2 byte codifica i dati da tutti i caratteri (inclusi i caratteri cinesi comuni nelle Regioni Uno e Due) nella regione a doppio byte GB18030, (cioè, i caratteri cinesi il cui primo valore byte è nell'intervallo 81HEX‑FEHEX e il secondo valore byte è nell'intervallo 40HEX‑7EHEX o 80HEX‑FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


La modalità GS1 indica che i dati rappresentati nel Han Xin Code sono dati GS1 del sistema GS1 definiti dalla Specifica Generale GS1. Esempio di stringa di input: \"(01)03453120000011(17)191125(10)ABCD1234(21)10\".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


La modalità Numerica codifica i dati dal set di cifre decimali (cifre 0-9, valori byte 30HEX a 39HEX). Normalmente, 3 caratteri di dati sono rappresentati da 10 bit.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


La modalità Testo codifica i dati dai simboli comuni definiti in ISO/IEC 646, cioè valori byte 00 HEX‑1B HEX e 20 HEX‑7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


La modalità Unicode progetta un modo per rappresentare qualsiasi dato testuale facendo riferimento alla codifica/carattere UTF8 nel Han Xin Code.

### URI {#URI}
```
public static final HanXinModes URI
```


La modalità URI indica che i dati rappresentati nel Han Xin Code sono Uniform Resource Identifier (URI) riferiti al RFC 3986.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

