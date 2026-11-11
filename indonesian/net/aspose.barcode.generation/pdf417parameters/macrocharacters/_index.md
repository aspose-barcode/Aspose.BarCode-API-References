---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Properti Pdf417Parameters. Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengenkode mode 916 dan 917 MicroPdf417. Nilai default MacroCharacters.None"
type: docs
weight: 90
url: /id/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengenkode mode MicroPdf417 916 dan 917. Nilai default: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## Contoh

Contoh-contoh ini menunjukkan cara mengenkode Macro Characters dalam MicroPdf417

```csharp
[C#]
//Mengenkripsi MicroPdf417 dengan Macro 05 string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Menyandikan MicroPdf417 dengan Macro 06 string: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Lihat Juga

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


