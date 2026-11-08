---
title: "metot"
linktitle: "set_MacroCharacters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "metod. Macro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar. Varsayılan değer: MacroCharacters.None C++'da."
type: docs
weight: 4000
url: /tr/cpp/aspose.barcode.generation/pdf417parameters/set_macrocharacters/
---
## Pdf417Parameters::set_MacroCharacters method


Macro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar. Varsayılan değer: [MacroCharacters.None](../../barcodeclassifications/).

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_MacroCharacters(MacroCharacter value)
```

## Açıklamalar


Bu örnekler, Macro Karakterleri MicroPdf417 içinde nasıl kodlayacağınızı gösterir
```cpp
[C#]
//MicroPdf417'yi 05 Makro ile şu dizeyi kodlar: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//MicroPdf417'yi 06 Makro ile şu dizeyi kodlar: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Ayrıca Bakınız

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
