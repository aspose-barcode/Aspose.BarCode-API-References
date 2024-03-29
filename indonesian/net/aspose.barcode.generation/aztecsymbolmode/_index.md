---
title: AztecSymbolMode
second_title: Aspose.BarCode untuk .NET API Referensi
description: Menentukan mode simbol Aztec.
type: docs
weight: 670
url: /id/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Menentukan mode simbol Aztec.

```csharp
public enum AztecSymbolMode
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Auto | `0` | Menentukan untuk secara otomatis mengambil simbol terbaik (Ringkas atau Rentang Penuh) untuk Aztec. Ini adalah nilai default. |
| Compact | `1` | Menentukan simbol Compact untuk Aztec. Simbol Compact Aztec hanya mengizinkan 1, 2, 3 atau 4 lapisan. |
| FullRange | `2` | Menentukan simbol Full-range untuk Aztec. Simbol Full-range Aztec memungkinkan dari 1 hingga 32 lapisan. |
| Rune | `3` | Menentukan simbol Rune untuk Aztec. Aztec Rune adalah serangkaian tanda kecil namun dapat dibaca oleh mesin. Ini hanya mengizinkan nilai angka dari 0 hingga 255. |

### Contoh

Contoh ini menunjukkan cara mengubah mode Simbol Aztec dan menyimpan gambar BarCode.

```csharp
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

### Lihat juga

* ruang nama [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
