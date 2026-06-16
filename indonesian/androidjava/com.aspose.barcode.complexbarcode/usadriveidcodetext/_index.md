---
title: USADriveIdCodetext
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode PDF417 Surat Izin Mengemudi USA.
type: docs
weight: 38
url: /id/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode PDF417 Surat Izin Mengemudi USA.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | Konstruktor default |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | Nomor Versi AAMVA 00-99 |
| [getBarcodeType()](#getBarcodeType--) | Mengembalikan tipe barcode dari USA DL (Pdf417) |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Membangun codetext dari data USA DL |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | Nomor ini secara unik mengidentifikasi yurisdiksi penerbit dan dapat diperoleh dengan menghubungi Otoritas Penerbit ISO (AAMVA). |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | Bidang Spesifik Yurisdiksi |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | Nomor Versi Yurisdiksi 00-99 |
| [getMandatoryElements()](#getMandatoryElements--) | Elemen (field) wajib pada kartu |
| [getNumberOfEntries()](#getNumberOfEntries--) | Nomor 00-99 subfile |
| [getOptionalElements()](#getOptionalElements--) | Elemen opsional (field) kartu |
| [getSubfileDesignator()](#getSubfileDesignator--) | Berisi informasi tentang subfile berikut, tipe, offset, dan panjang. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inisialisasi objek USA DL dari codetext |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | Menyimpan ke XML |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | Nomor Versi AAMVA 00-99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | Nomor ini secara unik mengidentifikasi yurisdiksi penerbit dan dapat diperoleh dengan menghubungi Otoritas Penerbit ISO (AAMVA). |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | Bidang Spesifik Yurisdiksi |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | Nomor Versi Yurisdiksi 00-99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | Elemen (field) wajib pada kartu |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | Nomor 00-99 subfile |
| [setOptionalElements(USADriveIdCodetext.OptionalFields value)](#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-) | Elemen opsional (field) kartu |
| [setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)](#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--) | Berisi informasi tentang subfile berikut, tipe, offset, dan panjang. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdCodetext() {#USADriveIdCodetext--}
```
public USADriveIdCodetext()
```


Konstruktor default

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAAMVAVersionNumber() {#getAAMVAVersionNumber--}
```
public final String getAAMVAVersionNumber()
```


Nomor Versi AAMVA 00-99

**Returns:**
java.lang.String
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Mengembalikan tipe barcode dari USA DL (Pdf417)

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type (Pdf417)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public final String getConstructedCodetext()
```


Membangun codetext dari data USA DL

**Returns:**
java.lang.String - Codetext yang dibangun
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


Nomor ini secara unik mengidentifikasi yurisdiksi penerbit dan dapat diperoleh dengan menghubungi Otoritas Penerbit ISO (AAMVA). IIN 6 digit lengkap harus dienkode.

**Returns:**
java.lang.String
### getJurisdictionSpecificSubfile() {#getJurisdictionSpecificSubfile--}
```
public final USADriveIdJurisdSubfile getJurisdictionSpecificSubfile()
```


Bidang Spesifik Yurisdiksi

**Returns:**
[USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile)
### getJurisdictionVersionNumber() {#getJurisdictionVersionNumber--}
```
public final String getJurisdictionVersionNumber()
```


Nomor Versi Yurisdiksi 00-99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


Elemen (field) wajib pada kartu

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


Nomor 00-99 subfile

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


Elemen opsional (field) kartu

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


Berisi informasi tentang subfile berikut, tipe, offset, dan panjang. Penting: hanya set tipe, offset dan panjang yang akan diatur secara otomatis.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public final void initFromString(String constructedCodetext)
```


Inisialisasi objek USA DL dari codetext

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Teks kode yang dibangun |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveToXml(OutputStream stream) {#saveToXml-java.io.OutputStream-}
```
public final void saveToXml(OutputStream stream)
```


Menyimpan ke XML

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream untuk disimpan |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


Nomor Versi AAMVA 00-99

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


Nomor ini secara unik mengidentifikasi yurisdiksi penerbit dan dapat diperoleh dengan menghubungi Otoritas Penerbit ISO (AAMVA). IIN 6 digit lengkap harus dienkode.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


Bidang Spesifik Yurisdiksi

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


Nomor Versi Yurisdiksi 00-99

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


Elemen (field) wajib pada kartu

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


Nomor 00-99 subfile

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


Elemen opsional (field) kartu

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


Berisi informasi tentang subfile berikut, tipe, offset, dan panjang. Penting: hanya set tipe, offset dan panjang yang akan diatur secara otomatis.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties> |  |

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

