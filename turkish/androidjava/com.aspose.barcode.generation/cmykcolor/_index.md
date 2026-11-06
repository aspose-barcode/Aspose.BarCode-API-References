---
title: "CMYKColor"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "CMYK renk için sınıf."
type: docs
weight: 19
url: /tr/androidjava/com.aspose.barcode.generation/cmykcolor/
---
**Inheritance:**
java.lang.Object
```
public class CMYKColor
```

CMYK rengi için sınıf. Null, CMYK'nın kullanılmadığını, varsayılan RGB renginin kullanıldığını ifade eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CMYKColor(int c, int m, int y, int k)](#CMYKColor-int-int-int-int-) | CMYK değerlerinden yeni bir CMYKColor sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [C](#C) |  |
| [K](#K) |  |
| [M](#M) |  |
| [Y](#Y) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renk değerlerinin aynı olup olmadığını karşılaştırır |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | CMYKColor'ın karma kodu |
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


CMYK değerlerinden yeni bir CMYKColor sınıfı örneği başlatır. CMYK değerleri 0-100 arasındadır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | int | Camgöbeği değeri [0, 100] |
| m | int | Macenta değeri [0, 100] |
| y | int | Sarı değeri [0, 100] |
| k | int | Siyah değeri [0, 100] |

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


Renk değerlerinin aynı olup olmadığını karşılaştırır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak CMYKColor |

**Returns:**
boolean - Değerler aynı mı
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


CMYKColor'ın karma kodu

**Returns:**
int - CMYKColor'ın karma kodu
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

