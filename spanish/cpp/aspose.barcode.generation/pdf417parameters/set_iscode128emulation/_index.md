---
title: "método"
linktitle: "set_IsCode128Emulation"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en la segunda posición en los modos 908 y 909, también puede codificar 910 y 911 que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128 en C++."
type: docs
weight: 4400
url: /es/cpp/aspose.barcode.generation/pdf417parameters/set_iscode128emulation/
---
## Pdf417Parameters::set_IsCode128Emulation method


Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en los modos de segunda posición 908 y 909, también puede codificar 910 y 911, que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128.

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsCode128Emulation(bool value)
```

## Observaciones


Estos ejemplos muestran cómo codificar los modos de emulación Code 128 con FNC1 en segunda posición y sin él. De esta manera MicroPdf417 puede decodificarse como un código de barras Code 128.
```cpp
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

## Ver también

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
