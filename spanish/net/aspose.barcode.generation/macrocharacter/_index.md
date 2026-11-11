---
title: "Enum MacroCharacter"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.Generation.MacroCharacter enum. Los valores de Macro Characters 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. El carácter Macro 05 se traduce a u001E05u001D como encabezado de datos decodificado y u001Eu0004 como tráiler de datos decodificado. El carácter Macro 06 se traduce a u001E06u001D como encabezado de datos decodificado y u001Eu0004 como tráiler de datos decodificado."
type: docs
weight: 1450
url: /es/net/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enumeration

Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. El carácter macro 05 se traduce a "[)&gt;\u001E05\u001D" como encabezado de datos decodificado y "\u001E\u0004" como trailer de datos decodificado. El carácter macro 06 se traduce a "[)&gt;\u001E06\u001D" como encabezado de datos decodificado y "\u001E\u0004" como trailer de datos decodificado.

```csharp
public enum MacroCharacter
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Ninguno de los Macro Characters se agrega a los datos del código de barras |
| Macro05 | `5` | El carácter Macro 05 se agrega a los datos del código de barras en la primera posición. El carácter Identificador de Datos GS1 ISO 15434 se traduce a "[)&gt;\u001E05\u001D" como encabezado de datos decodificado y "\u001E\u0004" como tráiler de datos decodificado. |
| Macro06 | `6` | El carácter Macro 06 se agrega a los datos del código de barras en la primera posición. El carácter Identificador de Datos ASC MH10 ISO 15434 se traduce a "[)&gt;\u001E06\u001D" como encabezado de datos decodificado y "\u001E\u0004" como tráiler de datos decodificado. |

## Ejemplos

Estos ejemplos muestran cómo codificar Macro Characters en MicroPdf417 y DataMatrix

```csharp
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

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


