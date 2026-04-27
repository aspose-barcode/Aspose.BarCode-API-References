---
title: CMYKColor
second_title: Aspose.BarCode for Android via Java API-referens
description: Klass för CMYK-färg.
type: docs
weight: 19
url: /sv/androidjava/com.aspose.barcode.generation/cmykcolor/
---
**Inheritance:**
java.lang.Object
```
public class CMYKColor
```

Klass för CMYK-färg. Null betyder att CMYK inte används, standard‑RGB‑färg används.
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [CMYKColor(int c, int m, int y, int k)](#CMYKColor-int-int-int-int-) | Initierar en ny instans av klassen  CMYKColor  från CMYK‑värden. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [C](#C) |  |
| [K](#K) |  |
| [M](#M) |  |
| [Y](#Y) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Jämför om färgvärdena är desamma |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Hash‑kod för CMYKColor |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CMYKColor(int c, int m, int y, int k) {#CMYKColor-int-int-int-int-}
```
public CMYKColor(int c, int m, int y, int k)
```


Initierar en ny instans av klassen  CMYKColor  från CMYK‑värden. CMYK‑värden är 0‑100.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| c | int | Cyan‑värde [0, 100] |
| m | int | Magenta‑värde [0, 100] |
| y | int | Gul‑värde [0, 100] |
| k | int | Svart‑värde [0, 100] |

### C {#C}
```
public float C
```


### K {#K}
```
public float K
```


### M {#M}
```
public float M
```


### Y {#Y}
```
public float Y
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Jämför om färgvärdena är desamma

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | CMYKColor att jämföra |

**Returns:**
boolean - Är värdena desamma
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash‑kod för CMYKColor

**Returns:**
int - Hash‑kod för CMYKColor
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

