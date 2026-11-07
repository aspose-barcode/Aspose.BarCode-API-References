---
title: "methode"
linktitle: "set_IsCode128Emulation"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Kan alleen worden gebruikt met MicroPdf417 en codeert Code‑128‑emulatiemodi. Kan FNC1 coderen in de tweede positie voor modi 908 en 909, en kan ook 910 en 911 coderen, wat alleen aangeeft dat herkende MicroPdf417 kan worden geïnterpreteerd als Code‑128 in C++."
type: docs
weight: 4400
url: /nl/cpp/aspose.barcode.generation/pdf417parameters/set_iscode128emulation/
---
## Pdf417Parameters::set_IsCode128Emulation method


Kan alleen worden gebruikt met MicroPdf417 en codeert Code‑128‑emulatiemodi. Kan FNC1 coderen op de tweede positie in de modi 908 en 909, en kan ook 910 en 911 coderen, die alleen aangeven dat herkende MicroPdf417 kan worden geïnterpreteerd als Code 128.

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsCode128Emulation(bool value)
```

## Opmerkingen


Deze voorbeelden tonen hoe Code‑128‑emulatiemodi te coderen met FNC1 op de tweede positie en zonder. Op deze manier kan MicroPdf417 worden gedecodeerd als Code‑128‑streepjescode.
```cpp
[C#]
//Codeert MicroPdf417 in Code‑128‑emulatiemodus met FNC1 op de tweede positie en toepassingsindicator "a", modus 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Codeert MicroPdf417 in Code‑128‑emulatiemodus met FNC1 op de tweede positie en toepassingsindicator "99", modus 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Codeert MicroPdf417 in Code‑128‑emulatiemodus, modi 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

## Zie ook

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
