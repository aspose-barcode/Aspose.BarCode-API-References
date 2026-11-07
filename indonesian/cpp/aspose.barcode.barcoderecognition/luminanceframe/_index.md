---
title: "Kelas Aspose::BarCode::BarCodeRecognition::LuminanceFrame"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::BarCodeRecognition::LuminanceFrame. Mewakili sebuah frame gambar skala abu-abu 8-bit. Setiap piksel direpresentasikan oleh satu byte yang berisi nilai luminansinya dalam C++."
type: docs
weight: 2400
url: /id/cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


Mewakili bingkai gambar grayscale 8-bit. Setiap piksel direpresentasikan oleh satu byte yang berisi nilai luminansinya.

```cpp
class LuminanceFrame : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Data](./get_data/)() const | Mendapatkan data luminansi. |
| [get_Height](./get_height/)() const | Mendapatkan tinggi frame dalam piksel. |
| [get_RotationDegrees](./get_rotationdegrees/)() const | Mendapatkan jumlah derajat rotasi frame searah jarum jam untuk mendapatkan orientasi yang benar. |
| [get_RowStride](./get_rowstride/)() const | Mendapatkan jarak dalam byte antara awal dua baris yang berdekatan. |
| [get_Width](./get_width/)() const | Mendapatkan lebar frame dalam piksel. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | Menginisialisasi sebuah instance baru dari kelas [LuminanceFrame](./) tanpa padding di antara baris. Jarak antara baris yang berdekatan sama dengan *width*. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | Menginisialisasi sebuah instance baru dari kelas [LuminanceFrame](./) dengan stride baris yang ditentukan. |
## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
