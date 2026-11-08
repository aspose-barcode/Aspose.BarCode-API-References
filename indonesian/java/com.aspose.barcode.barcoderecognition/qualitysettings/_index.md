---
title: "QualitySettings"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "QualitySettings memungkinkan konfigurasi kualitas dan kecepatan pengenalan secara manual."
type: docs
weight: 40
url: /id/java/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object
```
public final class QualitySettings
```

QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings menggunakan preset bawaan: HighPerformance, NormalQuality, HighQuality, MaxQuality atau Anda dapat mengkonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Memungkinkan mesin mengenali barcode yang memiliki checksum atau nilai yang tidak benar. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Mode yang memungkinkan metode mengenali elemen barcode dengan kualitas yang dipilih. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna. |
| [getDeconvolution()](#getDeconvolution--) | Mode dekonvolusi (pemulihan gambar) yang menentukan tingkat degradasi gambar. |
| [getHighPerformance()](#getHighPerformance--) | Preset kualitas pengenalan HighPerformance. |
| [getHighQuality()](#getHighQuality--) | Preset kualitas pengenalan HighQuality. |
| [getInverseImage()](#getInverseImage--) | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi). |
| [getMaxQuality()](#getMaxQuality--) | Preset kualitas pengenalan MaxQuality. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension. |
| [getNormalQuality()](#getNormalQuality--) | Preset kualitas pengenalan NormalQuality. |
| [getXDimension()](#getXDimension--) | Mode pengenalan yang menentukan ukuran (dari 1 hingga tak terhingga) elemen minimal barcode: sel matriks atau bar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Memungkinkan mesin mengenali barcode yang memiliki checksum atau nilai yang tidak benar. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Mode yang memungkinkan metode mengenali elemen barcode dengan kualitas yang dipilih. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Mode dekonvolusi (pemulihan gambar) yang menentukan tingkat degradasi gambar. |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi). |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Mode pengenalan yang menentukan ukuran (dari 1 hingga tak terhingga) elemen minimal barcode: sel matriks atau bar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Memungkinkan mesin mengenali barcode yang memiliki checksum atau nilai yang tidak benar. Mode ini dapat digunakan untuk mengenali barcode yang rusak dengan teks yang tidak tepat.

Value: Memungkinkan mesin mengenali barcode yang tidak benar.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Mode yang memungkinkan metode mengenali elemen barcode dengan kualitas yang dipilih. Elemen barcode dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat proses pengenalan.

Value: Mode yang memungkinkan metode mengenali elemen barcode dengan kualitas yang dipilih.

**Returns:**
[BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplexBackground() {#getComplexBackground--}
```
public ComplexBackgroundMode getComplexBackground()
```


Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna.

Value: Pengenalan tambahan barcode berwarna pada gambar berwarna.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Mode dekonvolusi (pemulihan gambar) yang menentukan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi yang dapat memulihkan gambar yang terdegradasi (konvolusi) oleh fungsi alami apa pun seperti blur, selama pengambilan gambar dengan kamera. Karena kami tidak dapat mendeteksi fungsi gambar yang merusak gambar, kami harus memeriksa fungsi-fungsi yang paling dikenal seperti penajaman atau morfologi matematis.

Value: Mode dekonvolusi yang menentukan tingkat degradasi gambar.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


Preset kualitas pengenalan HighPerformance. Kode batang berkualitas tinggi dikenali dengan baik dalam mode ini.

--------------------

> ```
> This sample shows how to use HighPerformance mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighPerformance());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Value: Preset kualitas pengenalan HighPerformance.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


Preset kualitas pengenalan HighQuality. Preset ini dikembangkan untuk kode batang berkualitas rendah. Memungkinkan mendeteksi kode batang yang sangat rusak.

--------------------

> ```
> This sample shows how to use HighQuality mode
>   
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Value: Preset kualitas pengenalan HighQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi).

Value: Pengenalan tambahan kode batang pada gambar dengan warna terbalik

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


Preset kualitas pengenalan MaxQuality. Preset ini dikembangkan untuk mengenali semua kode batang yang mungkin, bahkan kode batang yang tidak tepat.

--------------------

> ```
> This sample shows how to use MaxQuality mode
>   
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getMaxQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Value: Preset kualitas pengenalan MaxQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension.

Value: Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


Preset kualitas pengenalan NormalQuality. Cocok untuk sebagian besar kode batang

--------------------

> ```
> This sample shows how to use NormalQuality mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getNormalQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Value: Preset kualitas pengenalan NormalQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


Mode pengenalan yang menentukan ukuran (dari 1 hingga tak terhingga) elemen minimal barcode: sel matriks atau bar.

Value: ukuran (dari 1 hingga tak terhingga) elemen minimal kode batang: sel matriks atau bar.

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
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




### setAllowIncorrectBarcodes(boolean value) {#setAllowIncorrectBarcodes-boolean-}
```
public void setAllowIncorrectBarcodes(boolean value)
```


Memungkinkan mesin mengenali barcode yang memiliki checksum atau nilai yang tidak benar. Mode ini dapat digunakan untuk mengenali barcode yang rusak dengan teks yang tidak tepat.

Value: Memungkinkan mesin mengenali barcode yang tidak benar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Mode yang memungkinkan metode mengenali elemen barcode dengan kualitas yang dipilih. Elemen barcode dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat proses pengenalan.

Value: Mode yang memungkinkan metode mengenali elemen barcode dengan kualitas yang dipilih.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna.

Value: Pengenalan tambahan barcode berwarna pada gambar berwarna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Mode dekonvolusi (pemulihan gambar) yang menentukan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi yang dapat memulihkan gambar yang terdegradasi (konvolusi) oleh fungsi alami apa pun seperti blur, selama pengambilan gambar dengan kamera. Karena kami tidak dapat mendeteksi fungsi gambar yang merusak gambar, kami harus memeriksa fungsi-fungsi yang paling dikenal seperti penajaman atau morfologi matematis.

Value: Mode dekonvolusi yang menentukan tingkat degradasi gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi).

Value: Pengenalan tambahan kode batang pada gambar dengan warna terbalik

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension.

Value: Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Mode pengenalan yang menentukan ukuran (dari 1 hingga tak terhingga) elemen minimal barcode: sel matriks atau bar.

Value: ukuran (dari 1 hingga tak terhingga) elemen minimal kode batang: sel matriks atau bar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

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

