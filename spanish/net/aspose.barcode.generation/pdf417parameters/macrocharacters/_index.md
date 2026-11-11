---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad Pdf417Parameters. Los valores de los Caracteres Macro 05 y 06 se usan para obtener una codificación más compacta en modos especiales. Puede usarse solo con MicroPdf417 y codifica los modos 916 y 917 de MicroPdf417. Valor predeterminado MacroCharacters.None."
type: docs
weight: 90
url: /es/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Solo se pueden usar con MicroPdf417 y codifican los modos 916 y 917 de MicroPdf417. Valor predeterminado: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## Ejemplos

Estos ejemplos muestran cómo codificar los Caracteres Macro en MicroPdf417.

```csharp
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

### Ver también

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


