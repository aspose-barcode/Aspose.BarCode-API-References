---
title: HanXinModes
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Modo de codificación Han Xin Code.
type: docs
weight: 91
url: /es/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Modo de codificación Han Xin Code. Se recomienda usar Auto con caracteres ASCII / chinos o Unicode para caracteres Unicode.
## Campos

| Campo | Descripción |
| --- | --- |
| [AUTO](#AUTO) | Secuencia de modos Numérico, Texto, ECI, Bytes Binarios y 4 GB18030 que cambian automáticamente. |
| [BINARY](#BINARY) | El modo byte binario codifica datos binarios en cualquier forma y los codifica en su byte binario. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Cada carácter chino común en la Región Uno se representa con 12 bits. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Cada carácter chino común en la Región Dos se representa con 12 bits. |
| [ECI](#ECI) | Modo de Interpretación de Canal Extendido (ECI) |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Cada carácter de la región de 4 bytes GB18030 se representa con 21 bits. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Cada carácter de la región de 2 bytes GB18030 se representa con 15 bits. |
| [GS_1](#GS-1) | El modo GS1 indica que los datos representados en Han Xin Code son datos GS1 del sistema GS1 definidos por la Especificación General GS1. |
| [NUMERIC](#NUMERIC) | El modo numérico codifica datos del conjunto de dígitos decimales (dígitos 0-9, valores de byte 30HEX a 39HEX). |
| [TEXT](#TEXT) | El modo texto codifica datos de símbolos comunes definidos en ISO/IEC 646, es decir, |
| [UNICODE](#UNICODE) | El modo Unicode diseña una forma de representar cualquier dato de texto referenciado a la codificación/conjunto de caracteres UTF8 en Han Xin Code. |
| [URI](#URI) | El modo URI indica que los datos representados en Han Xin Code son una referencia de Identificador Uniforme de Recursos (URI) a la RFC 3986. |
## Methods

| Method | Descripción |
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


Secuencia de modos Numérico, Texto, ECI, Bytes Binarios y 4 GB18030 que cambian automáticamente.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


El modo byte binario codifica datos binarios en cualquier forma y los codifica en su byte binario. Cada byte en el modo Byte Binario se representa con 8 bits.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Cada carácter chino común en la Región Uno se representa con 12 bits. Los caracteres chinos comunes en la Región Uno incluyen caracteres cuyo primer valor de byte está en el rango B0HEX a D7HEX y cuyo segundo valor de byte está en el rango A1HEX a FEHEX (3760 caracteres), y caracteres cuyo primer valor de byte está en el rango A1HEX a A3HEX y cuyo segundo valor de byte está en el rango A1HEX a FEHEX (282 caracteres), y caracteres cuyos valores de byte están en el rango A8A1HEX a A8C0HEX (32 caracteres).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Cada carácter chino común en la Región Dos se representa con 12 bits. Los caracteres chinos comunes en la Región Dos incluyen caracteres cuyo primer valor de byte está en el rango D8HEX a F7HEX y cuyo segundo valor de byte está en el rango A1HEX a FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Modo de Interpretación de Canal Extendido (ECI)

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Cada carácter de la región de 4 bytes GB18030 se representa con 21 bits. La región de 4 bytes GB18030 codifica datos de todos los caracteres en la región de cuatro bytes GB18030 (es decir, caracteres cuyo primer valor de byte está en el rango 81HEX a FEHEX, segundo valor de byte en el rango 30HEX a 39HEX, tercer valor de byte en el rango 81HEX a FEHEX y cuarto valor de byte en el rango 30HEX a 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Cada carácter de la región de 2 bytes GB18030 se representa con 15 bits. La región de 2 bytes GB18030 codifica datos de todos los caracteres (incluidos los caracteres chinos comunes en las Regiones Uno y Dos) en la región de doble byte GB18030, (es decir, caracteres chinos cuyo primer valor de byte está en el rango 81HEX a FEHEX y cuyo segundo valor de byte está en el rango 40HEX a 7EHEX o 80HEX a FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


El modo GS1 indica que los datos representados en Han Xin Code son datos GS1 del sistema GS1 definidos por la Especificación General GS1. Ejemplo de cadena de entrada: \"(01)03453120000011(17)191125(10)ABCD1234(21)10\".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


El modo numérico codifica datos del conjunto de dígitos decimales (dígitos 0-9, valores de byte 30HEX a 39HEX). Normalmente, 3 caracteres de datos se representan con 10 bits.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


El modo texto codifica datos de símbolos comunes definidos en ISO/IEC 646, es decir, valores de byte 00 HEX a 1B HEX y 20 HEX a 7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


El modo Unicode diseña una forma de representar cualquier dato de texto referenciado a la codificación/conjunto de caracteres UTF8 en Han Xin Code.

### URI {#URI}
```
public static final HanXinModes URI
```


El modo URI indica que los datos representados en Han Xin Code son una referencia de Identificador Uniforme de Recursos (URI) a la RFC 3986.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
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
| Parameter | Type | Descripción |
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
| Parameter | Type | Descripción |
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
| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

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

