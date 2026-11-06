---
title: "ITFParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "ITF parametreleri."
type: docs
weight: 50
url: /tr/androidjava/com.aspose.barcode.generation/itfparameters/
---
**Inheritance:**
java.lang.Object
```
public class ITFParameters
```

ITF parametreleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBorderThickness()](#getBorderThickness--) | ITF kenarının (taşıyıcı çubuğu) kalınlığını Birim değeri olarak alır. |
| [getBorderType()](#getBorderType--) | ITF barkodunun kenar tipi. |
| [getClass()](#getClass--) |  |
| [getQuietZoneCoef()](#getQuietZoneCoef--) | xDimension'daki sessiz bölgelerin boyutu. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBorderThickness(Unit value)](#setBorderThickness-com.aspose.barcode.generation.Unit-) | ITF kenarının (taşıyıcı çubuğu) kalınlığını Birim değeri olarak ayarlar. |
| [setBorderType(ITF14BorderType value)](#setBorderType-com.aspose.barcode.generation.ITF14BorderType-) | ITF barkodunun kenar tipi. |
| [setQuietZoneCoef(int value)](#setQuietZoneCoef-int-) | xDimension'daki sessiz bölgelerin boyutu. |
| [toString()](#toString--) | Bu [ITFParameters](../../com.aspose.barcode.generation/itfparameters) öğesinin insan tarafından okunabilir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBorderThickness() {#getBorderThickness--}
```
public final Unit getBorderThickness()
```


ITF kenarının (taşıyıcı çubuğu) kalınlığını Birim değeri olarak alır. Varsayılan değer: 12pt.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - an ITF border (bearer bar) thickness in Unit value.
### getBorderType() {#getBorderType--}
```
public final ITF14BorderType getBorderType()
```


ITF barkodunun kenar tipi. Varsayılan değer: ITF14BorderType.Bar.

**Returns:**
[ITF14BorderType](../../com.aspose.barcode.generation/itf14bordertype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getQuietZoneCoef() {#getQuietZoneCoef--}
```
public final int getQuietZoneCoef()
```


xDimension'daki sessiz bölgelerin boyutu. Varsayılan değer: 10, yani xDimension = 2px ise sessiz bölgeler 20px olur.

**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
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




### setBorderThickness(Unit value) {#setBorderThickness-com.aspose.barcode.generation.Unit-}
```
public final void setBorderThickness(Unit value)
```


ITF kenarının (taşıyıcı çubuğu) kalınlığını Birim değeri olarak ayarlar. Varsayılan değer: 12pt.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | bir ITF kenarı (taşıyıcı çubuğu) kalınlığı Birim değeri olarak. |

### setBorderType(ITF14BorderType value) {#setBorderType-com.aspose.barcode.generation.ITF14BorderType-}
```
public final void setBorderType(ITF14BorderType value)
```


ITF barkodunun kenar tipi. Varsayılan değer: ITF14BorderType.Bar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITF14BorderType](../../com.aspose.barcode.generation/itf14bordertype) |  |

### setQuietZoneCoef(int value) {#setQuietZoneCoef-int-}
```
public final void setQuietZoneCoef(int value)
```


xDimension'daki sessiz bölgelerin boyutu. Varsayılan değer: 10, yani xDimension = 2px ise sessiz bölgeler 20px olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### toString() {#toString--}
```
public String toString()
```


Bu [ITFParameters](../../com.aspose.barcode.generation/itfparameters) öğesinin insan tarafından okunabilir dize temsili döndürür.

**Returns:**
java.lang.String - Bu [ITFParameters](../../com.aspose.barcode.generation/itfparameters) öğesini temsil eden bir dize.
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

