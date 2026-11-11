---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Konstruktor LuminanceFrame. Menginisialisasi instance baru dari kelas LuminanceFrame tanpa padding antar baris. Jarak antara baris yang berdekatan sama dengan width"
type: docs
weight: 10
url: /id/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Menginisialisasi instance baru dari kelas [`LuminanceFrame`](../) tanpa padding antar baris. Jarak antara baris yang berdekatan sama dengan *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | Byte[] | Data luminansi yang berisi satu byte per piksel. |
| width | Int32 | Lebar frame dalam piksel. |
| height | Int32 | Tinggi frame dalam piksel. |
| rotationDegrees | Int32 | Rotasi searah jarum jam yang diperlukan untuk menampilkan frame dalam posisi tegak. Nilai yang didukung adalah 0, 90, 180, dan 270. Nilai default adalah 0. |

### Lihat Juga

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Menginisialisasi instance baru dari kelas [`LuminanceFrame`](../) dengan row stride yang ditentukan.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | Byte[] | Data luminansi yang berisi satu byte per piksel. |
| width | Int32 | Lebar frame dalam piksel. |
| height | Int32 | Tinggi frame dalam piksel. |
| rowStride | Int32 | Jarak dalam byte antara awal dua baris yang berdekatan. Nilai tidak dapat kurang dari *width*. |
| rotationDegrees | Int32 | Rotasi searah jarum jam yang diperlukan untuk menampilkan frame dalam posisi tegak. Nilai yang didukung adalah 0, 90, 180, dan 270. |

### Lihat Juga

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


