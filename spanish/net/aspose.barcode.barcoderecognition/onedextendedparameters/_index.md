---
title: "Clase OneDExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.OneDExtendedParameters. Almacena datos especiales del código de barras 1D reconocido, como texto de código separado y suma de verificación."
type: docs
weight: 330
url: /es/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

Almacena datos especiales del código de barras 1D reconocido, como texto de código separado y suma de verificación

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum/) { get; } | Obtiene la suma de verificación para códigos de barras 1D. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Comprueba si todos los parámetros tienen solo valores predeterminados |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value/) { get; } | Obtiene el texto de código de los códigos de barras 1D sin suma de verificación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `OneDExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring/)() | Devuelve una representación de cadena legible por humanos de este `OneDExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality/) | Devuelve un valor que indica si el primer valor `OneDExtendedParameters` es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality/) | Devuelve un valor que indica si el primer valor `OneDExtendedParameters` es diferente del segundo. |

## Ejemplos

Este ejemplo muestra cómo obtener el valor y la suma de verificación del código de barras 1D.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Ver también

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


