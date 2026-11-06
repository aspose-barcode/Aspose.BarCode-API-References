---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "HIBC LIC ikincil ve ek verileri depolamak için sınıf."
type: docs
weight: 34
url: /tr/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

HIBC LIC ikincil ve ek verileri depolamak için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen  SecondaryAndAdditionalData  değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | Üretim tarihini tanımlar. |
| [getExpiryDate()](#getExpiryDate--) | Son kullanım tarihini tanımlar. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Son kullanım tarihi formatını tanımlar. |
| [getLotNumber()](#getLotNumber--) | Lot veya parti numarasını tanımlar. |
| [getQuantity()](#getQuantity--) | Miktarı tanımlar, 0 ile 500 arasında tam sayı olmalıdır. |
| [getSerialNumber()](#getSerialNumber--) | Seri numarasını tanımlar. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | HIBC LIC spesifikasyonuna göre dize formatından ikincil ve ek destek verilerini örnekler. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | Üretim tarihini tanımlar. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | Son kullanım tarihini tanımlar. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | Son kullanım tarihi formatını tanımlar. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Lot veya parti numarasını tanımlar. |
| [setQuantity(int value)](#setQuantity-int-) | Miktarı tanımlar, 0 ile 500 arasında tam sayı olmalıdır. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Seri numarasını tanımlar. |
| [toString()](#toString--) | Verileri HIBC LIC spesifikasyonuna göre dize formatına dönüştürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen  SecondaryAndAdditionalData  değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırmak için bir  SecondaryAndAdditionalData  değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


Üretim tarihini tanımlar. Üretim tarihi, bu alanı kullanmamak için DateTime.MinValue olarak ayarlanabilir. Varsayılan değer: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


Son kullanım tarihini tanımlar. ExpiryDateFormat None olarak ayarlanmamışsa kullanılacaktır.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


Son kullanım tarihi formatını tanımlar.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


Lot veya parti numarasını tanımlar. Lot/parti numarası, en fazla 18 sembol uzunluğunda alfanümerik bir dize olmalıdır. .

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


Miktarı tanımlar, 0 ile 500 arasında tam sayı olmalıdır. Bu alanı kullanmamak için Miktar -1 olarak ayarlanabilir. Varsayılan değer: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


Seri numarasını tanımlar. Seri numarası, en fazla 18 sembol uzunluğunda alfanümerik bir dize olmalıdır.

**Returns:**
java.lang.String
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




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


HIBC LIC spesifikasyonuna göre dize formatından ikincil ve ek destek verilerini örnekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | Biçimlendirilmiş dize. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


Üretim tarihini tanımlar. Üretim tarihi, bu alanı kullanmamak için DateTime.MinValue olarak ayarlanabilir. Varsayılan değer: DateTime.MinValue

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


Son kullanım tarihini tanımlar. ExpiryDateFormat None olarak ayarlanmamışsa kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


Son kullanım tarihi formatını tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


Lot veya parti numarasını tanımlar. Lot/parti numarası, en fazla 18 sembol uzunluğunda alfanümerik bir dize olmalıdır. .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


Miktarı tanımlar, 0 ile 500 arasında tam sayı olmalıdır. Bu alanı kullanmamak için Miktar -1 olarak ayarlanabilir. Varsayılan değer: -1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


Seri numarasını tanımlar. Seri numarası, en fazla 18 sembol uzunluğunda alfanümerik bir dize olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

