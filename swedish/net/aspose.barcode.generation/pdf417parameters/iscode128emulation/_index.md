---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Pdf417Parameters egenskap. Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionen i lägena 908 och 909 samt även koda 910 och 911, vilket bara indikerar att en identifierad MicroPdf417 kan tolkas som Code 128"
type: docs
weight: 60
url: /sv/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

Kan endast användas med MicroPdf417 och kodar emuleringslägen för Code 128 Kan koda FNC1 i andra positionen i lägena 908 och 909, kan också koda 910 och 911 vilket bara indikerar att ett identifierat MicroPdf417 kan tolkas som Code 128

```csharp
public bool IsCode128Emulation { get; set; }
```

## Exempel

Dessa exempel visar hur man kodar Code 128-emuleringslägen med FNC1 i andra positionen och utan. På så sätt kan MicroPdf417 avkodas som en Code 128-streckkod

```csharp
[C#]
//Kodar MicroPdf417 i Code 128-emuleringsläge med FNC1 i andra positionen och Applikationsindikator "a", läge 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Kodar MicroPdf417 i Code 128-emuleringsläge med FNC1 i andra positionen och Applikationsindikator "99", läge 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Kodar MicroPdf417 i Code 128-emuleringsläge, lägena 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### Se även

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


