---
title: HIBCLICCombinedCodetext
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama dan sekunder.
type: docs
weight: 14
url: /id/androidjava/com.aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICCombinedCodetext extends HIBCLICComplexCodetext
```

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama dan sekunder.

--------------------

> ```
> This sample shows how to encode and decode HIBC LIC using HIBCLICCombinedCodetext.
>  
> 
>  HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
>  combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
>  combinedCodetext.setPrimaryData(new PrimaryData());
>  combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
>  combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
>  combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
>  combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
>  combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
>  combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
>  combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
>  combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
>  combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
>  combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
>  ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
>  BufferedImage image = generator.generateBarCodeImage();
>  BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC);
>  reader.readBarCodes();
>  String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.tryDecodeHIBCLIC(codetext);
>  System.out.println("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
>  System.out.println("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
>  System.out.println("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
>  System.out.println("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
>  System.out.println("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
>  System.out.println("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
>  System.out.println("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
>  System.out.println("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
> ```
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [HIBCLICCombinedCodetext()](#HIBCLICCombinedCodetext--) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai HIBCLICCombinedCodetext yang ditentukan. |
| [getBarcodeType()](#getBarcodeType--) | Mendapatkan atau mengatur tipe barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Menyusun codetext |
| [getPrimaryData()](#getPrimaryData--) | Mengidentifikasi data utama. |
| [getSecondaryAndAdditionalData()](#getSecondaryAndAdditionalData--) | Mengidentifikasi data sekunder dan tambahan suplemental. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Menginisialisasi instance dari codetext yang disusun. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Mendapatkan atau mengatur tipe barcode. |
| [setPrimaryData(PrimaryData value)](#setPrimaryData-com.aspose.barcode.complexbarcode.PrimaryData-) | Mengidentifikasi data utama. |
| [setSecondaryAndAdditionalData(SecondaryAndAdditionalData value)](#setSecondaryAndAdditionalData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-) | Mengidentifikasi data sekunder dan tambahan suplemental. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICCombinedCodetext() {#HIBCLICCombinedCodetext--}
```
public HIBCLICCombinedCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai HIBCLICCombinedCodetext yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai HIBCLICCombinedCodetext untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Mendapatkan atau mengatur jenis barcode. Codetext HIBC LIC dapat dienkode menggunakan tipe encode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC.

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
java.lang.String - Codetext yang dibangun
### getPrimaryData() {#getPrimaryData--}
```
public PrimaryData getPrimaryData()
```


Mengidentifikasi data utama.

**Returns:**
[PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata)
### getSecondaryAndAdditionalData() {#getSecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData getSecondaryAndAdditionalData()
```


Mengidentifikasi data sekunder dan tambahan suplemental.

**Returns:**
[SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Menginisialisasi instance dari codetext yang disusun.

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




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Mendapatkan atau mengatur jenis barcode. Codetext HIBC LIC dapat dienkode menggunakan tipe encode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setPrimaryData(PrimaryData value) {#setPrimaryData-com.aspose.barcode.complexbarcode.PrimaryData-}
```
public void setPrimaryData(PrimaryData value)
```


Mengidentifikasi data utama.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata) |  |

### setSecondaryAndAdditionalData(SecondaryAndAdditionalData value) {#setSecondaryAndAdditionalData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-}
```
public void setSecondaryAndAdditionalData(SecondaryAndAdditionalData value)
```


Mengidentifikasi data sekunder dan tambahan suplemental.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata) |  |

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

