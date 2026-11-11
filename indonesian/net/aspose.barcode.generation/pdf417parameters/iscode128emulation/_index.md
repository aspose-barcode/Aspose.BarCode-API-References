---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Properti Pdf417Parameters. Hanya dapat digunakan dengan MicroPdf417 dan menyandikan mode emulasi Code 128. Dapat menyandikan FNC1 pada posisi kedua mode 908 dan 909 serta dapat menyandikan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128"
type: docs
weight: 60
url: /id/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128

```csharp
public bool IsCode128Emulation { get; set; }
```

## Contoh

Contoh-contoh ini menunjukkan cara menyandikan mode emulasi Code 128 dengan FNC1 pada posisi kedua dan tanpa. Dengan cara ini MicroPdf417 dapat didekode sebagai barcode Code 128

```csharp
[C#]
//Menyandikan MicroPdf417 dalam mode emulasi Code 128 dengan FNC1 pada posisi kedua dan Penanda Aplikasi "a", mode 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Menyandikan MicroPdf417 dalam mode emulasi Code 128 dengan FNC1 pada posisi kedua dan Penanda Aplikasi "99", mode 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Menyandikan MicroPdf417 dalam mode emulasi Code 128, mode 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### Lihat Juga

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


