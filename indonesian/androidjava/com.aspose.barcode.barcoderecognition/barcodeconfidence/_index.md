---
title: BarCodeConfidence
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Berisi tingkat kepercayaan pengenalan
type: docs
weight: 13
url: /id/androidjava/com.aspose.barcode.barcoderecognition/barcodeconfidence/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeConfidence
```

Berisi tingkat kepercayaan pengenalan

--------------------

> ```
> This sample shows how BarCodeConfidence changed, depending on barcode type
>  
>  //Moderate confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
>  //Strong confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.QR);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
> ```
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [MODERATE](#MODERATE) | Kepercayaan pengenalan barcode (kebanyakan barcode 1D) dengan checksum lemah atau bahkan tanpa checksum. |
| [NONE](#NONE) | Kepercayaan pengenalan barcode di mana teks kode tidak dikenali dengan benar atau barcode terdeteksi sebagai kemungkinan fakeBarCodeExtendedParameters. |
| [STRONG](#STRONG) | Kepercayaan pengenalan yang dikonfirmasi dengan kode BCH seperti Reed\\u2013Solomon. |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MODERATE {#MODERATE}
```
public static final int MODERATE
```


Kepercayaan pengenalan barcode (kebanyakan barcode 1D) dengan checksum lemah atau bahkan tanpa checksum. Dapat berisi beberapa kesalahan pengenalan pada teks kode atau bahkan pengenalan palsu jika nilainya rendah.

### NONE {#NONE}
```
public static final int NONE
```


Kepercayaan pengenalan barcode di mana teks kode tidak dikenali dengan benar atau barcode terdeteksi sebagai kemungkinan fakeBarCodeExtendedParameters.

### STRONG {#STRONG}
```
public static final int STRONG
```


Kepercayaan pengenalan yang dikonfirmasi dengan kode BCH seperti Reed\\u2013Solomon. Tidak boleh ada kesalahan pada teks kode yang dibaca atau pengenalan palsu.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

