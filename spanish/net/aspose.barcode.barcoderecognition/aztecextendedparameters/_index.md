---
title: "Clase AztecExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.AztecExtendedParameters. Almacena datos especiales del código de barras Aztec reconocido"
type: docs
weight: 40
url: /es/net/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class

Almacena datos especiales del código de barras Aztec reconocido.

```csharp
public sealed class AztecExtendedParameters : BaseExtendedParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Comprueba si todos los parámetros tienen solo valores predeterminados |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/aztecextendedparameters/isreaderinitialization/) { get; } | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodeid/) { get; } | Obtiene el ID del código de barras de modo de anexado estructurado Aztec. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es 0. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodescount/) { get; } | Obtiene el recuento de códigos de barras del modo de anexado estructurado Aztec. El valor predeterminado es 0. El recuento debe ser un valor de 1 a 26. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendfileid/) { get; } | Obtiene el ID de archivo del modo de anexado estructurado Aztec. El valor predeterminado es una cadena vacía. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/aztecextendedparameters/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `AztecExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/aztecextendedparameters/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/aztecextendedparameters/tostring/)() | Devuelve una representación en cadena legible por humanos de este `AztecExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_equality/) | Devuelve un valor que indica si el primer valor de `AztecExtendedParameters` es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_inequality/) | Devuelve un valor que indica si el primer valor de `AztecExtendedParameters` es diferente del segundo. |

## Ejemplos

Este ejemplo muestra cómo obtener los valores sin procesar de Aztec.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

### Ver también

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


