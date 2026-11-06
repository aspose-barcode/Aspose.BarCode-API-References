---
title: "BarCodeRegionParameters"
second_title: "Referensi API Aspose.BarCode untuk Android via Java"
description: "Mewakili wilayah barcode yang dikenali dan sudut barcode"
type: docs
weight: 16
url: /id/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Mewakili wilayah kode batang yang dikenali dan sudut kode batang

--------------------

> ```
> This sample shows how to get barcode Angle and bounding quadrangle values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>     System.out.println("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
>  }
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai BarCodeRegionParameters yang ditentukan. |
| [getAngle()](#getAngle--) | Mendapatkan sudut barcode (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Mendapatkan array Point yang membatasi wilayah barcode |
| [getQuadrangle()](#getQuadrangle--) | Mendapatkan Quadrangle Aspose.BarCode.BarCodeRecognition yang membatasi wilayah barcode |
| [getRectangle()](#getRectangle--) | Mendapatkan Rectangle System.Drawing yang membatasi wilayah barcode |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari BarCodeRegionParameters ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai BarCodeRegionParameters yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Mendapatkan sudut barcode (0-360).

Nilai: Sudut untuk barcode (0-360).

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


Mendapatkan array Point yang membatasi wilayah barcode

Nilai: Mengembalikan array Point yang membatasi wilayah barcode

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Mendapatkan Quadrangle Aspose.BarCode.BarCodeRecognition yang membatasi wilayah barcode

Nilai: Mengembalikan Quadrangle Aspose.BarCode.BarCodeRecognition yang membatasi wilayah barcode

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


Mendapatkan Rectangle System.Drawing yang membatasi wilayah barcode

Nilai: Mengembalikan Rectangle System.Drawing yang membatasi wilayah barcode

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
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


Mengembalikan representasi string yang dapat dibaca manusia dari BarCodeRegionParameters ini.

**Returns:**
java.lang.String - String yang mewakili BarCodeRegionParameters ini.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

