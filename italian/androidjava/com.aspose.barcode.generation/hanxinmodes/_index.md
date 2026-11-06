---
title: "HanXinModes"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "Modalità di codifica per Han Xin Code."
type: docs
weight: 90
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
| [AUTO](#AUTO) | Sequenza di modalità Numeric, Text, ECI, Binary Bytes e 4 GB18030 che cambiano automaticamente. |
| [BINARY](#BINARY) | La modalità Binary byte codifica i dati binari in qualsiasi forma e li codifica nel loro byte binario. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Ogni carattere cinese comune nella Regione Uno è rappresentato da 12 bit. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Ogni carattere cinese comune nella Regione Due è rappresentato da 12 bit. |
| [ECI](#ECI) | Modalità Extended Channel Interpretation (ECI) |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Ogni carattere della Regione GB18030 a 4 byte è rappresentato da 21 bit. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Ogni carattere della Regione GB18030 a 2 byte è rappresentato da 15 bit. |
| [GS_1](#GS-1) | La modalità GS1 indica che i dati rappresentati nel Han Xin Code sono dati GS1 del sistema GS1 definiti dalla Specifica Generale GS1. |
| [NUMERIC](#NUMERIC) | La modalità Numeric codifica i dati dal set di cifre decimali (cifre 0-9, valori byte 30HEX a 39HEX). |
| [TEXT](#TEXT) | La modalità Text codifica i dati da simboli comuni definiti in ISO/IEC 646, cioè. |
| [UNICODE](#UNICODE) | La modalità Unicode prevede un modo per rappresentare qualsiasi dato testuale riferito alla codifica/carattere UTF8 nel Han Xin Code. |
| [URI](#URI) | La modalità URI indica che i dati rappresentati nel Han Xin Code sono un Uniform Resource Identifier (URI) riferito a RFC 3986. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
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


Sequenza di modalità Numeric, Text, ECI, Binary Bytes e 4 GB18030 che cambiano automaticamente.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


La modalità Binary byte codifica i dati binari in qualsiasi forma e li codifica nel loro byte binario. Ogni byte nella modalità Binary Byte è rappresentato da 8 bit.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Ogni carattere cinese comune nella Regione Uno è rappresentato da 12 bit. I caratteri cinesi comuni nella Regione uno includono i caratteri il cui valore del primo byte è nell'intervallo da B0HEX a D7HEX e il valore del secondo byte è nell'intervallo da A1HEX a FEHEX (3760 caratteri), e i caratteri il cui valore del primo byte è nell'intervallo da A1HEX a A3HEX e il valore del secondo byte è nell'intervallo da A1HEX a FEHEX (282 caratteri), e i caratteri i cui valori dei byte sono nell'intervallo da A8A1HEX a A8C0HEX (32 caratteri).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Ogni carattere cinese comune nella Regione Due è rappresentato da 12 bit. I caratteri cinesi comuni nella Regione Due includono i caratteri il cui valore del primo byte è nell'intervallo da D8HEX a F7HEX e il valore del secondo byte è nell'intervallo da A1HEX a FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Modalità Extended Channel Interpretation (ECI)

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Ogni carattere della regione a 4 byte GB18030 è rappresentato da 21 bit. La regione a 4 byte GB18030 codifica i dati di tutti i caratteri nella regione a quattro byte GB18030 (cioè, i caratteri il cui valore del primo byte è nell'intervallo da 81HEX a FEHEX, il valore del secondo byte è nell'intervallo da 30HEX a 39HEX, il valore del terzo byte è nell'intervallo da 81HEX a FEHEX e il valore del quarto byte è nell'intervallo da 30HEX a 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Ogni carattere della regione a 2 byte GB18030 è rappresentato da 15 bit. La regione a 2 byte GB18030 codifica i dati di tutti i caratteri (inclusi i caratteri cinesi comuni nelle Regioni Uno e Due) nella regione a doppio byte GB18030, (cioè, i caratteri cinesi il cui valore del primo byte è nell'intervallo da 81HEX a FEHEX e il valore del secondo byte è nell'intervallo da 40HEX a 7EHEX o da 80HEX a FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


La modalità GS1 indica che i dati rappresentati nel codice Han Xin sono dati GS1 del sistema GS1 definiti dalla Specifica Generale GS1. Esempio di stringa di input: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


La modalità numerica codifica i dati dal set di cifre decimali (cifre 0-9, valori dei byte da 30HEX a 39HEX). Normalmente, 3 caratteri di dati sono rappresentati da 10 bit.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


La modalità testo codifica i dati dai simboli comuni definiti in ISO/IEC 646, cioè valori dei byte da 00 HEX a 1B HEX e da 20 HEX a 7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


La modalità Unicode prevede un modo per rappresentare qualsiasi dato testuale riferito alla codifica/carattere UTF8 nel Han Xin Code.

### URI {#URI}
```
public static final HanXinModes URI
```


La modalità URI indica che i dati rappresentati nel Han Xin Code sono un Uniform Resource Identifier (URI) riferito a RFC 3986.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static HanXinModes fromValue(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
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
| Parametro | Tipo | Descrizione |
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

