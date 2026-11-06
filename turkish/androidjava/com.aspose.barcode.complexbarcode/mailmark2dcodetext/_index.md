---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Royal Mail 2D Mailmark koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 23
url: /tr/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Royal Mail 2D Mailmark koduna gömülü metni kodlamak ve çözmek için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Mailmark2DCodetext sınıfının varsayılan örneğini oluştur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Barkod tipini alır. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Mailmark verilerinden kod metnini oluştur. |
| [getCustomerContent()](#getCustomerContent--) | Müşteri tarafından kullanılmak üzere isteğe bağlı alan. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Datamatrix barkodunun kodlama modu. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Tipi, Data Matrix barkodunun boyutunu tanımlar. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Teslimat Adresinin Posta Kodunu DPS ile içerir. İç bölgede ise Posta Kodu/DP aşağıdaki karakter sayısını içerir. |
| [getInformationTypeID()](#getInformationTypeID--) | Her ürün tipi için Royal Mail Mailmark barkod yükünü tanımlar. |
| [getItemID()](#getItemID--) | Tedarik Zinciri Kimliği içinde benzersiz öğeyi tanımlar. |
| [getRTSFlag()](#getRTSFlag--) | İade Gönderici hizmetinin hangi seviyesinin istendiğini gösteren bayrak. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | İade Gönderici Posta Kodunu içerir ancak DPS yoktur. |
| [getSupplyChainID()](#getSupplyChainID--) | Posta gönderiminde yer alan benzersiz müşteri grubunu tanımlar. |
| [getUPUCountryID()](#getUPUCountryID--) | UPU Ülke Kimliğini tanımlar. Maksimum uzunluk: 4 karakter. |
| [getVersionID()](#getVersionID--) | Barkod sürümünü her Bilgi Tipi Kimliği için ilgili olarak tanımlar. |
| [getclass()](#getclass--) | Öğenin sınıfını tanımlar. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Oluşturulmuş kod metninden Mailmark verilerini başlatır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Müşteri tarafından kullanılmak üzere isteğe bağlı alan. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix barkodunun kodlama modu. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark Tipi, Data Matrix barkodunun boyutunu tanımlar. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Teslimat Adresinin Posta Kodunu DPS ile içerir. İç bölgede ise Posta Kodu/DP aşağıdaki karakter sayısını içerir. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Her ürün tipi için Royal Mail Mailmark barkod yükünü tanımlar. |
| [setItemID(int value)](#setItemID-int-) | Tedarik Zinciri Kimliği içinde benzersiz öğeyi tanımlar. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | İade Gönderici hizmetinin hangi seviyesinin istendiğini gösteren bayrak. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | İade Gönderici Posta Kodunu içerir ancak DPS yoktur. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Posta gönderiminde yer alan benzersiz müşteri grubunu tanımlar. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | UPU Ülke Kimliğini tanımlar. Maksimum uzunluk: 4 karakter. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Barkod sürümünü her Bilgi Tipi Kimliği için ilgili olarak tanımlar. |
| [setclass(String value)](#setclass-java.lang.String-) | Öğenin sınıfını tanımlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Mailmark2DCodetext sınıfının varsayılan örneğini oluştur.

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
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Mailmark verilerinden kod metnini oluştur.

**Returns:**
java.lang.String - Oluşturulmuş kod metni
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Müşteri tarafından kullanılmak üzere isteğe bağlı alan. Türüne göre maksimum uzunluk: Tür 7: 6 karakter Tür 9: 45 karakter Tür 29: 25 karakter

**Returns:**
java.lang.String - Müşteri içeriği
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Datamatrix barkodunun kodlama modu. Varsayılan değer: DataMatrixEncodeMode.C40.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


2D Mailmark Tipi, Data Matrix barkodunun boyutunu tanımlar.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


Teslimat Adresinin Posta Kodu ve DPS'yi içerir. İç bölgelerde Posta Kodu/DP aşağıdaki karakter sayılarını içerir. Bölge (1 veya 2 karakter) İlçe (1 veya 2 karakter) Sektör (1 karakter) Birim (2 karakter) DPS (2 karakter). Posta Kodu ve DPS geçerli bir PAF® formatına uymalıdır.

**Returns:**
java.lang.String - DPS ile teslimat adresinin posta kodu
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Her ürün türü için Royal Mail Mailmark barkod yükünü tanımlar. Geçerli Değerler: '0' - Yerel Sıralı ve Sırasız 'A' - Çevrimiçi Posta 'B' - Faturalama 'C' - Konsolidasyon

**Returns:**
java.lang.String - Bilgi türü ID
### getItemID() {#getItemID--}
```
public int getItemID()
```


Tedarik Zinciri ID içinde benzersiz öğeyi tanımlar. Her Mailmark barkodu, en az 90 gün benzersiz şekilde tanımlanabilmesi için bir ID taşımalıdır. Maksimum değer: 99999999.

**Returns:**
int - Tedarik Zinciri ID içindeki öğe
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


İade Gönderici hizmetinin hangi seviyesinin istendiğini gösteren bayrak.

**Returns:**
java.lang.String - RTS Bayrağı
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Gönderenin Geri Dönüş Posta Kodunu içerir ancak DPS yoktur. PC (DPS olmadan) bir PAF® formatına uymalıdır.

**Returns:**
java.lang.String - DPS olmadan Gönderenin Geri Dönüş Posta Kodu
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Posta gönderiminde yer alan benzersiz müşteri grubunu tanımlar. Maksimum değer: 9999999.

**Returns:**
int - Tedarik zinciri ID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


UPU Ülke Kimliğini tanımlar. Maksimum uzunluk: 4 karakter.

**Returns:**
java.lang.String - Ülke ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Her Bilgi Türü ID için ilgili barkod sürümünü tanımlar. Geçerli Değerler: Şu anda '1'. '0' ve '2' ile '9' ve 'A' ile 'Z' arasında kalanlar potansiyel gelecek kullanım için ayrılmıştır.

**Returns:**
java.lang.String - Sürüm ID
### getclass() {#getclass--}
```
public String getclass()
```


Öğenin sınıfını tanımlar. Geçerli Değerler: '1' - 1C (Perakende) '2' - 2C (Perakende) '3' - Ekonomi (Perakende) '5' - Ertelenmiş (Perakende) '8' - Premium (Ağ Erişimi) '9' - Standart (Ağ Erişimi)

**Returns:**
java.lang.String - öğenin sınıfı
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




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


Müşteri tarafından kullanılmak üzere isteğe bağlı alan. Türüne göre maksimum uzunluk: Tür 7: 6 karakter Tür 9: 45 karakter Tür 29: 25 karakter

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Müşteri içeriği |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix barkodunun kodlama modu. Varsayılan değer: EncodeMode.C40.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Datamatrix barkodunun kodlama modu. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Tipi, Data Matrix barkodunun boyutunu tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Data Matrix barkodunun boyutu |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Teslimat Adresinin Posta Kodu ve DPS'yi içerir. İç bölgelerde Posta Kodu/DP aşağıdaki karakter sayılarını içerir. Bölge (1 veya 2 karakter) İlçe (1 veya 2 karakter) Sektör (1 karakter) Birim (2 karakter) DPS (2 karakter). Posta Kodu ve DPS geçerli bir PAF® formatına uymalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | DPS ile teslimat adresinin posta kodu |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Her ürün türü için Royal Mail Mailmark barkod yükünü tanımlar. Geçerli Değerler: '0' - Yerel Sıralı ve Sırasız 'A' - Çevrimiçi Posta 'B' - Faturalama 'C' - Konsolidasyon

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Bilgi türü ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Tedarik Zinciri ID içinde benzersiz öğeyi tanımlar. Her Mailmark barkodu, en az 90 gün benzersiz şekilde tanımlanabilmesi için bir ID taşımalıdır. Maksimum değer: 99999999.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Supply Chain ID içindeki öğe |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


İade Gönderici hizmetinin hangi seviyesinin istendiğini gösteren bayrak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Gönderenin Geri Dönüş Posta Kodunu içerir ancak DPS yoktur. PC (DPS olmadan) bir PAF® formatına uymalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Gönderen Posta Kodu'na Dön, ancak DPS yok |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Posta gönderiminde yer alan benzersiz müşteri grubunu tanımlar. Maksimum değer: 9999999.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Tedarik Zinciri Kimliği |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


UPU Ülke Kimliğini tanımlar. Maksimum uzunluk: 4 karakter.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Ülke Kimliği |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Her Bilgi Türü ID için ilgili barkod sürümünü tanımlar. Geçerli Değerler: Şu anda '1'. '0' ve '2' ile '9' ve 'A' ile 'Z' arasında kalanlar potansiyel gelecek kullanım için ayrılmıştır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Sürüm Kimliği |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Öğenin sınıfını tanımlar. Geçerli Değerler: '1' - 1C (Perakende) '2' - 2C (Perakende) '3' - Ekonomi (Perakende) '5' - Ertelenmiş (Perakende) '8' - Premium (Ağ Erişimi) '9' - Standart (Ağ Erişimi)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | öğenin sınıfı |

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

