---
title: "Clase DotCodeExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.DotCodeExtendedParameters. Almacena datos especiales del código de barras DotCode reconocido"
type: docs
weight: 250
url: /es/net/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class

Almacena datos especiales del código de barras DotCode reconocido.

```csharp
public sealed class DotCodeExtendedParameters : BaseExtendedParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Comprueba si todos los parámetros tienen solo valores predeterminados |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/isreaderinitialization/) { get; } | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false. |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodeid/) { get; } | Obtiene el ID del código de barras en modo de anexado estructurado DotCode. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodescount/) { get; } | Obtiene el recuento de códigos de barras en modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `DotCodeExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/tostring/)() | Devuelve una representación de cadena legible por humanos de este `DotCodeExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_equality/) | Devuelve un valor que indica si el primer valor de `DotCodeExtendedParameters` es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_inequality/) | Devuelve un valor que indica si el primer valor de `DotCodeExtendedParameters` es diferente al segundo. |

## Ejemplos

Este ejemplo muestra cómo obtener los valores sin procesar de DotCode

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

### Ver también

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


