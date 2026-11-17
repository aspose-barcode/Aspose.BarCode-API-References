---
title: "method"
linktitle: "get_IsCode128Emulation"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置编码 FNC1（模式 908 和 909），也可以编码 910 和 911，这仅表示已识别的 MicroPdf417 可被解释为 Code 128，在 C++ 中。"
type: docs
weight: 4300
url: /zh/cpp/aspose.barcode.generation/pdf417parameters/get_iscode128emulation/
---
## Pdf417Parameters::get_IsCode128Emulation method


只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置模式 908 和 909 中编码 FNC1，还可以编码 910 和 911，这仅表示识别的 MicroPdf417 可被解释为 Code 128。

```cpp
bool Aspose::BarCode::Generation::Pdf417Parameters::get_IsCode128Emulation() const
```

## 备注


这些示例展示了如何在第二位置以及不使用第二位置的情况下编码 Code 128 仿真模式。这样 MicroPdf417 可以被解码为 Code 128 条码。
```cpp
[C#]
//在第二位置使用 FNC1 并使用应用指示符 \"a\"（模式 908）对 MicroPdf417 进行 Code 128 仿真模式编码。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//在第二位置使用 FNC1 并使用应用指示符 \"99\"（模式 909）对 MicroPdf417 进行 Code 128 仿真模式编码。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//对 MicroPdf417 进行 Code 128 仿真模式编码，模式 910、911。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

## 另见

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
