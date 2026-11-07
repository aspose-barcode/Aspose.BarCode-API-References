---
title: "method"
linktitle: "get_IsCode128Emulation"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Может использоваться только с MicroPdf417 и кодирует режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции режимов 908 и 909, также может кодировать 910 и 911, что просто указывает, что распознанный MicroPdf417 может интерпретироваться как Code 128 в C++."
type: docs
weight: 4300
url: /ru/cpp/aspose.barcode.generation/pdf417parameters/get_iscode128emulation/
---
## Pdf417Parameters::get_IsCode128Emulation method


Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во втором положении в режимах 908 и 909, а также может кодировать 910 и 911, что просто указывает, что распознанный MicroPdf417 может интерпретироваться как Code 128.

```cpp
bool Aspose::BarCode::Generation::Pdf417Parameters::get_IsCode128Emulation() const
```

## Примечания


Эти примеры показывают, как кодировать режимы эмуляции Code 128 с FNC1 во второй позиции и без него. Таким образом MicroPdf417 может быть декодирован как штрих‑код Code 128.
```cpp
[C#]
//Кодирует MicroPdf417 в режиме эмуляции Code 128 с FNC1 во второй позиции и индикатором приложения "a", режим 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Кодирует MicroPdf417 в режиме эмуляции Code 128 с FNC1 во второй позиции и индикатором приложения "99", режим 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Кодирует MicroPdf417 в режиме эмуляции Code 128, режимы 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

## См. также

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
