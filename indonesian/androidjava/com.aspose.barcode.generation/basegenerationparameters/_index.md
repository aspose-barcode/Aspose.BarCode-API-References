---
title: BaseGenerationParameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Parameter pembuatan gambar barcode.
type: docs
weight: 17
url: /id/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Parameter pembuatan gambar barcode.
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Menentukan berbagai jenis mode penyesuaian ukuran otomatis. |
| [getBackColor()](#getBackColor--) | Background color of the barcode image. |
| [getBarcode()](#getBarcode--) | Gets the  BarcodeParameters  that contains all barcode properties. |
| [getBorder()](#getBorder--) | Gets the  BorderParameters  that contains all configuration properties for barcode border. |
| [getCaptionAbove()](#getCaptionAbove--) | Keterangan Di Atas gambar BarCode. |
| [getCaptionBelow()](#getCaptionBelow--) | Keterangan Di Bawah gambar BarCode. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Parameter gambar. |
| [getImageHeight()](#getImageHeight--) | Tinggi gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | Lebar gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Mendapatkan resolusi gambar BarCode. |
| [getRotationAngle()](#getRotationAngle--) | Sudut rotasi gambar BarCode, diukur dalam derajat, e.g. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Mendapatkan nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Menentukan berbagai jenis mode penyesuaian ukuran otomatis. |
| [setBackColor(int value)](#setBackColor-int-) | Background color of the barcode image. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | Tinggi gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | Lebar gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Mengatur resolusi gambar BarCode. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Sudut rotasi gambar BarCode, diukur dalam derajat, e.g. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Mengatur nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Menentukan berbagai jenis mode penyesuaian ukuran otomatis. Nilai default: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


Warna latar belakang gambar barcode. Nilai default: Color.White. Lihat Color.

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Gets the  BarcodeParameters  that contains all barcode properties.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Gets the  BorderParameters  that contains all configuration properties for barcode border.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


Keterangan Di Atas gambar BarCode. Lihat CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Keterangan Di Bawah gambar BarCode. Lihat CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getImage() {#getImage--}
```
public ImageParameters getImage()
```


Parameter gambar. Lihat.

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


Tinggi gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


Lebar gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Mendapatkan resolusi gambar BarCode. Satu nilai untuk kedua dimensi. Nilai default: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


Sudut rotasi gambar BarCode, diukur dalam derajat, e.g. RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi. Jika RotationAngle TIDAK sama dengan 90, 180, 270, atau 0, hal ini dapat meningkatkan kesulitan pemindai untuk membaca gambar. Nilai default: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Returns:**
float
### getUseAntiAlias() {#getUseAntiAlias--}
```
public boolean getUseAntiAlias()
```


Mendapatkan nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar.

**Returns:**
boolean
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




### setAutoSizeMode(AutoSizeMode value) {#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-}
```
public void setAutoSizeMode(AutoSizeMode value)
```


Menentukan berbagai jenis mode penyesuaian ukuran otomatis. Nilai default: AutoSizeMode.NONE.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Warna latar belakang gambar barcode. Nilai default: Color.White. Lihat Color.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


Tinggi gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


Lebar gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Mengatur resolusi gambar BarCode. Satu nilai untuk kedua dimensi. Nilai default: 96 dpi.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


Sudut rotasi gambar BarCode, diukur dalam derajat, e.g. RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi. Jika RotationAngle TIDAK sama dengan 90, 180, 270, atau 0, hal ini dapat meningkatkan kesulitan pemindai untuk membaca gambar. Nilai default: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Mengatur nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

