---
title: "MaxiCodeParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "MaxiCode parametreleri."
type: docs
weight: 55
url: /tr/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode parametreleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI kodlamasını alır. |
| [getEncodeMode()](#getEncodeMode--) | Bir MaxiCode kodlama modunu alır. |
| [getMode()](#getMode--) | Bir MaxiCode kodlama modunu alır. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Yapılandırılmış ekleme modunda bir MaxiCode barkod kimliğini alır. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Yapılandırılmış ekleme modunda MaxiCode barkod sayısını alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI kodlamasını ayarlar. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Bir MaxiCode kodlama modunu ayarlar. |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | Bir MaxiCode kodlama modunu ayarlar. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Yapılandırılmış ekleme modunda bir MaxiCode barkod kimliği ayarlar. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Yapılandırılmış ekleme modunda MaxiCode barkod sayısını ayarlar. |
| [toString()](#toString--) | Bu [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D Barkod modülünün Yükseklik/Genişlik oranı.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI kodlamasını alır. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Returns:**
int - ECI kodlaması.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Bir MaxiCode kodlama modunu alır. Varsayılan değer: Otomatik.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public final MaxiCodeMode getMode()
```


Bir MaxiCode kodlama modunu alır.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Yapılandırılmış ekleme modunda bir MaxiCode barkod kimliğini alır. Kimlik 1 ile 8 arasında bir değer olmalıdır. Varsayılan değer: 0

**Returns:**
int - yapılandırılmış ekleme modunda bir MaxiCode barkod kimliği.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Yapılandırılmış ekleme modunda MaxiCode barkod sayısını alır. Sayı 2 ile 8 arasında bir değer olmalıdır (maksimum barkod sayısı). Varsayılan değer: -1

**Returns:**
int - yapılandırılmış ekleme modunda bir MaxiCode barkod sayısı.
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D Barkod modülünün Yükseklik/Genişlik oranı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI kodlamasını ayarlar. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | ECI kodlaması. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Bir MaxiCode kodlama modunu ayarlar. Varsayılan değer: Otomatik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | bir MaxiCode kodlama modu. |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


Bir MaxiCode kodlama modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | bir MaxiCode kodlama modu. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Yapılandırılmış ekleme modunda bir MaxiCode barkod kimliği ayarlar. Kimlik 1 ile 8 arasında bir değer olmalıdır. Varsayılan değer: 0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | yapılandırılmış ekleme modunda bir MaxiCode barkod kimliği. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Yapılandırılmış ekleme modunda MaxiCode barkod sayısını ayarlar. Sayı 2 ile 8 arasında bir değer olmalıdır (maksimum barkod sayısı). Varsayılan değer: -1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | yapılandırılmış ekleme modunda bir MaxiCode barkod sayısı. |

### toString() {#toString--}
```
public String toString()
```


Bu [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) nesnesinin insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) nesnesini temsil eden bir dize.
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

