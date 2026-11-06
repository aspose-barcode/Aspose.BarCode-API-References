---
title: "DotCodeParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "DotCode parametreleri."
type: docs
weight: 35
url: /tr/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode parametreleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Sütun sayısını belirler. |
| [getECIEncoding()](#getECIEncoding--) | ECI kodlamasını belirler. |
| [getEncodeMode()](#getEncodeMode--) | DotCode kodlama modunu belirler. |
| [getRows()](#getRows--) | Satır sayısını belirler. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | DotCode yapılandırılmış ekleme modu barkodunun kimliğini belirler. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | DotCode yapılandırılmış ekleme modu barkod sayısını belirler. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Kodun, barkod okuyucusunu başlatma veya yeniden programlama talimatları olarak aşağıdaki verileri yorumlaması için okuyucuya talimat vermek amacıyla kullanılıp kullanılmadığını gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [setColumns(int value)](#setColumns-int-) | Sütun sayısını belirler. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI kodlamasını belirler. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | DotCode kodlama modunu belirler. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Kodun, barkod okuyucusunu başlatma veya yeniden programlama talimatları olarak aşağıdaki verileri yorumlaması için okuyucuya talimat vermek amacıyla kullanılıp kullanılmadığını gösterir. |
| [setRows(int value)](#setRows-int-) | Satır sayısını belirler. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | DotCode yapılandırılmış ekleme modu barkodunun kimliğini belirler. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | DotCode yapılandırılmış ekleme modu barkod sayısını belirler. |
| [toString()](#toString--) | Bu [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
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
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Sütun sayısını belirler. Bir DotCode sembolünün satır sayısı ile sütun sayısının toplamı tek olmalıdır. Sütun sayısı en az 5 olmalıdır. Varsayılan değer: -1

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI kodlamasını belirler. DotCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


DotCode kodlama modunu belirler. Varsayılan değer: Otomatik.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Satır sayısını belirler. Bir DotCode sembolünün satır sayısı ile sütun sayısının toplamı tek olmalıdır. Satır sayısı en az 5 olmalıdır. Varsayılan değer: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


DotCode yapılandırılmış ekleme modu barkodunun kimliğini belirler. Kimlik 1'den başlar ve barkod sayısına eşit ya da daha az olmalıdır. Varsayılan değer -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


DotCode yapılandırılmış ekleme modu barkod sayısını belirler. Varsayılan değer -1. Sayı 1 ile 35 arasında olmalıdır.

**Returns:**
int
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


Kodun, barkod okuyucusunu başlatma veya yeniden programlama talimatları olarak aşağıdaki verileri yorumlaması için okuyucuya talimat vermek amacıyla kullanılıp kullanılmadığını gösterir. Varsayılan değer false'tur.

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

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Sütun sayısını belirler. Bir DotCode sembolünün satır sayısı ile sütun sayısının toplamı tek olmalıdır. Sütun sayısı en az 5 olmalıdır. Varsayılan değer: -1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI kodlamasını belirler. DotCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


DotCode kodlama modunu belirler. Varsayılan değer: Otomatik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Kodun, barkod okuyucusunu başlatma veya yeniden programlama talimatları olarak aşağıdaki verileri yorumlaması için okuyucuya talimat vermek amacıyla kullanılıp kullanılmadığını gösterir. Varsayılan değer false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Satır sayısını belirler. Bir DotCode sembolünün satır sayısı ile sütun sayısının toplamı tek olmalıdır. Satır sayısı en az 5 olmalıdır. Varsayılan değer: -1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


DotCode yapılandırılmış ekleme modu barkodunun kimliğini belirler. Kimlik 1'den başlar ve barkod sayısına eşit ya da daha az olmalıdır. Varsayılan değer -1.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


DotCode yapılandırılmış ekleme modu barkod sayısını belirler. Varsayılan değer -1. Sayı 1 ile 35 arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### toString() {#toString--}
```
public String toString()
```


Bu [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) nesnesinin insan tarafından okunabilir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) nesnesini temsil eden bir dize.
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

