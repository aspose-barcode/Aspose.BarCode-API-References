---
title: "DotCodeParameters"
second_title: "Aspose.BarCode for Java API Referansı"
description: "DotCode parametreleri."
type: docs
weight: 34
url: /tr/java/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode parametreleri.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D BarCode modülünün Yükseklik/Genişlik oranı. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Sütun sayısını tanımlar. |
| [getECIEncoding()](#getECIEncoding--) | ECI kodlamasını tanımlar. |
| [getEncodeMode()](#getEncodeMode--) | DotCode kodlama modunu tanımlar. |
| [getRows()](#getRows--) | Satır sayısını tanımlar. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | DotCode yapılandırılmış ekleme modu barkodunun kimliğini tanımlar. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | DotCode yapılandırılmış ekleme modu barkod sayısını tanımlar. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Kodun, okuyucuya aşağıdaki verileri barkod okuyucusunun başlatılması veya yeniden programlanması için talimat olarak yorumlamasını söylemek amacıyla kullanılıp kullanılmadığını gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D BarCode modülünün Yükseklik/Genişlik oranı. |
| [setColumns(int value)](#setColumns-int-) | Sütun sayısını tanımlar. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI kodlamasını tanımlar. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | DotCode kodlama modunu tanımlar. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Kodun, okuyucuya aşağıdaki verileri barkod okuyucusunun başlatılması veya yeniden programlanması için talimat olarak yorumlamasını söylemek amacıyla kullanılıp kullanılmadığını gösterir. |
| [setRows(int value)](#setRows-int-) | Satır sayısını tanımlar. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | DotCode yapılandırılmış ekleme modu barkodunun kimliğini tanımlar. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | DotCode yapılandırılmış ekleme modu barkod sayısını tanımlar. |
| [toString()](#toString--) | Bu [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
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


2D BarCode modülünün Yükseklik/Genişlik oranı.

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


Sütun sayısını tanımlar. Bir DotCode sembolünün satır sayısı ile sütun sayısının toplamı tek olmalıdır. Sütun sayısı en az 5 olmalıdır. Varsayılan değer: -1

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI kodlamasını tanımlar. DotCodeEncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


DotCode kodlama modunu tanımlar. Varsayılan değer: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Satır sayısını tanımlar. Bir DotCode sembolünün satır sayısı ile sütun sayısının toplamı tek olmalıdır. Satır sayısı en az 5 olmalıdır. Varsayılan değer: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


DotCode yapılandırılmış ekleme modu barkodunun kimliğini tanımlar. Kimlik 1'den başlar ve barkod sayısına eşit ya da daha az olmalıdır. Varsayılan değer -1'dir.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


DotCode yapılandırılmış ekleme modu barkod sayısını tanımlar. Varsayılan değer -1'dir. Sayı 1 ile 35 arasında bir değer olmalıdır.

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


Kodun, okuyucuya aşağıdaki verileri barkod okuyucusunun başlatılması veya yeniden programlanması için talimat olarak yorumlamasını söylemek için kullanılıp kullanılmadığını gösterir. Varsayılan değer false'tur.

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


2D BarCode modülünün Yükseklik/Genişlik oranı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Sütun sayısını tanımlar. Bir DotCode sembolünün satır sayısı ile sütun sayısının toplamı tek olmalıdır. Sütun sayısı en az 5 olmalıdır. Varsayılan değer: -1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI kodlamasını tanımlar. DotCodeEncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


DotCode kodlama modunu tanımlar. Varsayılan değer: Auto.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Kodun, okuyucuya aşağıdaki verileri barkod okuyucusunun başlatılması veya yeniden programlanması için talimat olarak yorumlamasını söylemek için kullanılıp kullanılmadığını gösterir. Varsayılan değer false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Satır sayısını tanımlar. Bir DotCode sembolünün satır sayısı ile sütun sayısının toplamı tek olmalıdır. Satır sayısı en az 5 olmalıdır. Varsayılan değer: -1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


DotCode yapılandırılmış ekleme modu barkodunun kimliğini tanımlar. Kimlik 1'den başlar ve barkod sayısına eşit ya da daha az olmalıdır. Varsayılan değer -1'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


DotCode yapılandırılmış ekleme modu barkod sayısını tanımlar. Varsayılan değer -1'dir. Sayı 1 ile 35 arasında bir değer olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### toString() {#toString--}
```
public String toString()
```


Bu [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) nesnesinin insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) nesnesini temsil eden bir dizedir.
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

