---
title: "Clase Code128ExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.BarCodeRecognition.Code128ExtendedParameters class. Almacena datos especiales del código de barras Code128 reconocido"
type: docs
weight: 180
url: /es/net/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class

Almacena datos especiales del código de barras Code128 reconocido.

Representa la región del código de barras reconocido y el ángulo del código de barras.

```csharp
public sealed class Code128ExtendedParameters : BaseExtendedParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Code128DataPortions](../../aspose.barcode.barcoderecognition/code128extendedparameters/code128dataportions/) { get; } | Obtiene la matriz [`Code128DataPortion`](../code128dataportion/) del código de barras Code128 reconocido |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Comprueba si todos los parámetros tienen solo valores predeterminados |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/code128extendedparameters/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `Code128ExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/code128extendedparameters/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/code128extendedparameters/tostring/)() | Devuelve una representación en cadena legible por humanos de este `Code128ExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_equality/) | Devuelve un valor que indica si el primer valor de `Code128ExtendedParameters` es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_inequality/) | Devuelve un valor que indica si el primer valor de `Code128ExtendedParameters` es diferente del segundo. |

## Ejemplos

Este ejemplo muestra cómo obtener los valores sin procesar de code128

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

### Ver también

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


