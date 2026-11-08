---
title: "método"
linktitle: "get_MacroCharacters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Los valores de Macro Characters 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Solo se puede usar con MicroPdf417 y codifica los modos 916 y 917 de MicroPdf417. Valor predeterminado: MacroCharacters.None en C++."
type: docs
weight: 3900
url: /es/cpp/aspose.barcode.generation/pdf417parameters/get_macrocharacters/
---
## Pdf417Parameters::get_MacroCharacters method


Los valores de Macro Characters 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Solo se puede usar con MicroPdf417 y codifica los modos 916 y 917 de MicroPdf417. Valor predeterminado: [MacroCharacters.None](../../barcodeclassifications/).

```cpp
MacroCharacter Aspose::BarCode::Generation::Pdf417Parameters::get_MacroCharacters() const
```

## Observaciones


Estos ejemplos muestran cómo codificar Macro Characters en MicroPdf417
```cpp
[C#]
//Codifica MicroPdf417 con Macro 05 la cadena: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Codifica MicroPdf417 con Macro 06 la cadena: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Ver también

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
