---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad Pdf417Parameters. Puede usarse solo con MicroPdf417 y codifica los modos de emulación Code 128. Puede codificar FNC1 en la segunda posición en los modos 908 y 909, también puede codificar 910 y 911, que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128."
type: docs
weight: 60
url: /es/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en modos de segunda posición 908 y 909, también puede codificar 910 y 911 que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128.

```csharp
public bool IsCode128Emulation { get; set; }
```

## Ejemplos

Estos ejemplos muestran cómo codificar los modos de emulación Code 128 con FNC1 en la segunda posición y sin él. De esta manera, MicroPdf417 puede decodificarse como un código de barras Code 128.

```csharp
[C#]
//Codifica MicroPdf417 en modo de emulación Code 128 con FNC1 en segunda posición y el Indicador de Aplicación "a", modo 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Codifica MicroPdf417 en modo de emulación Code 128 con FNC1 en segunda posición y el Indicador de Aplicación "99", modo 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Codifica MicroPdf417 en modo de emulación Code 128, modos 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### Ver también

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


