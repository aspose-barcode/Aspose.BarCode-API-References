---
title: "AztecParametersUI"
second_title: "Aspose.BarCode for Java API Referansı"
description: "AztecParameters sınıfı için UI sarmalayıcı"
type: docs
weight: 10
url: /tr/java/com.aspose.barcode.barcodecontrol/aztecparametersui/
---
**Inheritance:**
java.lang.Object
```
public class AztecParametersUI
```

AztecParameters sınıfı için UI sarmalayıcı
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D BarCode modülünün Yükseklik/Genişlik oranı. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI kodlamasını alır. |
| [getEncodeMode()](#getEncodeMode--) | Aztec kodlama modunu alır. |
| [getErrorLevel()](#getErrorLevel--) | Aztec barkod türlerinin hata düzeltme seviyesini belirtir. |
| [getLayersCount()](#getLayersCount--) | Aztec sembolünün katman sayısını alır. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztec barkodunun Structured Append modu için Barkod Kimliğini alır. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztec barkodunun Structured Append modu için barkod sayısını alır. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztec barkodunun Structured Append modu için Dosya Kimliğini alır (isteğe bağlı alan). |
| [getSymbolMode()](#getSymbolMode--) | Aztec Sembol modunu alır. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D BarCode modülünün Yükseklik/Genişlik oranı. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI kodlamasını ayarlar. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Aztec kodlama modunu ayarlar. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Aztec barkod türlerinin hata düzeltme seviyesini belirtir. |
| [setLayersCount(int value)](#setLayersCount-int-) | Aztec sembolünün katman sayısını ayarlar. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Aztec barkodunun Structured Append modu için Barkod Kimliğini alır. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aztec barkodunun Structured Append modu için barkod sayısını alır. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Aztec barkodunun Structured Append modu için Dosya Kimliğini alır (isteğe bağlı alan). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Aztec Sembol modunu ayarlar. |
| [toString()](#toString--) | Bu [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
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
public float getAspectRatio()
```


2D BarCode modülünün Yükseklik/Genişlik oranı.

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


ECI kodlamasını alır. AztecEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1

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
public int getErrorLevel()
```


Aztec tipindeki barkodların hata düzeltme seviyesi. Değer 10 ile 95 arasında olmalıdır.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Aztec sembolünün katman sayısını alır. Katman sayısı, Compact mod için 1 ile 3 arasında, Full Range mod için 1 ile 32 arasında olmalıdır. Varsayılan değer: 0 (auto).

**Returns:**
int - Aztec sembolünün katman sayısı.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Aztec barkodunun Structured Append modu için Barkod Kimliği. Barkod Kimliği 1 ile barkod sayısı arasında olmalıdır. Varsayılan değer: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aztec barkodunun Structured Append modu için barkod sayısı. Barkod sayısı 1 ile 26 arasında olmalıdır. Varsayılan değer: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Aztec barkodunun Structured Append modu için Dosya Kimliği (isteğe bağlı alan). Dosya Kimliği boşluk içermemelidir. Varsayılan değer: boş dize

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public AztecSymbolMode getSymbolMode()
```


Aztec Sembol modunu alır.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır.

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
public void setAspectRatio(float value)
```


2D BarCode modülünün Yükseklik/Genişlik oranı.

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
public void setErrorLevel(int value)
```


Aztec tipindeki barkodların hata düzeltme seviyesi. Değer 10 ile 95 arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Aztec sembolünün katman sayısını ayarlar. Katman sayısı, Compact mod için 1 ile 3 arasında, Full Range mod için 1 ile 32 arasında olmalıdır. Varsayılan değer: 0 (auto).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Aztec sembolünün katman sayısı. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Aztec barkodunun Structured Append modu için Barkod Kimliği. Barkod Kimliği 1 ile barkod sayısı arasında olmalıdır. Varsayılan değer: 0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aztec barkodunun Structured Append modu için barkod sayısı. Barkod sayısı 1 ile 26 arasında olmalıdır. Varsayılan değer: 0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Aztec barkodunun Structured Append modu için Dosya Kimliği (isteğe bağlı alan). Dosya Kimliği boşluk içermemelidir. Varsayılan değer: boş dize

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public void setSymbolMode(AztecSymbolMode value)
```


Aztec Sembol modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) |  |

### toString() {#toString--}
```
public String toString()
```


Bu [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) nesnesinin insan tarafından okunabilir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) öğesini temsil eden bir dize.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

