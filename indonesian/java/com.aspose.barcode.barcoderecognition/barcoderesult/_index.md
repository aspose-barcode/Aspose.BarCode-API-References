---
title: "BarCodeResult"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Menyimpan data kode batang yang dikenali seperti tipe SingleDecodeType string codetext BarCodeRegionParameters region dan parameter lainnya"
type: docs
weight: 17
url: /id/java/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Menyimpan data barcode yang dikenali seperti tipe SingleDecodeType, string codetext, BarCodeRegionParameters region, dan parameter lainnya

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Membuat salinan dari kelas BarCodeResult. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan kelas BarCodeResult. |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai BarCodeResult yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Mendapatkan byte kode yang terenkode |
| [getCodeText()](#getCodeText--) | Mendapatkan teks kode |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | Mendapatkan teks kode dengan pengkodean. |
| [getCodeType()](#getCodeType--) | Mendapatkan tipe kode batang |
| [getCodeTypeName()](#getCodeTypeName--) | Mendapatkan nama tipe kode batang |
| [getConfidence()](#getConfidence--) | Mendapatkan tingkat kepercayaan pengenalan kode batang yang dikenali |
| [getExtended()](#getExtended--) | Mendapatkan parameter tambahan dari kode batang yang dikenali |
| [getReadingQuality()](#getReadingQuality--) | Mendapatkan kualitas pembacaan. |
| [getRegion()](#getRegion--) | Mendapatkan wilayah kode batang |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari BarCodeResult ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Membuat salinan dari kelas BarCodeResult.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Sebuah instance salinan BarCodeResult. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Membuat salinan kelas BarCodeResult.

**Returns:**
java.lang.Object - Mengembalikan salinan kelas BarCodeResult.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai BarCodeResult yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Sebuah nilai BarCodeResult untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


Mendapatkan byte kode yang terenkode

Nilai: Byte kode dari kode batang

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Mendapatkan teks kode

Nilai: Teks kode dari kode batang

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
```


Mendapatkan teks kode dengan pengkodean.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| charset | java.nio.charset.Charset | Pengkodean untuk codetext. |

**Returns:**
java.lang.String - Sebuah string yang berisi teks kode yang dikenali.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Mendapatkan tipe kode batang

Value: Informasi tipe dari barcode yang dikenali

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Mendapatkan nama tipe kode batang

Value: Nama tipe dari barcode yang dikenali

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


Mendapatkan tingkat kepercayaan pengenalan kode batang yang dikenali

Value:  BarCodeConfidence.Strong  tidak memiliki palsu atau kesalahan pengenalan,  BarCodeConfidence.Moderate  dapat kadang memiliki palsu atau kode teks yang salah karena tingkat kepercayaan ini untuk barcode dengan checksum lemah atau bahkan tanpa checksum,  BarCodeConfidence.None  selalu memiliki kode teks yang salah dan dapat menjadi pengenalan palsu

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Mendapatkan parameter tambahan dari kode batang yang dikenali

Value: Parameter tambahan dari barcode yang dikenali

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Mendapatkan kualitas pembacaan. Berfungsi untuk barcode 1D dan pos.

Value: Persentase kualitas pembacaan

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Mendapatkan wilayah kode batang

Value: Wilayah dari barcode yang dikenali

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash bilangan bulat bertanda 32-bit.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari BarCodeResult ini.

**Returns:**
java.lang.String - Sebuah string yang mewakili  BarCodeResult .
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

