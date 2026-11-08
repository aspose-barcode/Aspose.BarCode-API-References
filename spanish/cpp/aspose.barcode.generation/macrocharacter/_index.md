---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Los valores de Macro Characters 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. El carácter macro 05 se traduce a \"[)>\\u001E05\\u001D\" como encabezado de datos decodificado y \"\\u001E\\u0004\" como tráiler de datos decodificado. El carácter macro 06 se traduce a \"[)>\\u001E06\\u001D\" como encabezado de datos decodificado y \"\\u001E\\u0004\" como tráiler de datos decodificado en C++."
type: docs
weight: 7300
url: /es/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. El carácter macro 05 se traduce a "[)>\u001E05\u001D" como encabezado de datos decodificados y "\u001E\u0004" como trailer de datos decodificados. El carácter macro 06 se traduce a "[)>\u001E06\u001D" como encabezado de datos decodificados y "\u001E\u0004" como trailer de datos decodificados.

```cpp
enum class MacroCharacter
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | Ninguno de los caracteres macro se agrega a los datos del código de barras |
| Macro05 | 5 | El carácter macro 05 se agrega a los datos del código de barras en la primera posición. El identificador de datos GS1 ISO 15434 se traduce a "[)>\u001E05\u001D" como encabezado de datos decodificado y "\u001E\u0004" como tráiler de datos decodificado. |
| Macro06 | 6 | El carácter macro 06 se agrega a los datos del código de barras en la primera posición. El identificador de datos ASC MH10 ISO 15434 se traduce a "[)>\u001E06\u001D" como encabezado de datos decodificado y "\u001E\u0004" como tráiler de datos decodificado. |

## Observaciones


Estos ejemplos muestran cómo codificar caracteres macro en MicroPdf417 y DataMatrix
```cpp
[C#]
//Para generar un mensaje GS1 autoidentificado como este "(10)123ABC(10)123ABC" en formato ISO 15434, necesita:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

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

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
