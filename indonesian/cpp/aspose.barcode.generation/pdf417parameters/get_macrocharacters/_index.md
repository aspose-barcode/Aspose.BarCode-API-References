---
title: "metode"
linktitle: "get_MacroCharacters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengenkode mode MicroPdf417 916 dan 917. Nilai default: MacroCharacters.None dalam C++."
type: docs
weight: 3900
url: /id/cpp/aspose.barcode.generation/pdf417parameters/get_macrocharacters/
---
## Pdf417Parameters::get_MacroCharacters method


Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengenkode mode MicroPdf417 916 dan 917. Nilai default: [MacroCharacters.None](../../barcodeclassifications/).

```cpp
MacroCharacter Aspose::BarCode::Generation::Pdf417Parameters::get_MacroCharacters() const
```

## Catatan


Contoh-contoh ini menunjukkan cara mengenkode Macro Characters dalam MicroPdf417
```cpp
[C#]
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

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
