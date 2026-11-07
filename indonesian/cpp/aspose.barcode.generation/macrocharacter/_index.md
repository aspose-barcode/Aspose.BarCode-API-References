---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " enum. Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Karakter Macro 05 diterjemahkan menjadi \"[)>\\u001E05\\u001D\" sebagai header data terdekripsi dan \"\\u001E\\u0004\" sebagai trailer data terdekripsi. Karakter Macro 06 diterjemahkan menjadi \"[)>\\u001E06\\u001D\" sebagai header data terdekripsi dan \"\\u001E\\u0004\" sebagai trailer data terdekripsi dalam C++."
type: docs
weight: 7300
url: /id/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


Nilai Macro Karakter 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Karakter Macro 05 diterjemahkan menjadi "[)>\u001E05\u001D" sebagai header data terdekripsi dan "\u001E\u0004" sebagai trailer data terdekripsi. Karakter Macro 06 diterjemahkan menjadi "[)>\u001E06\u001D" sebagai header data terdekripsi dan "\u001E\u0004" sebagai trailer data terdekripsi.

```cpp
enum class MacroCharacter
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Tidak ada | 0 | Tidak ada Macro Characters yang ditambahkan ke data kode batang |
| Macro05 | 5 | Karakter Macro 05 ditambahkan ke data kode batang pada posisi pertama. Karakter Identifikasi Data GS1 ISO 15434 diterjemahkan menjadi "[)>\u001E05\u001D" sebagai header data terdekripsi dan "\u001E\u0004" sebagai trailer data terdekripsi. |
| Macro06 | 6 | Karakter Macro 06 ditambahkan ke data kode batang pada posisi pertama. Karakter Identifikasi Data ASC MH10 ISO 15434 diterjemahkan menjadi "[)>\u001E06\u001D" sebagai header data terdekripsi dan "\u001E\u0004" sebagai trailer data terdekripsi. |

## Catatan


Contoh-contoh ini menunjukkan cara mengenkode Macro Characters dalam MicroPdf417 dan DataMatrix
```cpp
[C#]
//untuk menghasilkan pesan GS1 yang teridentifikasi otomatis seperti ini "(10)123ABC(10)123ABC" dalam format ISO 15434 Anda memerlukan:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Mengenkripsi MicroPdf417 dengan Macro 05 string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Mengenkripsi MicroPdf417 dengan Macro 06 string: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
