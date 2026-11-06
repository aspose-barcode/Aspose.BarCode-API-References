---
title: "AztecParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Aztec parametreleri."
type: docs
weight: 12
url: /tr/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Aztec parametreleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI kodlamasını alır. |
| [getEncodeMode()](#getEncodeMode--) | Aztec kodlama modunu alır. |
| [getErrorLevel()](#getErrorLevel--) | Aztec barkod tiplerinin hata düzeltme seviyesi. |
| [getLayersCount()](#getLayersCount--) | Aztec sembolünün katman sayısını alır. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztec barkodunun Yapılandırılmış Ekleme modu için Barkod Kimliği. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztec barkodunun Yapılandırılmış Ekleme modu için barkod sayısı. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztec barkodunun Yapılandırılmış Ekleme modu için Dosya Kimliği (isteğe bağlı alan). |
| [getSymbolMode()](#getSymbolMode--) | Aztec Sembol modunu alır. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Okuyucuya sembolde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI kodlamasını ayarlar. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Aztec kodlama modunu ayarlar. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Aztec barkod tiplerinin hata düzeltme seviyesi. |
| [setLayersCount(int value)](#setLayersCount-int-) | Aztec sembolünün katman sayısını ayarlar. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Okuyucuya sembolde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Aztec barkodunun Yapılandırılmış Ekleme modu için Barkod Kimliği. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aztec barkodunun Yapılandırılmış Ekleme modu için barkod sayısı. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Aztec barkodunun Yapılandırılmış Ekleme modu için Dosya Kimliği (isteğe bağlı alan). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Aztec Sembol modunu ayarlar. |
| [toString()](#toString--) | Bu [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
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


ECI kodlamasını alır. AztecEncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Returns:**
int - ECI kodlaması.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Aztec kodlama modunu alır. Varsayılan değer: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - bir Aztec kodlama modu.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Aztec barkod tiplerinin hata düzeltme seviyesi. Değer 5 ile 95 arasında olmalıdır.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Aztec sembolünün katman sayısını alır. Katman sayısı Kompakt mod için 1 ile 3 arasında, Tam Aralık mod için 1 ile 32 arasında olmalıdır. Varsayılan değer: 0 (otomatik).

**Returns:**
int - Aztec sembolünün katman sayısı.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Aztec barkodunun Yapılandırılmış Ekleme modu için Barkod Kimliği. Barkod Kimliği 1 ile barkod sayısı arasında olmalıdır. Varsayılan değer: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aztec barkodunun Structured Append modunda barkod sayısı. Barkod sayısı 1 ile 26 arasında olmalıdır. Varsayılan değer: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Aztec barkodunun Structured Append modunda Dosya Kimliği (isteğe bağlı alan). Dosya Kimliği boşluk içermemelidir. Varsayılan değer: boş string

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Aztec Sembol modunu alır. Varsayılan değer: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Okuyucuya sembolde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır.

**Returns:**
boolean
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


ECI kodlamasını ayarlar. AztecEncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | ECI kodlaması. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Aztec kodlama modunu ayarlar. Varsayılan değer: Auto.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.barcode.generation.AztecEncodeMode | bir Aztec kodlama modu. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Aztec barkod tiplerinin hata düzeltme seviyesi. Değer 5 ile 95 arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Aztec sembolünün katman sayısını ayarlar. Katman sayısı Compact mod için 1 ile 3 arasında, Full Range mod için 1 ile 32 arasında olmalıdır. Varsayılan değer: 0 (otomatik).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Aztec sembolünün katman sayısı. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Okuyucuya sembolde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Aztec barkodunun Yapılandırılmış Ekleme modu için Barkod Kimliği. Barkod Kimliği 1 ile barkod sayısı arasında olmalıdır. Varsayılan değer: 0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aztec barkodunun Structured Append modunda barkod sayısı. Barkod sayısı 1 ile 26 arasında olmalıdır. Varsayılan değer: 0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Aztec barkodunun Structured Append modunda Dosya Kimliği (isteğe bağlı alan). Dosya Kimliği boşluk içermemelidir. Varsayılan değer: boş string

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Aztec Sembol modunu ayarlar. Varsayılan değer: AztecSymbolMode.Auto.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | bir Aztec Sembol modu. |

### toString() {#toString--}
```
public String toString()
```


Bu [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) nesnesinin insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) öğesini temsil eden bir dize.
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

