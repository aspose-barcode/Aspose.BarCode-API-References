---
title: "Adres"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Alacaklı veya borçlunun adresi."
type: docs
weight: 10
url: /tr/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Alacaklı veya borçlunun adresi.

Sokak, ev numarası, posta kodu ve kasaba (type  *structured address* ) ya da adres satırı 1 ve 2 (type  *combined address elements* ) ayarlayabilirsiniz. Tip, bu alanlardan herhangi biri ayarlandığında otomatik olarak belirlenir. Alanları ayarlamadan önce adres tipi  *undetermined* . Her iki tipin alanları ayarlanırsa, adres tipi  *conflicting* . İsim ve ülke kodu, tüm alanlar boş olmadıkça her zaman ayarlanmalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Address()](#Address--) | Adres örneği oluşturur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clear()](#clear--) | Tüm alanları temizler ve tipi  AddressType.Undetermined  olarak ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin geçerli nesneye eşit olup olmadığını belirler. |
| [getAddressLine1()](#getAddressLine1--) | Adres satırı 1'i alır. |
| [getAddressLine2()](#getAddressLine2--) | Adres satırı 2'yi alır. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | İki harfli ISO ülke kodunu alır. |
| [getHouseNo()](#getHouseNo--) | Ev numarasını alır. |
| [getName()](#getName--) | İsmi alır, doğal bir kişinin ad ve soyadı ya da tüzel bir kişinin şirket adı. |
| [getPostalCode()](#getPostalCode--) | Posta kodunu alır. |
| [getStreet()](#getStreet--) | Sokağı alır. |
| [getTown()](#getTown--) | Kasaba ya da şehri alır. |
| [getType()](#getType--) | Adres tipini alır. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodunu alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Adres satırı 1'i ayarlar. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Adres satırı 2'yi ayarlar. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | İki harfli ISO ülke kodunu ayarlar. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Ev numarasını ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | İsmi ayarlar, doğal bir kişinin ad ve soyadı ya da tüzel bir kişinin şirket adı. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Posta kodunu ayarlar. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Sokağı ayarlar. |
| [setTown(String value)](#setTown-java.lang.String-) | Kasaba ya da şehri ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Adres örneği oluşturur

### clear() {#clear--}
```
public void clear()
```


Tüm alanları temizler ve tipi  AddressType.Undetermined  olarak ayarlar.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin geçerli nesneye eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Geçerli nesneyle karşılaştırılacak nesne. |

**Returns:**
boolean -  true  eğer belirtilen nesne geçerli nesneye eşitse; aksi takdirde,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Adres satırı 1'i alır.

Adres satırı 1, sokak adı, ev numarası veya posta kutusunu içerir.

Bu alanı ayarlamak, adres tipini  AddressType.CombinedElements  olarak ayarlar, zaten  AddressType.Structured  ise,  AddressType.Conflicting .

Bu alan yalnızca birleşik öğe adresleri için kullanılır ve isteğe bağlıdır.

Değer: Adres satırı 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Adres satırı 2'yi alır.

Adres satırı 2, posta kodu ve kasabayı içerir.

Bu alanı ayarlamak, adres tipini  AddressType.CombinedElements  olarak ayarlar, zaten  AddressType.Structured  ise,  AddressType.Conflicting .

Bu alan yalnızca birleşik öğe adresleri için kullanılır. Bu tip için zorunludur.

Değer: Adres satırı 2.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


İki harfli ISO ülke kodunu alır.

Ülke kodu, tüm adres  null  veya boş değerler içermediği sürece zorunludur.

Değer: ISO ülke kodu.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Ev numarasını alır.

Bu alanı ayarlamak, adres tipini  AddressType.Structured  olarak ayarlar, zaten  AddressType.CombinedElements  ise,  AddressType.Conflicting .

Bu alan yalnızca yapılandırılmış adresler için kullanılır ve isteğe bağlıdır.

Değer: Ev numarası.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


İsmi alır, doğal bir kişinin ad ve soyadı ya da tüzel bir kişinin şirket adı.

Değer: İsim.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Posta kodunu alır.

Bu alanı ayarlamak, adres tipini  AddressType.Structured  olarak ayarlar, zaten  AddressType.CombinedElements  ise,  AddressType.Conflicting .

Bu alan yalnızca yapılandırılmış adresler için kullanılır. Bu tip için zorunludur.

Değer: Posta kodu.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Sokağı alır.

Sokak, ev numarası olmadan belirtilmelidir.

Bu alanı ayarlamak, adres tipini  AddressType.Structured  olarak ayarlar, zaten  AddressType.CombinedElements  ise,  AddressType.Conflicting .

Bu alan yalnızca yapılandırılmış adresler için kullanılır ve isteğe bağlıdır.

Değer: Sokak.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Kasaba ya da şehri alır.

Bu alanı ayarlamak, adres tipini  AddressType.Structured  olarak ayarlar, zaten  AddressType.CombinedElements  ise,  AddressType.Conflicting .

Bu alan yalnızca yapılandırılmış adresler için kullanılır. Bu tip için zorunludur.

Değer: Kasaba veya şehir.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Adres tipini alır.

Adres türü, ya sokak / ev numarası ya da adres satırı 1 ve 2 ayarlanarak otomatik olarak belirlenir. Alanlar ayarlanmadan önce, adres türü *Undetermined* durumundadır. Her iki türden alanlar ayarlanırsa, adres türü *Conflicting* olur.

Değer: Adres türü.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodunu alır.

**Returns:**
int - Geçerli nesne için bir karma kodu.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


Adres satırı 1'i ayarlar.

Adres satırı 1, sokak adı, ev numarası veya posta kutusunu içerir.

Bu alanı ayarlamak, adres tipini  AddressType.CombinedElements  olarak ayarlar, zaten  AddressType.Structured  ise,  AddressType.Conflicting .

Bu alan yalnızca birleşik öğe adresleri için kullanılır ve isteğe bağlıdır.

Değer: Adres satırı 1.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Adres satırı 2'yi ayarlar.

Adres satırı 2, posta kodu ve kasabayı içerir.

Bu alanı ayarlamak, adres tipini  AddressType.CombinedElements  olarak ayarlar, zaten  AddressType.Structured  ise,  AddressType.Conflicting .

Bu alan yalnızca birleşik öğe adresleri için kullanılır. Bu tip için zorunludur.

Değer: Adres satırı 2.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


İki harfli ISO ülke kodunu ayarlar.

Ülke kodu, tüm adres  null  veya boş değerler içermediği sürece zorunludur.

Değer: ISO ülke kodu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Ev numarasını ayarlar.

Bu alanı ayarlamak, adres tipini  AddressType.Structured  olarak ayarlar, zaten  AddressType.CombinedElements  ise,  AddressType.Conflicting .

Bu alan yalnızca yapılandırılmış adresler için kullanılır ve isteğe bağlıdır.

Değer: Ev numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


İsmi ayarlar, doğal bir kişinin ad ve soyadı ya da tüzel bir kişinin şirket adı.

Değer: İsim.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Posta kodunu ayarlar.

Bu alanı ayarlamak, adres tipini  AddressType.Structured  olarak ayarlar, zaten  AddressType.CombinedElements  ise,  AddressType.Conflicting .

Bu alan yalnızca yapılandırılmış adresler için kullanılır. Bu tip için zorunludur.

Değer: Posta kodu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Sokağı ayarlar.

Sokak, ev numarası olmadan belirtilmelidir.

Bu alanı ayarlamak, adres tipini  AddressType.Structured  olarak ayarlar, zaten  AddressType.CombinedElements  ise,  AddressType.Conflicting .

Bu alan yalnızca yapılandırılmış adresler için kullanılır ve isteğe bağlıdır.

Değer: Sokak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Kasaba ya da şehri ayarlar.

Bu alanı ayarlamak, adres tipini  AddressType.Structured  olarak ayarlar, zaten  AddressType.CombinedElements  ise,  AddressType.Conflicting .

Bu alan yalnızca yapılandırılmış adresler için kullanılır. Bu tip için zorunludur.

Değer: Kasaba veya şehir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

