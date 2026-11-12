---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Properti subfile USA DL, offset, dan panjang diatur secara otomatis."
type: docs
weight: 890
url: /id/nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

Properti subfile USA DL, offset, dan panjang diatur secara otomatis.

```js
new SubfileProperties()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getLength()](#getlength) | 4 Byte ini berisi nilai numerik 4 digit yang menentukan panjang Subfile dalam byte.Penentu segmen m |
| [getOffset()](#getoffset) | Nilai numerik 4 digit yang menentukan jumlah byte dari kepala atau awal file ke tempat data terkait |
| [getType()](#gettype) | Tipe subfile 2 byte, seperti "DL" |
| [setLength()](#setlength) | 4 Byte ini berisi nilai numerik 4 digit yang menentukan panjang Subfile dalam byte.Penentu segmen m |
| [setOffset()](#setoffset) | Nilai numerik 4 digit yang menentukan jumlah byte dari kepala atau awal file ke tempat data terkait |
| [setType()](#settype) | Tipe subfile 2 byte, seperti "DL" |

### getLength() {#getlength}

4 Byte ini berisi nilai numerik 4 digit yang menentukan panjang Subfile dalam byte.Penentu segmen harus termasuk dalam perhitungan panjang subfile.Penentu segmen = 1. Setiap subfile harus dimulai dengan Tipe Subfile dua karakter dan dua karakter ini juga harus termasuk dalam panjangnya.

### getOffset() {#getoffset}

Nilai numerik 4 digit yang menentukan jumlah byte dari kepala atau awal file ke tempat data yang terkait dengan sub-file tertentu berada.Byte pertama dalam file berada pada offset 0.

### getType() {#gettype}

Tipe subfile 2 byte, seperti "DL"

### setLength() {#setlength}

4 Byte ini berisi nilai numerik 4 digit yang menentukan panjang Subfile dalam byte.Penentu segmen harus termasuk dalam perhitungan panjang subfile.Penentu segmen = 1. Setiap subfile harus dimulai dengan Tipe Subfile dua karakter dan dua karakter ini juga harus termasuk dalam panjangnya.

### setOffset() {#setoffset}

Nilai numerik 4 digit yang menentukan jumlah byte dari kepala atau awal file ke tempat data yang terkait dengan sub-file tertentu berada.Byte pertama dalam file berada pada offset 0.

### setType() {#settype}

Tipe subfile 2 byte, seperti "DL"
