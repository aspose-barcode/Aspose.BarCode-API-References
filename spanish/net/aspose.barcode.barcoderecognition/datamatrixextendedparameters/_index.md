---
title: "Clase DataMatrixExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters. Almacena datos especiales del código de barras DataMatrix reconocido"
type: docs
weight: 220
url: /es/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

Almacena datos especiales del código de barras DataMatrix reconocido.

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Comprueba si todos los parámetros tienen solo valores predeterminados |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | Obtiene el ID del código de barras en modo structured append de DataMatrix. El ID comienza en 1 y debe ser menor o igual al número de códigos de barras. El valor predeterminado es -1. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | Obtiene la cantidad de códigos de barras en modo structured append de DataMatrix. El valor predeterminado es -1. La cantidad debe ser un valor entre 1 y 35. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | Obtiene el ID del código de barras en modo structured append de DataMatrix. El ID comienza en 1 y debe ser menor o igual al número de códigos de barras. El valor predeterminado es -1. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor `DataMatrixExtendedParameters` especificado. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | Devuelve una representación de cadena legible por humanos de este `DataMatrixExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | Devuelve un valor que indica si el primer valor de `DataMatrixExtendedParameters` es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | Devuelve un valor que indica si el primer valor de `DataMatrixExtendedParameters` es diferente del segundo. |

## Ejemplos

Este ejemplo muestra cómo obtener los valores sin procesar de DataMatrix

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### Ver también

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


