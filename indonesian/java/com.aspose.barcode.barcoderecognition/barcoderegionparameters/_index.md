---
title: "BarCodeRegionParameters"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Mewakili wilayah barcode yang dikenali dan sudut barcode"
type: docs
weight: 16
url: /id/java/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Mewakili wilayah barcode yang dikenali dan sudut barcode

--------------------

> ```
> This sample shows how to get barcode Angle and bounding quadrangle values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
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
| [getQuadrangle()](#getQuadrangle--) | Mendapatkan Aspose.BarCode.BarCodeRecognition.Quadrangle yang membatasi wilayah barcode |
| [getRectangle()](#getRectangle--) | Mendapatkan System.Drawing.Rectangle yang membatasi wilayah barcode |
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
java.awt.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Mendapatkan Aspose.BarCode.BarCodeRecognition.Quadrangle yang membatasi wilayah barcode

Nilai: Mengembalikan Aspose.BarCode.BarCodeRecognition.Quadrangle yang membatasi wilayah barcode

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Mendapatkan System.Drawing.Rectangle yang membatasi wilayah barcode

Nilai: Mengembalikan System.Drawing.Rectangle yang membatasi wilayah barcode

**Returns:**
java.awt.Rectangle
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


Mengembalikan representasi string yang dapat dibaca manusia dari BarCodeRegionParameters ini.

**Returns:**
java.lang.String - String yang mewakili BarCodeRegionParameters ini.
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

