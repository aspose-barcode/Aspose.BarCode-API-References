---
title: "Aspose::BarCode::Generation::FontUnit class"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Generation::FontUnit class. Menentukan format tertentu untuk teks, termasuk jenis font, ukuran, dan atribut gaya di mana ukuran berada dalam properti nilai Unit dalam C++."
type: docs
weight: 2500
url: /id/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


Menentukan format tertentu untuk teks, termasuk jenis font, ukuran, dan atribut gaya di mana ukuran berada dalam properti nilai [Unit](../unit/).

```cpp
class FontUnit : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | Mendapatkan nama jenis font ini. |
| [get_Size](./get_size/)() const | Mendapatkan ukuran [FontUnit](./) dalam nilai [Unit](../unit/). |
| [get_Style](./get_style/)() const | Mendapatkan informasi gaya untuk [FontUnit](./) ini. |
| [set_FamilyName](./set_familyname/)(System::String) | Mengatur nama wajah dari Font ini. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | Mengatur informasi gaya untuk [FontUnit](./) ini. |
## Catatan


Contoh ini menunjukkan cara membuat dan menyimpan gambar [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
