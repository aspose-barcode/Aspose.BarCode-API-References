---
title: "Unit"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Farklı birimlerde (Piksel, İnç vb.) boyut değerini belirtir.."
type: docs
weight: 67
url: /tr/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Boyut değerini farklı birimlerde (Piksel, İnç vb.) belirtir.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örnek ile belirtilen nesnenin, aynı zamanda bir  Unit  nesnesi olması gereken, aynı değere sahip olup olmadığını belirler. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Belge birimlerinde boyut değerini alır. |
| [getInches()](#getInches--) | İnç cinsinden boyut değerini alır. |
| [getMillimeters()](#getMillimeters--) | Milimetre cinsinden boyut değerini alır. |
| [getPixels()](#getPixels--) | Piksel cinsinden boyut değerini alır. |
| [getPoint()](#getPoint--) | Punto cinsinden boyut değerini alır. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Bu nesne için karma kodunu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Belge birimlerinde boyut değerini ayarlar. |
| [setInches(float value)](#setInches-float-) | İnç cinsinden boyut değerini ayarlar. |
| [setMillimeters(float value)](#setMillimeters-float-) | Milimetre cinsinden boyut değerini ayarlar. |
| [setPixels(float value)](#setPixels-float-) | Piksel cinsinden boyut değerini ayarlar. |
| [setPoint(float value)](#setPoint-float-) | Punto cinsinden boyut değerini ayarlar. |
| [toString()](#toString--) | Bu Unit öğesinin insan tarafından okunabilir bir dize temsili döndürür. |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örnek ile belirtilen nesnenin, aynı zamanda bir  Unit  nesnesi olması gereken, aynı değere sahip olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak Unit. |

**Returns:**
boolean - obj bir Unit ise ve değeri bu örnekle aynıysa true; aksi takdirde false. Obj null ise, yöntem false döndürür.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


Belge birimlerinde boyut değerini alır.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


İnç cinsinden boyut değerini alır.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Milimetre cinsinden boyut değerini alır.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Piksel cinsinden boyut değerini alır.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Punto cinsinden boyut değerini alır.

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu nesne için karma kodunu döndürür.

**Returns:**
int - 32 bit işaretli tamsayı karma kodu.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


Belge birimlerinde boyut değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


İnç cinsinden boyut değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Milimetre cinsinden boyut değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Piksel cinsinden boyut değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Punto cinsinden boyut değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### toString() {#toString--}
```
public String toString()
```


Bu Unit öğesinin insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu Unit öğesini temsil eden bir dize.
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpi | float |  |

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

