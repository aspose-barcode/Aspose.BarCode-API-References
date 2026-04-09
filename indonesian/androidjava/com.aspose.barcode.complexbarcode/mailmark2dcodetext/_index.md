---
title: Mailmark2DCodetext
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mail 2D Mailmark.
type: docs
weight: 23
url: /id/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mail 2D Mailmark.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Mendapatkan tipe barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | Bendera yang menunjukkan tingkat layanan Return to Sender yang diminta. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Berisi Kode Pos Return to Sender tetapi tidak ada DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. |
| [getUPUCountryID()](#getUPUCountryID--) | Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter. |
| [getVersionID()](#getVersionID--) | Mengidentifikasi versi barcode yang relevan untuk setiap ID Tipe Informasi. |
| [getclass()](#getclass--) | Mengidentifikasi kelas item. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes Mailmark data from constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optional space for use by customer. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [setItemID(int value)](#setItemID-int-) | Identifies the unique item within the Supply Chain ID. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Bendera yang menunjukkan tingkat layanan Return to Sender yang diminta. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Berisi Kode Pos Return to Sender tetapi tidak ada DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Mengidentifikasi versi barcode yang relevan untuk setiap ID Tipe Informasi. |
| [setclass(String value)](#setclass-java.lang.String-) | Mengidentifikasi kelas item. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Create default instance of Mailmark2DCodetext class.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Mendapatkan tipe barcode.

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


Construct codetext from Mailmark data.

**Returns:**
java.lang.String - Codetext yang dibangun
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Ruang opsional untuk digunakan oleh pelanggan. Panjang maksimum per Tipe: Tipe 7: 6 karakter Tipe 9: 45 karakter Tipe 29: 25 karakter

**Returns:**
java.lang.String - Konten pelanggan
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Mode enkode barcode Datamatrix. Nilai default: DataMatrixEncodeMode.C40.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


2D Mailmark Type defines size of Data Matrix barcode.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


Berisi Kode Pos Alamat Pengiriman dengan DPS. Jika di daratan, Postcode/DP berisi jumlah karakter berikut. Area (1 atau 2 karakter) Distrik (1 atau 2 karakter) Sektor (1 karakter) Unit (2 karakter) DPS (2 karakter). Kode Pos dan DPS harus mematuhi format PAF® yang valid.

**Returns:**
java.lang.String - Kode Pos Alamat Pengiriman dengan DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Mengidentifikasi muatan barcode Royal Mail Mailmark untuk setiap tipe produk. Nilai yang valid: '0' - Domestik Terurut & Tidak Terurut 'A' - Pos Online 'B' - Franking 'C' - Konsolidasi

**Returns:**
java.lang.String - ID tipe informasi
### getItemID() {#getItemID--}
```
public int getItemID()
```


Mengidentifikasi item unik dalam ID Rantai Pasokan. Setiap barcode Mailmark harus membawa ID sehingga dapat diidentifikasi secara unik setidaknya selama 90 hari. Nilai maksimum: 99999999.

**Returns:**
int - item dalam ID Rantai Pasokan
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Bendera yang menunjukkan tingkat layanan Return to Sender yang diminta.

**Returns:**
java.lang.String - Bendera RTS
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Berisi Kode Pos Return to Sender tetapi tidak ada DPS. PC (tanpa DPS) harus mematuhi format PAF®.

**Returns:**
java.lang.String - Kode Pos Return to Sender tanpa DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. Nilai maksimum: 9999999.

**Returns:**
int - ID rantai pasokan
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter.

**Returns:**
java.lang.String - ID Negara
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Mengidentifikasi versi barcode yang relevan untuk setiap ID Tipe Informasi. Nilai yang valid: Saat ini '1'. '0' & '2' sampai '9' dan 'A' sampai 'Z' cadangan untuk penggunaan potensial di masa depan.

**Returns:**
java.lang.String - ID Versi
### getclass() {#getclass--}
```
public String getclass()
```


Mengidentifikasi kelas item. Nilai yang valid: '1' - 1C (Ritel) '2' - 2C (Ritel) '3' - Ekonomi (Ritel) '5' - Tertunda (Ritel) '8' - Premium (Akses Jaringan) '9' - Standar (Akses Jaringan)

**Returns:**
java.lang.String - kelas item
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


Initializes Mailmark data from constructed codetext.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Codetext yang dibangun. |

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


Ruang opsional untuk digunakan oleh pelanggan. Panjang maksimum per Tipe: Tipe 7: 6 karakter Tipe 9: 45 karakter Tipe 29: 25 karakter

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Konten pelanggan |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Mode enkode barcode Datamatrix. Nilai default: EncodeMode.C40.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Ukuran barcode Data Matrix |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Berisi Kode Pos Alamat Pengiriman dengan DPS. Jika di daratan, Postcode/DP berisi jumlah karakter berikut. Area (1 atau 2 karakter) Distrik (1 atau 2 karakter) Sektor (1 karakter) Unit (2 karakter) DPS (2 karakter). Kode Pos dan DPS harus mematuhi format PAF® yang valid.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Kode pos dari Alamat Pengiriman dengan DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Mengidentifikasi muatan barcode Royal Mail Mailmark untuk setiap tipe produk. Nilai yang valid: '0' - Domestik Terurut & Tidak Terurut 'A' - Pos Online 'B' - Franking 'C' - Konsolidasi

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | ID tipe informasi |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Mengidentifikasi item unik dalam ID Rantai Pasokan. Setiap barcode Mailmark harus membawa ID sehingga dapat diidentifikasi secara unik setidaknya selama 90 hari. Nilai maksimum: 99999999.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | item dalam ID Rantai Pasokan |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Bendera yang menunjukkan tingkat layanan Return to Sender yang diminta.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Berisi Kode Pos Return to Sender tetapi tidak ada DPS. PC (tanpa DPS) harus mematuhi format PAF®.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Kode Pos Pengembalian ke Pengirim tetapi tanpa DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. Nilai maksimum: 9999999.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | ID rantai pasokan |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | ID negara |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Mengidentifikasi versi barcode yang relevan untuk setiap ID Tipe Informasi. Nilai yang valid: Saat ini '1'. '0' & '2' sampai '9' dan 'A' sampai 'Z' cadangan untuk penggunaan potensial di masa depan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | ID versi |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Mengidentifikasi kelas item. Nilai yang valid: '1' - 1C (Ritel) '2' - 2C (Ritel) '3' - Ekonomi (Ritel) '5' - Tertunda (Ritel) '8' - Premium (Akses Jaringan) '9' - Standar (Akses Jaringan)

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | kelas dari item |

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

