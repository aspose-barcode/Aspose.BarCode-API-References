---
title: HIBCLICPrimaryDataCodetext
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama.
type: docs
weight: 16
url: /id/androidjava/com.aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICPrimaryDataCodetext extends HIBCLICComplexCodetext
```

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama.

--------------------

> ```
> This sample shows how to encode and decode HIBC LIC using HIBCLICPrimaryDataCodetext.
>  
>  HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
>  complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
>  complexCodetext.setData(new PrimaryData());
>  complexCodetext.getData().setProductOrCatalogNumber("12345");
>  complexCodetext.getData().setLabelerIdentificationCode("A999");
>  complexCodetext.getData().setUnitOfMeasureID(1);
>  ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>  {
>      BufferedImage image = generator.generateBarCodeImage();
>      BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC);
>      {
>          reader.readBarCodes();
>          HIBCLICPrimaryCodetext result = (HIBCLICPrimaryCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
>          HIBCLICPrimaryCodetext result = (HIBCLICPrimaryCodetext)ComplexCodetextReader.tryDecodeHIBCLIC(codetext);
>          System.out.println("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
>          System.out.println("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
>          System.out.println("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
>      }
>  }
> ```
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [HIBCLICPrimaryDataCodetext()](#HIBCLICPrimaryDataCodetext--) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  HIBCLICPrimaryDataCodetext  yang ditentukan. |
| [getBarcodeType()](#getBarcodeType--) | Mendapatkan atau mengatur tipe barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Menyusun codetext |
| [getData()](#getData--) | Mengidentifikasi data utama. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Menginisialisasi instance dari codetext yang disusun. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Mendapatkan atau mengatur tipe barcode. |
| [setData(PrimaryData value)](#setData-com.aspose.barcode.complexbarcode.PrimaryData-) | Mengidentifikasi data utama. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICPrimaryDataCodetext() {#HIBCLICPrimaryDataCodetext--}
```
public HIBCLICPrimaryDataCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  HIBCLICPrimaryDataCodetext  yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai  HIBCLICPrimaryDataCodetext  untuk dibandingkan dengan instance ini. |

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
### getData() {#getData--}
```
public PrimaryData getData()
```


Mengidentifikasi data utama.

**Returns:**
[PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata)
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

### setData(PrimaryData value) {#setData-com.aspose.barcode.complexbarcode.PrimaryData-}
```
public void setData(PrimaryData value)
```


Mengidentifikasi data utama.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata) |  |

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

