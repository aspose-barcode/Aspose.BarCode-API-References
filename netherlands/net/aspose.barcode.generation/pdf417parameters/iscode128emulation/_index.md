---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Pdf417Parameters eigenschap. Alleen bruikbaar met MicroPdf417 en codeert Code‑128‑emulatiemodi. Kan FNC1 coderen in de tweede positie voor de modi 908 en 909, en kan ook 910 en 911 coderen, wat alleen aangeeft dat een herkende MicroPdf417 kan worden geïnterpreteerd als Code 128"
type: docs
weight: 60
url: /nl/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

Kan alleen worden gebruikt met MicroPdf417 en codeert Code‑128-emulatiemodi. Kan FNC1 coderen in tweede‑positie‑modi 908 en 909, en kan ook 910 en 911 coderen, die alleen aangeven dat herkende MicroPdf417 kan worden geïnterpreteerd als Code 128.

```csharp
public bool IsCode128Emulation { get; set; }
```

## Voorbeelden

Deze voorbeelden laten zien hoe Code‑128‑emulatiemodi te coderen met FNC1 in de tweede positie en zonder. Op deze manier kan MicroPdf417 worden gedecodeerd als een Code‑128‑barcode

```csharp
[C#]
//Encodeert MicroPdf417 in Code 128-emulatiemodus met FNC1 op de tweede positie en toepassingsindicator "a", modus 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Encodeert MicroPdf417 in Code 128-emulatiemodus met FNC1 op de tweede positie en toepassingsindicator "99", modus 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Encodeert MicroPdf417 in Code 128-emulatiemodus, modi 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### Zie ook

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


