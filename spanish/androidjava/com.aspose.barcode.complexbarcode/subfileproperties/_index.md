---
title: USADriveIdCodetext.SubfileProperties
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Las propiedades de desplazamiento y longitud del subarchivo de la licencia de EE. UU se establecen automáticamente.
type: docs
weight: 12
url: /es/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

Las propiedades del subarchivo de la licencia de conducir de EE. UU, desplazamiento y longitud se establecen automáticamente.
## Constructors

| Constructor | Descripción |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Estos bytes contienen un valor numérico de 4 dígitos que especifica la longitud del Subfile en bytes. El terminador de segmento debe incluirse al calcular la longitud del subfile. Un terminador de segmento = 1. |
| [getOffset()](#getOffset--) | Valor numérico de 4 dígitos que especifica el número de bytes desde el inicio del archivo hasta donde se encuentran los datos relacionados con el subarchivo particular. El primer byte del archivo está ubicado en el desplazamiento 0. |
| [getType()](#getType--) | Tipo de subarchivo de 2 bytes, como "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Estos bytes contienen un valor numérico de 4 dígitos que especifica la longitud del Subfile en bytes. El terminador de segmento debe incluirse al calcular la longitud del subfile. Un terminador de segmento = 1. |
| [setOffset(int value)](#setOffset-int-) | Valor numérico de 4 dígitos que especifica el número de bytes desde el inicio del archivo hasta donde se encuentran los datos relacionados con el subarchivo particular. El primer byte del archivo está ubicado en el desplazamiento 0. |
| [setType(String value)](#setType-java.lang.String-) | Tipo de subarchivo de 2 bytes, como "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| tipo | java.lang.String |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


4 Estos bytes contienen un valor numérico de 4 dígitos que especifica la longitud del Subfile en bytes. El terminador de segmento debe incluirse al calcular la longitud del subfile. Un terminador de segmento = 1. Cada subfile debe comenzar con el Tipo de Subfile de dos caracteres y estos dos caracteres también deben incluirse en la longitud.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


Valor numérico de 4 dígitos que especifica el número de bytes desde el inicio del archivo hasta donde se encuentran los datos relacionados con el subarchivo particular. El primer byte del archivo está ubicado en el desplazamiento 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


Tipo de subarchivo de 2 bytes, como "DL"

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 Estos bytes contienen un valor numérico de 4 dígitos que especifica la longitud del Subfile en bytes. El terminador de segmento debe incluirse al calcular la longitud del subfile. Un terminador de segmento = 1. Cada subfile debe comenzar con el Tipo de Subfile de dos caracteres y estos dos caracteres también deben incluirse en la longitud.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


Valor numérico de 4 dígitos que especifica el número de bytes desde el inicio del archivo hasta donde se encuentran los datos relacionados con el subarchivo particular. El primer byte del archivo está ubicado en el desplazamiento 0.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


Tipo de subarchivo de 2 bytes, como "DL"

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




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

