---
title: ComplexBarcodeGenerator
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: ComplexBarcodeGenerator untuk barcode kompleks backend, misalnya.
type: docs
weight: 12
url: /id/androidjava/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator untuk pembuatan gambar barcode kompleks backend (mis. SwissQR).

--------------------

> ```
> This sample shows how to create and save a SwissQR image.
>   
>     SwissQRCodetext swissQRCodetext = new SwissQRCodetext();
>     swissQRCodetext.getBill().setAccount("Account");
>     swissQRCodetext.getBill().setBillInformation("BillInformation");
>     // init rest of the fields
>     ComplexBarcodeGenerator cg = new ComplexBarcodeGenerator(swissQRCodetext);
>     BufferedImage res = cg.generateBarCodeImage();
> ```
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | Membuat sebuah instance dari ComplexBarcodeGenerator. |
## Methods

| Method | Deskripsi |
| --- | --- |
| [dispose()](#dispose--) | Membersihkan semua sumber daya yang sedang digunakan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | Menghasilkan gambar barcode kompleks dengan pengaturan saat ini. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | Parameter generasi. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Menghasilkan dan menyimpan gambar barcode kompleks dengan pengaturan saat ini. |
| [save(String filename)](#save-java.lang.String-) | Menghasilkan dan menyimpan gambar barcode kompleks dengan pengaturan saat ini. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Menghasilkan dan menyimpan gambar barcode kompleks dengan pengaturan saat ini. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


Membuat sebuah instance dari ComplexBarcodeGenerator.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | Teks kode kompleks |

### dispose() {#dispose--}
```
public void dispose()
```


Membersihkan semua sumber daya yang sedang digunakan.

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
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Menghasilkan gambar barcode kompleks dengan pengaturan saat ini.

**Returns:**
android.graphics.Bitmap - Gambar barcode. Lihat Bitmap.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Parameter generasi.

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream, BarCodeImageFormat format) {#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(OutputStream stream, BarCodeImageFormat format)
```


Menghasilkan dan menyimpan gambar barcode kompleks dengan pengaturan saat ini.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Keluaran System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Menentukan format file dari gambar keluaran. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Menghasilkan dan menyimpan gambar barcode kompleks dengan pengaturan saat ini.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Jalur untuk menyimpan. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Menghasilkan dan menyimpan gambar barcode kompleks dengan pengaturan saat ini.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Jalur untuk menyimpan. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Menentukan format file dari gambar keluaran. |

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

