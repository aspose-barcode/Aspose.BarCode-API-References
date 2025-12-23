---
title: Pdf417Parameters.IsCode128Emulation
second_title: Aspose.BarCode for .NET API Reference
description: Pdf417Parameters property. Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909 also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128
type: docs
weight: 60
url: /net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128

```csharp
public bool IsCode128Emulation { get; set; }
```

## Examples

These samples show how to encode Code 128 emulation modes with FNC1 in second position and without. In this way MicroPdf417 can be decoded as Code 128 barcode

```csharp
[C#]
//Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### See Also

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


