---
title: "Aspose::BarCode::Generation::Unit class"
linktitle: "Unit"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Generation::Unit class. Menentukan nilai ukuran dalam berbagai satuan (Pixel, Inches, dll.) dalam C++."
type: docs
weight: 5000
url: /id/cpp/aspose.barcode.generation/unit/
---
## Unit class


Menentukan nilai ukuran dalam berbagai satuan (Pixel, Inci, dll.).

```cpp
class Unit : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Menentukan apakah instance ini dan objek yang ditentukan, yang juga harus berupa objek [Unit](./), memiliki nilai yang sama. |
| [get_Document](./get_document/)() | Mendapatkan nilai ukuran dalam satuan dokumen. |
| [get_Inches](./get_inches/)() | Mendapatkan nilai ukuran dalam inci. |
| [get_Millimeters](./get_millimeters/)() | Mendapatkan nilai ukuran dalam milimeter. |
| [get_Pixels](./get_pixels/)() | Mendapatkan nilai ukuran dalam piksel. |
| [get_Point](./get_point/)() | Mendapatkan nilai ukuran dalam poin. |
| [get_Resolution](./get_resolution/)() const | Resolusi |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk objek ini. |
| [set_Document](./set_document/)(float) | Mengatur nilai ukuran dalam satuan dokumen. |
| [set_Inches](./set_inches/)(float) | Mengatur nilai ukuran dalam inci. |
| [set_Millimeters](./set_millimeters/)(float) | Mengatur nilai ukuran dalam milimeter. |
| [set_Pixels](./set_pixels/)(float) | Mengatur nilai ukuran dalam piksel. |
| [set_Point](./set_point/)(float) | Mengatur nilai ukuran dalam poin. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [Unit](./). |
## Catatan


Contoh ini menunjukkan cara membuat dan menyimpan gambar [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
