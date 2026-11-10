---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Pdf417Parameters property. Kann nur mit MicroPdf417 verwendet werden und kodiert Code 128‑Emulationsmodi. Kann FNC1 in zweiter Position kodieren, Modi 908 und 909, außerdem kann 910 und 911 kodiert werden, die lediglich anzeigen, dass ein erkanntes MicroPdf417 als Code 128 interpretiert werden kann."
type: docs
weight: 60
url: /de/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position in den Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann.

```csharp
public bool IsCode128Emulation { get; set; }
```

## Beispiele

Diese Beispiele zeigen, wie Code‑128‑Emulationsmodi mit FNC1 in zweiter Position und ohne kodiert werden können. Auf diese Weise kann MicroPdf417 als Code 128‑Strichcode dekodiert werden.

```csharp
[C#]
//Kodiert MicroPdf417 im Code‑128‑Emulationsmodus mit FNC1 in zweiter Position und Anwendungsindikator "a", Modus 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Kodiert MicroPdf417 im Code‑128‑Emulationsmodus mit FNC1 in zweiter Position und Anwendungsindikator "99", Modus 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Kodiert MicroPdf417 im Code‑128‑Emulationsmodus, Modi 910, 911.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### Siehe auch

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


