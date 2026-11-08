---
title: "HIBCPASCodetext"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Kelas untuk mengenkode dan mendekode teks yang tertanam dalam kode HIBC PAS."
type: docs
weight: 18
url: /id/java/com.aspose.barcode.complexbarcode/hibcpascodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class HIBCPASCodetext implements IComplexCodetext
```

Kelas untuk mengenkode dan mendekode teks yang tertanam dalam kode HIBC PAS.

--------------------

> ```
> This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.
>   
> 
>   HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
>   complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
>   complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
>   complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
>   complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
>   ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>   BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.HIBC_DATA_MATRIX_PAS);
>   reader.readBarCodes();
>   String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  	HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
>   System.out.println("Data location: {0}", readCodetext.getDataLocation());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[0].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[0].getData());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[1].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[1].getData());
>       }
>   }
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HIBCPASCodetext()](#HIBCPASCodetext--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addRecord(HIBCPASRecord record)](#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-) | Menambahkan catatan baru |
| [addRecord(int dataType, String data)](#addRecord-int-java.lang.String-) | Menambahkan catatan baru |
| [clear()](#clear--) | Menghapus daftar catatan |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai HIBCPASCodetext yang ditentukan. |
| [getBarcodeType()](#getBarcodeType--) | Mendapatkan tipe barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Menyusun codetext |
| [getDataLocation()](#getDataLocation--) | Mengidentifikasi lokasi data. |
| [getRecords()](#getRecords--) | Mendapatkan daftar catatan |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Menginisialisasi instance dari codetext yang telah disusun. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Mendapatkan atau mengatur tipe barcode. |
| [setDataLocation(int value)](#setDataLocation-int-) | Mengidentifikasi lokasi data. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCPASCodetext() {#HIBCPASCodetext--}
```
public HIBCPASCodetext()
```


### addRecord(HIBCPASRecord record) {#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-}
```
public void addRecord(HIBCPASRecord record)
```


Menambahkan catatan baru

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| record | [HIBCPASRecord](../../com.aspose.barcode.complexbarcode/hibcpasrecord) | Catatan yang akan ditambahkan |

### addRecord(int dataType, String data) {#addRecord-int-java.lang.String-}
```
public void addRecord(int dataType, String data)
```


Menambahkan catatan baru

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataType | int | Tipe data |
| data | java.lang.String | String data |

### clear() {#clear--}
```
public void clear()
```


Menghapus daftar catatan

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai HIBCPASCodetext yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai HIBCPASCodetext untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
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


Menyusun codetext

**Returns:**
java.lang.String - Kode teks yang dibangun
### getDataLocation() {#getDataLocation--}
```
public int getDataLocation()
```


Mengidentifikasi lokasi data.

**Returns:**
int
### getRecords() {#getRecords--}
```
public System.Collections.Generic.List<HIBCPASRecord> getRecords()
```


Mendapatkan daftar catatan

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.complexbarcode.HIBCPASRecord> - Daftar catatan
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash bilangan bulat bertanda 32-bit.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Menginisialisasi instance dari codetext yang telah disusun.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Kode teks yang dibangun. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Mendapatkan atau mengatur tipe barcode. Kode teks HIBC PAS dapat dienkode menggunakan HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS, dan HIBCQRPAS. Nilai default: HIBCCode39PAS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setDataLocation(int value) {#setDataLocation-int-}
```
public void setDataLocation(int value)
```


Mengidentifikasi lokasi data.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

