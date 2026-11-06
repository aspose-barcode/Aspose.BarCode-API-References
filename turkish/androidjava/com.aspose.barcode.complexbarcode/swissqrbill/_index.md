---
title: "SwissQRBill"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "SwissQR fatura verileri"
type: docs
weight: 35
url: /tr/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

SwissQR fatura verileri
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | ISO11649 alacaklı referansını ham bir dizeden, dizeyi "RF" ile ön ekleyerek ve 97 modülü kontrol toplamını ekleyerek oluşturur ve ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin geçerli nesneye eşit olup olmadığını belirler. |
| [getAccount()](#getAccount--) | Alacaklının hesap numarasını alır. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Alternatif ödeme şemalarını alır veya ayarlar. |
| [getAmount()](#getAmount--) | Ödeme tutarını alır. |
| [getBillInformation()](#getBillInformation--) | Ek yapılandırılmış fatura bilgilerini alır. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Alacaklı adresini alır. |
| [getCurrency()](#getCurrency--) | Ödeme para birimini alır. |
| [getDebtor()](#getDebtor--) | Borçlunun adresini alır. |
| [getReference()](#getReference--) | Alacaklının ödeme referansını alır. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Ek yapılandırılmamış mesajı alır. |
| [getVersion()](#getVersion--) | SwissQR fatura standardının sürümünü alır. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodunu alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Alacaklının hesap numarasını ayarlar. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Alternatif ödeme şemalarını alır veya ayarlar. |
| [setAmount(double value)](#setAmount-double-) | Ödeme tutarını ayarlar. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Ek yapılandırılmış fatura bilgilerini ayarlar. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Alacaklının adresini ayarlar. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Ödeme para birimini ayarlar. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Borçlunun adresini ayarlar. |
| [setReference(String value)](#setReference-java.lang.String-) | Alacaklının ödeme referansını ayarlar. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Ek yapılandırılmamış mesajı ayarlar. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | SwissQR fatura standardının sürümünü ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


ISO11649 alacaklı referansını ham bir dizeden, dizeyi "RF" ile ön ekleyerek ve 97 modülü kontrol toplamını ekleyerek oluşturur ve ayarlar.

Referanstan boşluk karakterleri kaldırılır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rawReference | java.lang.String | Ham referans. |

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
### getAccount() {#getAccount--}
```
public String getAccount()
```


Alacaklının hesap numarasını alır.

Hesap numaraları, İsviçre veya Lihtenştayn bankalarına ait geçerli IBAN'lar olmalıdır. Hesap numarasında boşluklara izin verilir.

Değer: Alacaklı hesap numarası.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Alternatif ödeme şemalarını alır veya ayarlar.

Maksimum iki parametreli şema izin verilir.

Değer: Alternatif ödeme şemaları.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Ödeme tutarını alır.

Geçerli değerler 0,01 ile 999.999.999,99 arasındadır.

Değer: Ödeme tutarı.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Ek yapılandırılmış fatura bilgilerini alır.

Değer: Yapılandırılmış fatura bilgileri.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreditor() {#getCreditor--}
```
public Address getCreditor()
```


Alacaklı adresini alır.

Değer: Alacaklı adresi.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Ödeme para birimini alır.

Geçerli değerler "CHF" ve "EUR".

Değer: Ödeme para birimi.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Borçlunun adresini alır.

Alacaklı isteğe bağlıdır. Eğer atlanırsa, bu alanı  null  olarak ayarlamak ya da tüm  null  veya boş değerleri içeren bir adres ayarlamak da kabul edilebilir.

Değer: Alacaklı adresi.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Alacaklının ödeme referansını alır.

Referans, SwissQR IBAN'ları için zorunludur, ör. CHxx30000xxxxxx ile CHxx31999xxxxx aralığındaki IBAN'lar.

Belirtilirse, referans ya geçerli bir SwissQR referansı (ISR referans formuna karşılık gelen) ya da ISO 11649'a göre geçerli bir alacaklı referansı ("RFxxxx") olmalıdır. İkisi de biçimlendirme için boşluk içerebilir.

Değer: Alacaklı ödeme referansı.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Ek yapılandırılmamış mesajı alır.

Değer: Yapılandırılmamış mesaj.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


SwissQR fatura standardının sürümünü alır.

Değer: SwissQR fatura standart sürümü.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
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




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


Alacaklının hesap numarasını ayarlar.

Hesap numaraları, İsviçre veya Lihtenştayn bankalarına ait geçerli IBAN'lar olmalıdır. Hesap numarasında boşluklara izin verilir.

Değer: Alacaklı hesap numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Alternatif ödeme şemalarını alır veya ayarlar.

Maksimum iki parametreli şema izin verilir.

Değer: Alternatif ödeme şemaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Ödeme tutarını ayarlar.

Geçerli değerler 0,01 ile 999.999.999,99 arasındadır.

Değer: Ödeme tutarı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Ek yapılandırılmış fatura bilgilerini ayarlar.

Değer: Yapılandırılmış fatura bilgileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Alacaklının adresini ayarlar.

Değer: Alacaklı adresi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Ödeme para birimini ayarlar.

Geçerli değerler "CHF" ve "EUR".

Değer: Ödeme para birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Borçlunun adresini ayarlar.

Alacaklı isteğe bağlıdır. Eğer atlanırsa, bu alanı  null  olarak ayarlamak ya da tüm  null  veya boş değerleri içeren bir adres ayarlamak da kabul edilebilir.

Değer: Alacaklı adresi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Alacaklının ödeme referansını ayarlar.

Referans, SwissQR IBAN'ları için zorunludur, ör. CHxx30000xxxxxx ile CHxx31999xxxxx aralığındaki IBAN'lar.

Belirtilirse, referans ya geçerli bir SwissQR referansı (ISR referans formuna karşılık gelen) ya da ISO 11649'a göre geçerli bir alacaklı referansı ("RFxxxx") olmalıdır. İkisi de biçimlendirme için boşluk içerebilir.

Değer: Alacaklı ödeme referansı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Ek yapılandırılmamış mesajı ayarlar.

Değer: Yapılandırılmamış mesaj.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


SwissQR fatura standardının sürümünü ayarlar.

Değer: SwissQR fatura standart sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion) |  |

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

