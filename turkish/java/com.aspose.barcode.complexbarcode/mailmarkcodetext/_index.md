---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode for Java API Referansı"
description: "4 durumlu Royal Mailmark koduna gömülü metni kodlamak ve kodunu çözmek için sınıf."
type: docs
weight: 24
url: /tr/java/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

4 durumlu Royal Mailmark koduna gömülü metni kodlamak ve kodunu çözmek için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | MailmarkCodetext sınıfının yeni bir örneğini başlatır. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Barkod tipini alır. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Boş veya Test "1" - 1C (Perakende) "2" - 2C (Perakende) "3" - 3C (Perakende) "4" - Premium (RetailPublishing Mail) (potansiyel gelecekteki kullanım için) "5" - Ertelenmiş (Perakende) "6" - Hava (Perakende) (potansiyel gelecekteki kullanım için) "7" - Yüzey (Perakende) (potansiyel gelecekteki kullanım için) "8" - Premium (Ağ Erişimi) "9" - Standart (Ağ Erişimi) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Mailmark verilerinden kod metni oluştur. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | PC ve DP, PAF formatına uymalıdır. |
| [getFormat()](#getFormat--) | "0" \u2013 Boş veya Test "1" \u2013 Mektup "2" \u2013 Büyük Mektup |
| [getItemID()](#getItemID--) | Maksimum değer 99999999'dur. |
| [getSupplychainID()](#getSupplychainID--) | Maksimum değerler Barcode C için 99 ve Barcode L için 999999'dur. |
| [getVersionID()](#getVersionID--) | Şu anda "1" \\u2013 Mailmark barkod için (0 ve 2'den 9'a ve A'dan Z'ye gelecekte kullanım için ayrılmış) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Oluşturulmuş kod metninden Mailmark verilerini başlatır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Boş veya Test "1" - 1C (Perakende) "2" - 2C (Perakende) "3" - 3C (Perakende) "4" - Premium (RetailPublishing Mail) (potansiyel gelecekteki kullanım için) "5" - Ertelenmiş (Perakende) "6" - Hava (Perakende) (potansiyel gelecekteki kullanım için) "7" - Yüzey (Perakende) (potansiyel gelecekteki kullanım için) "8" - Premium (Ağ Erişimi) "9" - Standart (Ağ Erişimi) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | PC ve DP, PAF formatına uymalıdır. |
| [setFormat(int value)](#setFormat-int-) | "0" \u2013 Boş veya Test "1" \u2013 Mektup "2" \u2013 Büyük Mektup |
| [setItemID(int value)](#setItemID-int-) | Maksimum değer 99999999'dur. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Maksimum değerler Barcode C için 99 ve Barcode L için 999999'dur. |
| [setVersionID(int value)](#setVersionID-int-) | Şu anda "1" \\u2013 Mailmark barkod için (0 ve 2'den 9'a ve A'dan Z'ye gelecekte kullanım için ayrılmış) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


MailmarkCodetext sınıfının yeni bir örneğini başlatır.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Barkod tipini alır.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Boş veya Test "1" - 1C (Perakende) "2" - 2C (Perakende) "3" - 3C (Perakende) "4" - Premium (RetailPublishing Mail) (potansiyel gelecekteki kullanım için) "5" - Ertelenmiş (Perakende) "6" - Hava (Perakende) (potansiyel gelecekteki kullanım için) "7" - Yüzey (Perakende) (potansiyel gelecekteki kullanım için) "8" - Premium (Ağ Erişimi) "9" - Standart (Ağ Erişimi)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Mailmark verilerinden kod metni oluştur.

**Returns:**
java.lang.String - Oluşturulmuş kod metni
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


PC ve DP, PAF formatına uymalıdır. Uluslararası "XY11 " (5 boşluklu son) gösteren dokuz karakterlik dize veya yerel sıralama kodunu belirten bir karakter deseni. Yerel sıralama kodu, dış posta kodu, iç posta kodu ve Teslim Noktası Soneki içerir.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \u2013 Boş veya Test "1" \u2013 Mektup "2" \u2013 Büyük Mektup

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


Maksimum değer 99999999'dur.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Maksimum değerler Barcode C için 99 ve Barcode L için 999999'dur.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


Şu anda "1" \\u2013 Mailmark barkod için (0 ve 2'den 9'a ve A'dan Z'ye gelecekte kullanım için ayrılmış)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Oluşturulmuş kod metninden Mailmark verilerini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Oluşturulmuş kod metni. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Boş veya Test "1" - 1C (Perakende) "2" - 2C (Perakende) "3" - 3C (Perakende) "4" - Premium (RetailPublishing Mail) (potansiyel gelecekteki kullanım için) "5" - Ertelenmiş (Perakende) "6" - Hava (Perakende) (potansiyel gelecekteki kullanım için) "7" - Yüzey (Perakende) (potansiyel gelecekteki kullanım için) "8" - Premium (Ağ Erişimi) "9" - Standart (Ağ Erişimi)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


PC ve DP, PAF formatına uymalıdır. Uluslararası "XY11 " (5 boşluklu son) gösteren dokuz karakterlik dize veya yerel sıralama kodunu belirten bir karakter deseni. Yerel sıralama kodu, dış posta kodu, iç posta kodu ve Teslim Noktası Soneki içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \u2013 Boş veya Test "1" \u2013 Mektup "2" \u2013 Büyük Mektup

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Maksimum değer 99999999'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Maksimum değerler Barcode C için 99 ve Barcode L için 999999'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


Şu anda "1" \\u2013 Mailmark barkod için (0 ve 2'den 9'a ve A'dan Z'ye gelecekte kullanım için ayrılmış)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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

