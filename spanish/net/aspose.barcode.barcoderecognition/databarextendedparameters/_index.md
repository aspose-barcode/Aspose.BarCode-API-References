---
title: "Clase DataBarExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.DataBarExtendedParameters. Almacena información adicional de DataBar del código de barras reconocido"
type: docs
weight: 210
url: /es/net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

Almacena información adicional de DataBar del código de barras reconocido.

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent/) { get; } | Obtiene la bandera del componente compuesto 2D de DataBar. El valor predeterminado es false. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Comprueba si todos los parámetros tienen solo valores predeterminados |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor `DataBarExtendedParameters` especificado. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring/)() | Devuelve una representación en forma de cadena legible por humanos de este `DataBarExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality/) | Devuelve un valor que indica si el primer valor `DataBarExtendedParameters` es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality/) | Devuelve un valor que indica si el primer valor `DataBarExtendedParameters` es diferente del segundo. |

## Ejemplos

Este ejemplo muestra cómo obtener información adicional de DataBar

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

### Ver también

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


