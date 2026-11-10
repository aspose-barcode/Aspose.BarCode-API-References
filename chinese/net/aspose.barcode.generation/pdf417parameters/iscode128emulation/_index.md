---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Pdf417Parameters 属性。仅可与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可在第二位置编码 FNC1（模式 908 和 909），也可编码 910 和 911，这仅表示已识别的 MicroPdf417 可被解释为 Code 128。"
type: docs
weight: 60
url: /zh/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置编码 FNC1（模式 908 和 909），还可以编码 910 和 911，这仅表示识别的 MicroPdf417 可解释为 Code 128。

```csharp
public bool IsCode128Emulation { get; set; }
```

## 示例

以下示例展示了如何在第二位置使用或不使用 FNC1 编码 Code 128 仿真模式。通过这种方式，MicroPdf417 可以被解码为 Code 128 条码。

```csharp
[C#]
//在 Code 128 仿真模式下对 MicroPdf417 进行编码，FNC1 位于第二位置，应用指示符为 "a"，模式 908。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//在 Code 128 仿真模式下对 MicroPdf417 进行编码，FNC1 位于第二位置，应用指示符为 "99"，模式 909。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//在 Code 128 仿真模式下对 MicroPdf417 进行编码，模式 910、911。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### 另见

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


