---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " enum. Menentukan mode simbol Aztec dalam C++."
type: docs
weight: 5400
url: /id/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Menentukan mode simbol Aztec.

```cpp
enum class AztecSymbolMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Otomatis | 0 | Menentukan untuk secara otomatis memilih simbol terbaik (Compact atau Full-range) untuk Aztec. Ini adalah nilai default. |
| Compact | 1 | Menentukan simbol Compact untuk Aztec. Simbol Compact Aztec hanya memperbolehkan 1, 2, 3, atau 4 lapisan. |
| FullRange | 2 | Menentukan simbol Full-range untuk Aztec. Simbol Full-range Aztec memperbolehkan dari 1 hingga 32 lapisan. |
| Rune | 3 | Menentukan simbol Rune untuk Aztec. Aztec Runes adalah serangkaian tanda kecil namun berbeda yang dapat dibaca mesin. Hanya memperbolehkan nilai angka dari 0 hingga 255. |

## Catatan


Contoh ini menunjukkan cara mengubah mode Symbol Aztec dan menyimpan gambar [BarCode](../../aspose.barcode/).
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
        generator.CodeText = "125"
        generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
        generator.Save("test.png")
    End Using
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
