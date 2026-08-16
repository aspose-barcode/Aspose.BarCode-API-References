---
title: USADriveIdCodetext.SubfileProperties
second_title: Aspose.BarCode per Android via Java API Reference
description: Le proprietà di offset e lunghezza del subfile USA DL sono impostate automaticamente.
type: docs
weight: 12
url: /it/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

Le proprietà del sottofile USA DL, offset e lunghezza sono impostate automaticamente.
## Constructors

| Constructor | Descrizione |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Questi byte contengono un valore numerico a 4 cifre che specifica la lunghezza del Subfile in byte. Il terminatore di segmento deve essere incluso nel calcolo della lunghezza del subfile. Un terminatore di segmento = 1. |
| [getOffset()](#getOffset--) | Valore numerico a 4 cifre che specifica il numero di byte dalla testa o dall'inizio del file fino a dove sono situati i dati relativi al particolare sub-file. Il primo byte del file si trova all'offset 0. |
| [getType()](#getType--) | Tipo di subfile a 2 byte, come "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Questi byte contengono un valore numerico a 4 cifre che specifica la lunghezza del Subfile in byte. Il terminatore di segmento deve essere incluso nel calcolo della lunghezza del subfile. Un terminatore di segmento = 1. |
| [setOffset(int value)](#setOffset-int-) | Valore numerico a 4 cifre che specifica il numero di byte dalla testa o dall'inizio del file fino a dove sono situati i dati relativi al particolare sub-file. Il primo byte del file si trova all'offset 0. |
| [setType(String value)](#setType-java.lang.String-) | Tipo di subfile a 2 byte, come "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| tipo | java.lang.String |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getLength() {#getLength--}
```
public final int getLength()
```


4 Questi byte contengono un valore numerico a 4 cifre che specifica la lunghezza del Subfile in byte. Il terminatore di segmento deve essere incluso nel calcolo della lunghezza del subfile. Un terminatore di segmento = 1. Ogni subfile deve iniziare con il Tipo di Subfile a due caratteri e questi due caratteri devono essere inclusi nella lunghezza.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


Valore numerico a 4 cifre che specifica il numero di byte dalla testa o dall'inizio del file fino a dove sono situati i dati relativi al particolare sub-file. Il primo byte del file si trova all'offset 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


Tipo di subfile a 2 byte, come "DL"

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


4 Questi byte contengono un valore numerico a 4 cifre che specifica la lunghezza del Subfile in byte. Il terminatore di segmento deve essere incluso nel calcolo della lunghezza del subfile. Un terminatore di segmento = 1. Ogni subfile deve iniziare con il Tipo di Subfile a due caratteri e questi due caratteri devono essere inclusi nella lunghezza.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


Valore numerico a 4 cifre che specifica il numero di byte dalla testa o dall'inizio del file fino a dove sono situati i dati relativi al particolare sub-file. Il primo byte del file si trova all'offset 0.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


Tipo di subfile a 2 byte, come "DL"

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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

