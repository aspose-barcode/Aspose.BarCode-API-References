---
title: "metod"
linktitle: "set_IsCode128Emulation"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Kan endast användas med MicroPdf417 och kodar Code 128‑emuleringslägen. Kan koda FNC1 i andra positionen för lägena 908 och 909, kan också koda 910 och 911 vilket bara indikerar att igenkänd MicroPdf417 kan tolkas som Code 128 i C++."
type: docs
weight: 4400
url: /sv/cpp/aspose.barcode.generation/pdf417parameters/set_iscode128emulation/
---
## Pdf417Parameters::set_IsCode128Emulation method


Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionslägena 908 och 909, samt kan koda 910 och 911 som bara indikerar att identifierad MicroPdf417 kan tolkas som Code 128.

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsCode128Emulation(bool value)
```

## Anmärkningar


Dessa exempel visar hur man kodar Code 128‑emuleringslägen med FNC1 i andra positionen och utan. På så sätt kan MicroPdf417 avkodas som en Code 128‑streckkod.
```cpp
[C#]
//Kodar MicroPdf417 i Code 128‑emuleringsläge med FNC1 i andra positionen och applikationsindikator "a", läge 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Kodar MicroPdf417 i Code 128‑emuleringsläge med FNC1 i andra positionen och applikationsindikator "99", läge 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Kodar MicroPdf417 i Code 128‑emuleringsläge, lägena 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

## Se även

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
