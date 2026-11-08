---
title: "Quadrangle"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Menyimpan sekumpulan empat Point yang mewakili wilayah Quadrangle."
type: docs
weight: 39
url: /id/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Menyimpan sekumpulan empat Point yang mewakili wilayah Quadrangle.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Menginisialisasi instance baru dari kelas  Quadrangle  dengan titik-titik deskriptif. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [EMPTY](#EMPTY) | Mewakili kelas  Quadrangle  dengan propertinya yang belum diinisialisasi. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Menentukan apakah Quadrangle yang ditentukan berada di dalam atau berpotongan dengan kelas  Quadrangle  ini. |
| [contains(int x, int y)](#contains-int-int-) | Menentukan apakah titik yang ditentukan berada di dalam kelas  Quadrangle  ini. |
| [contains(Point pt)](#contains-java.awt.Point-) | Menentukan apakah  Point  yang ditentukan berada di dalam kelas  Quadrangle  ini. |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Menentukan apakah  Rectangle  yang ditentukan berada di dalam atau berpotongan dengan kelas  Quadrangle  ini. |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  Quadrangle  yang ditentukan. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Membuat  Rectangle  yang membatasi  Quadrangle  ini |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Mendapatkan titik sudut kiri-bawah  Point  dari wilayah  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Mendapatkan titik sudut kiri-atas  Point  dari wilayah  Quadrangle |
| [getRightBottom()](#getRightBottom--) | Mendapatkan titik sudut kanan-bawah  Point  dari wilayah  Quadrangle |
| [getRightTop()](#getRightTop--) | Mendapatkan titik sudut kanan-atas  Point  dari wilayah  Quadrangle |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isEmpty()](#isEmpty--) | Menguji apakah semua  Point s  dari  Quadrangle  ini memiliki nilai nol. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Mendapatkan titik sudut kiri-bawah  Point  dari wilayah  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Mendapatkan titik sudut kiri-atas  Point  dari wilayah  Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Mendapatkan titik sudut kanan-bawah  Point  dari wilayah  Quadrangle |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Mendapatkan titik sudut kanan-atas  Point  dari wilayah  Quadrangle |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari Quadrangle ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


Menginisialisasi instance baru dari kelas  Quadrangle  dengan titik-titik deskriptif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| leftTop | java.awt.Point | Sebuah Point yang merepresentasikan sudut kiri-atas dari Quadrangle. |
| rightTop | java.awt.Point | Sebuah Point yang merepresentasikan sudut kanan-atas dari Quadrangle. |
| rightBottom | java.awt.Point | Sebuah Point yang merepresentasikan sudut kanan-bawah dari Quadrangle. |
| leftBottom | java.awt.Point | Sebuah Point yang merepresentasikan sudut kiri-bawah dari Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Mewakili kelas  Quadrangle  dengan propertinya yang belum diinisialisasi.

Nilai: Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Menentukan apakah Quadrangle yang ditentukan berada di dalam atau berpotongan dengan kelas  Quadrangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Quadrangle yang akan diuji. |

**Returns:**
boolean - Mengembalikan **true** jika Quadrangle berada di dalam atau berpotongan dengan kelas Quadrangle ini; sebaliknya, **false**.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Menentukan apakah titik yang ditentukan berada di dalam kelas  Quadrangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat titik x. |
| y | int | Koordinat titik y. |

**Returns:**
boolean - Mengembalikan **true** jika point berada di dalam kelas Quadrangle ini; sebaliknya, **false**.
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Menentukan apakah  Point  yang ditentukan berada di dalam kelas  Quadrangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | java.awt.Point | Point yang akan diuji. |

**Returns:**
boolean - Mengembalikan **true** jika Point berada di dalam kelas Quadrangle ini; sebaliknya, **false**.
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Menentukan apakah  Rectangle  yang ditentukan berada di dalam atau berpotongan dengan kelas  Quadrangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | java.awt.Rectangle | Rectangle yang akan diuji. |

**Returns:**
boolean - Mengembalikan **true** jika Rectangle berada di dalam atau berpotongan dengan kelas Quadrangle ini; sebaliknya, **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  Quadrangle  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai Quadrangle untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Membuat  Rectangle  yang membatasi  Quadrangle  ini

**Returns:**
java.awt.Rectangle - mengembalikan Rectangle yang membatasi Quadrangle ini
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public Point getLeftBottom()
```


Mendapatkan titik sudut kiri-bawah  Point  dari wilayah  Quadrangle

Nilai: Titik kiri-bawah dari wilayah Quadrangle

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Mendapatkan titik sudut kiri-atas  Point  dari wilayah  Quadrangle

Nilai: Titik kiri-atas dari wilayah Quadrangle

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Mendapatkan titik sudut kanan-bawah  Point  dari wilayah  Quadrangle

Nilai: Titik kanan-bawah dari wilayah Quadrangle

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Mendapatkan titik sudut kanan-atas  Point  dari wilayah  Quadrangle

Nilai: Titik kanan-atas dari wilayah Quadrangle

**Returns:**
java.awt.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash bilangan bulat bertanda 32-bit.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Menguji apakah semua  Point s  dari  Quadrangle  ini memiliki nilai nol.

Nilai: Mengembalikan **true** jika semua Point dari Quadrangle ini memiliki nilai nol; jika tidak, **false**.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLeftBottom(Point value) {#setLeftBottom-java.awt.Point-}
```
public void setLeftBottom(Point value)
```


Mendapatkan titik sudut kiri-bawah  Point  dari wilayah  Quadrangle

Nilai: Titik kiri-bawah dari wilayah Quadrangle

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Mendapatkan titik sudut kiri-atas  Point  dari wilayah  Quadrangle

Nilai: Titik kiri-atas dari wilayah Quadrangle

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Mendapatkan titik sudut kanan-bawah  Point  dari wilayah  Quadrangle

Nilai: Titik kanan-bawah dari wilayah Quadrangle

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Mendapatkan titik sudut kanan-atas  Point  dari wilayah  Quadrangle

Nilai: Titik kanan-atas dari wilayah Quadrangle

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari Quadrangle ini.

**Returns:**
java.lang.String - String yang merepresentasikan Quadrangle ini.
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

