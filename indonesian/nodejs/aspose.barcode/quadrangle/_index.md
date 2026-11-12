---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menyimpan sekumpulan empat Point yang mewakili wilayah Quadrangle."
type: docs
weight: 850
url: /id/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

Menyimpan sekumpulan empat Point yang mewakili wilayah Quadrangle.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

Menginisialisasi instance baru dari struktur Quadrangle dengan titik-titik yang mendeskripsikannya.

| Parameter | Deskripsi |
| --- | --- |
| leftTop | Sebuah Point yang mewakili sudut kiri-atas dari Quadrangle. |
| rightTop | Sebuah Point yang mewakili sudut kanan-atas dari Quadrangle. |
| rightBottom | Sebuah Point yang mewakili sudut kanan-bawah dari Quadrangle. |
| leftBottom | Sebuah Point yang mewakili sudut kiri-bawah dari Quadrangle. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [contains(pt)](#contains) | Menentukan apakah Point yang ditentukan berada di dalam struktur Quadrangle ini. |
| [containsPoint(x, y)](#containspoint) | Menentukan apakah point yang ditentukan berada di dalam struktur Quadrangle ini. |
| [containsQuadrangle(quad)](#containsquadrangle) | Menentukan apakah Quadrangle yang ditentukan berada di dalam atau berpotongan dengan struktur Quadrangle ini. |
| [containsRectangle(rect)](#containsrectangle) | Menentukan apakah Rectangle yang ditentukan berada di dalam atau berpotongan dengan struktur Quadrangle ini. |
| [equals(other)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai Quadrangle yang ditentukan. |
| [getBoundingRectangle()](#getboundingrectangle) | Membuat Rectangle yang membatasi Quadrangle ini |
| [getLeftBottom()](#getleftbottom) | Mendapatkan Point sudut kiri-bawah dari wilayah Quadrangle Nilai: Sebuah Point sudut kiri-bawah dari wilayah Quadrangle |
| [getLeftTop()](#getlefttop) | Mendapatkan Point sudut kiri-atas dari wilayah Quadrangle Nilai: Sebuah Point sudut kiri-atas dari wilayah Quadrangle |
| [getRightBottom()](#getrightbottom) | Mendapatkan Point sudut kanan-bawah dari wilayah Quadrangle Nilai: Sebuah Point sudut kanan-bawah dari wilayah Quadrangle |
| [getRightTop()](#getrighttop) | Mendapatkan Point sudut kanan-atas dari wilayah Quadrangle Nilai: Sebuah Point sudut kanan-atas dari wilayah Quadrangle |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [isEmpty()](#isempty) | Menguji apakah semua Points dari Quadrangle ini memiliki nilai nol. Nilai: Mengembalikan true jika semua Points dari Quadrangle ini memiliki nilai nol; sebaliknya, false. |
| [setLeftBottom()](#setleftbottom) | Mengatur Point sudut kiri-bawah dari wilayah Quadrangle. Nilai: Point sudut kiri-bawah dari wilayah Quadrangle. |
| [setLeftTop()](#setlefttop) | Mengatur Point sudut kiri-atas dari wilayah Quadrangle. Nilai: Point sudut kiri-atas dari wilayah Quadrangle. |
| [setRightBottom()](#setrightbottom) | Mengatur Point sudut kanan-bawah dari wilayah Quadrangle. Nilai: Point sudut kanan-bawah dari wilayah Quadrangle. |
| [setRightTop()](#setrighttop) | Mengatur Point sudut kanan-atas dari wilayah Quadrangle. Nilai: Point sudut kanan-atas dari wilayah Quadrangle. |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari Quadrangle ini. |

### contains(pt) {#contains}

Menentukan apakah Point yang ditentukan berada di dalam struktur Quadrangle ini.

| Parameter | Deskripsi |
| --- | --- |
| pt | Point yang akan diuji. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

Menentukan apakah point yang ditentukan berada di dalam struktur Quadrangle ini.

| Parameter | Deskripsi |
| --- | --- |
| x | Koordinat titik x. |
| y | Koordinat titik y. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

Menentukan apakah Quadrangle yang ditentukan berada di dalam atau berpotongan dengan struktur Quadrangle ini.

| Parameter | Deskripsi |
| --- | --- |
| quad | Quadrangle yang akan diuji. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

Menentukan apakah Rectangle yang ditentukan berada di dalam atau berpotongan dengan struktur Quadrangle ini.

| Parameter | Deskripsi |
| --- | --- |
| rect | Rectangle yang akan diuji. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai Quadrangle yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| lainnya | Nilai Quadrangle untuk dibandingkan dengan instance ini. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

Membuat Rectangle yang membatasi Quadrangle ini

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Mendapatkan Point sudut kiri-bawah dari wilayah Quadrangle Nilai: Sebuah Point sudut kiri-bawah dari wilayah Quadrangle

### getLeftTop() {#getlefttop}

Mendapatkan Point sudut kiri-atas dari wilayah Quadrangle Nilai: Sebuah Point sudut kiri-atas dari wilayah Quadrangle

### getRightBottom() {#getrightbottom}

Mendapatkan Point sudut kanan-bawah dari wilayah Quadrangle Nilai: Sebuah Point sudut kanan-bawah dari wilayah Quadrangle

### getRightTop() {#getrighttop}

Mendapatkan Point sudut kanan-atas dari wilayah Quadrangle Nilai: Sebuah Point sudut kanan-atas dari wilayah Quadrangle

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Menguji apakah semua Points dari Quadrangle ini memiliki nilai nol. Nilai: Mengembalikan true jika semua Points dari Quadrangle ini memiliki nilai nol; jika tidak, false.

### setLeftBottom() {#setleftbottom}

Mengatur Point sudut kiri-bawah dari wilayah Quadrangle. Nilai: Point sudut kiri-bawah dari wilayah Quadrangle.

### setLeftTop() {#setlefttop}

Mengatur Point sudut kiri-atas dari wilayah Quadrangle. Nilai: Point sudut kiri-atas dari wilayah Quadrangle.

### setRightBottom() {#setrightbottom}

Mengatur Point sudut kanan-bawah dari wilayah Quadrangle. Nilai: Point sudut kanan-bawah dari wilayah Quadrangle.

### setRightTop() {#setrighttop}

Mengatur Point sudut kanan-atas dari wilayah Quadrangle. Nilai: Point sudut kanan-atas dari wilayah Quadrangle.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari Quadrangle ini.

**Returns:** A string that represents this Quadrangle.
