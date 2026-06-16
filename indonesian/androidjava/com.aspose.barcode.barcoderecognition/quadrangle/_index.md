---
title: Quadrangle
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Menyimpan sekumpulan empat Point yang mewakili wilayah Quadrangle.
type: docs
weight: 43
url: /id/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Menyimpan sekumpulan empat  Point s yang mewakili wilayah  Quadrangle .
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Menginisialisasi instance baru dari struktur  Quadrangle  dengan titik-titik yang mendeskripsikannya. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [EMPTY](#EMPTY) | Mewakili kelas  Quadrangle  dengan propertinya yang belum diinisialisasi. |
## Methods

| Method | Deskripsi |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Menentukan apakah  Point  yang ditentukan berada di dalam kelas  Quadrangle  ini. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Menentukan apakah  Rectangle  yang ditentukan berada di dalam atau berpotongan dengan kelas  Quadrangle  ini. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Menentukan apakah  Quadrangle  yang ditentukan berada di dalam atau berpotongan dengan kelas  Quadrangle  ini. |
| [contains(int x, int y)](#contains-int-int-) | Menentukan apakah titik yang ditentukan berada di dalam kelas  Quadrangle  ini. |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  Quadrangle  yang ditentukan. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Membuat  Rectangle  yang membatasi Quadrangle ini |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Mendapatkan titik sudut kiri-bawah  Point  dari wilayah Quadrangle |
| [getLeftTop()](#getLeftTop--) | Mendapatkan sudut kiri-atas Point dari wilayah Quadrangle |
| [getRightBottom()](#getRightBottom--) | Mendapatkan sudut kanan-bawah Point dari wilayah Quadrangle |
| [getRightTop()](#getRightTop--) | Mendapatkan sudut kanan-atas Point dari wilayah Quadrangle |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isEmpty()](#isEmpty--) | Menguji apakah semua Point dari Quadrangle ini memiliki nilai nol. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Mendapatkan titik sudut kiri-bawah  Point  dari wilayah Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Mendapatkan sudut kiri-atas Point dari wilayah Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Mendapatkan sudut kanan-bawah Point dari wilayah Quadrangle |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Mendapatkan sudut kanan-atas Point dari wilayah Quadrangle |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari Quadrangle ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


Menginisialisasi instance baru dari struktur  Quadrangle  dengan titik-titik yang mendeskripsikannya.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| leftTop | android.graphics.Point | Sebuah Point yang merepresentasikan sudut kiri-atas dari Quadrangle. |
| rightTop | android.graphics.Point | Sebuah Point yang merepresentasikan sudut kanan-atas dari Quadrangle. |
| rightBottom | android.graphics.Point | Sebuah Point yang merepresentasikan sudut kanan-bawah dari Quadrangle. |
| leftBottom | android.graphics.Point | Sebuah Point yang merepresentasikan sudut kiri-bawah dari Quadrangle. |

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
### contains(Point pt) {#contains-android.graphics.Point-}
```
public boolean contains(Point pt)
```


Menentukan apakah  Point  yang ditentukan berada di dalam kelas  Quadrangle  ini.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| pt | android.graphics.Point | Point untuk diuji. |

**Returns:**
boolean - Mengembalikan **true** jika Point berada di dalam kelas Quadrangle ini; sebaliknya, **false**.
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Menentukan apakah  Rectangle  yang ditentukan berada di dalam atau berpotongan dengan kelas  Quadrangle  ini.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| rect | android.graphics.Rect | Rectangle untuk diuji. |

**Returns:**
boolean - Mengembalikan **true** jika Rectangle berada atau berpotongan dengan kelas Quadrangle ini; sebaliknya, **false**.
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Menentukan apakah  Quadrangle  yang ditentukan berada di dalam atau berpotongan dengan kelas  Quadrangle  ini.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Quadrangle untuk diuji. |

**Returns:**
boolean - Mengembalikan **true** jika Quadrangle berada atau berpotongan dengan kelas Quadrangle ini; sebaliknya, **false**.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Menentukan apakah titik yang ditentukan berada di dalam kelas  Quadrangle  ini.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat titik x. |
| y | int | Koordinat titik y. |

**Returns:**
boolean - Mengembalikan **true** jika titik berada di dalam kelas Quadrangle ini; jika tidak, **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  Quadrangle  yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai Quadrangle untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Membuat  Rectangle  yang membatasi Quadrangle ini

**Returns:**
android.graphics.Rect - mengembalikan Rectangle yang membatasi Quadrangle ini.
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


Mendapatkan titik sudut kiri-bawah  Point  dari wilayah Quadrangle

Nilai: Titik kiri-bawah Point dari wilayah Quadrangle.

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Mendapatkan sudut kiri-atas Point dari wilayah Quadrangle

Nilai: Titik kiri-atas Point dari wilayah Quadrangle.

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Mendapatkan sudut kanan-bawah Point dari wilayah Quadrangle

Nilai: Titik kanan-bawah Point dari wilayah Quadrangle.

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Mendapatkan sudut kanan-atas Point dari wilayah Quadrangle

Nilai: Titik kanan-atas Point dari wilayah Quadrangle.

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Menguji apakah semua Point dari Quadrangle ini memiliki nilai nol.

Nilai: Mengembalikan **true** jika semua Point pada Quadrangle ini memiliki nilai nol; jika tidak, **false**.

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




### setLeftBottom(Point value) {#setLeftBottom-android.graphics.Point-}
```
public void setLeftBottom(Point value)
```


Mendapatkan titik sudut kiri-bawah  Point  dari wilayah Quadrangle

Nilai: Titik kiri-bawah Point dari wilayah Quadrangle.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Mendapatkan sudut kiri-atas Point dari wilayah Quadrangle

Nilai: Titik kiri-atas Point dari wilayah Quadrangle.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Mendapatkan sudut kanan-bawah Point dari wilayah Quadrangle

Nilai: Titik kanan-bawah Point dari wilayah Quadrangle.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Mendapatkan sudut kanan-atas Point dari wilayah Quadrangle

Nilai: Titik kanan-atas Point dari wilayah Quadrangle.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari Quadrangle ini.

**Returns:**
java.lang.String - String yang mewakili Quadrangle ini.
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

