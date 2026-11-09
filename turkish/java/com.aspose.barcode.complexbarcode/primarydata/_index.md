---
title: "PrimaryData"
second_title: "Aspose.BarCode for Java API Referansı"
description: "HIBC LIC birincil verilerini depolamak için sınıf."
type: docs
weight: 33
url: /tr/java/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

HIBC LIC birincil verilerini depolamak için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen  PrimaryData  değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Etiketleyici kimlik kodunun tarihini tanımlar. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Ürün veya katalog numarasını tanımlar. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Ölçü birimi kimliğini tanımlar. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | HIBC LIC spesifikasyonuna göre dize formatından birincil verileri örnekler. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Etiketleyici kimlik kodunun tarihini tanımlar. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Ürün veya katalog numarasını tanımlar. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Ölçü birimi kimliğini tanımlar. |
| [toString()](#toString--) | Verileri HIBC LIC spesifikasyonuna göre dize formatına dönüştürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen  PrimaryData  değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırmak için bir  PrimaryData  değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnek ile aynı değere sahipse; aksi takdirde,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


Etiketleyici kimlik kodunun tarihini tanımlar. Etiketleyici kimlik kodu 4 sembol alfasayısal bir dize olmalı ve ilk karakter her zaman alfabetik olmalıdır.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Ürün veya katalog numarasını tanımlar. Ürün veya katalog numarası en fazla 18 sembol uzunluğunda alfasayısal bir dize olmalıdır.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


Ölçü birimi kimliğini tanımlar. Ölçü birimi kimliği 0 ile 9 arasında bir tam sayı olmalıdır.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodu döndürür.

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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


HIBC LIC spesifikasyonuna göre dize formatından birincil verileri örnekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | Biçimlendirilmiş dize. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Etiketleyici kimlik kodunun tarihini tanımlar. Etiketleyici kimlik kodu 4 sembol alfasayısal bir dize olmalı ve ilk karakter her zaman alfabetik olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Ürün veya katalog numarasını tanımlar. Ürün veya katalog numarası en fazla 18 sembol uzunluğunda alfasayısal bir dize olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Ölçü birimi kimliğini tanımlar. Ölçü birimi kimliği 0 ile 9 arasında bir tam sayı olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### toString() {#toString--}
```
public String toString()
```


Verileri HIBC LIC spesifikasyonuna göre dize formatına dönüştürür.

**Returns:**
java.lang.String - Biçimlendirilmiş dize.
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

