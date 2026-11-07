---
title: "constructor"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "konstruktor. Menginisialisasi instance baru dari kelas LuminanceFrame tanpa padding antar baris. Jarak antara baris berdekatan sama dengan lebar dalam C++."
type: docs
weight: 600
url: /id/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


Menginisialisasi instance baru dari kelas [LuminanceFrame](../) tanpa padding antar baris. Jarak antara baris berdekatan sama dengan *width*.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Data luminansi yang berisi satu byte per piksel. |
| width | int32_t | Lebar frame dalam piksel. |
| height | int32_t | Tinggi frame dalam piksel. |
| rotationDegrees | int32_t | Rotasi searah jarum jam yang diperlukan untuk menampilkan frame dalam posisi tegak. Nilai yang didukung adalah 0, 90, 180, dan 270. Nilai default adalah 0. |

## Lihat Juga

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


Menginisialisasi instance baru dari kelas [LuminanceFrame](../) dengan row stride yang ditentukan.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Data luminansi yang berisi satu byte per piksel. |
| width | int32_t | Lebar frame dalam piksel. |
| height | int32_t | Tinggi frame dalam piksel. |
| rowStride | int32_t | Jarak dalam byte antara awal dua baris yang bersebelahan. Nilai tidak dapat kurang dari *width*. |
| rotationDegrees | int32_t | Rotasi searah jarum jam yang diperlukan untuk menampilkan bingkai secara tegak. Nilai yang didukung adalah 0, 90, 180, dan 270. |

## Lihat Juga

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
