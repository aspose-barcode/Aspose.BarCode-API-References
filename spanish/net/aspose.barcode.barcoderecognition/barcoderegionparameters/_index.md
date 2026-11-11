---
title: "Clase BarCodeRegionParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.BarCodeRegionParameters. Representa la región de códigos de barras reconocidos y el ángulo del código de barras"
type: docs
weight: 90
url: /es/net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

Representa la región del código de barras reconocido y el ángulo del código de barras.

```csharp
public sealed class BarCodeRegionParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle/) { get; } | Obtiene el ángulo del código de barras (0-360). |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points/) { get; } | Obtiene la matriz Points que delimita la región del código de barras |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle/) { get; } | Obtiene [`Quadrangle`](../quadrangle/) que delimita la región del código de barras |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle/) { get; } | Obtiene Rectangle que delimita la región del código de barras |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `BarCodeRegionParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring/)() | Devuelve una representación en cadena legible por humanos de este `BarCodeRegionParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality/) | Devuelve un valor que indica si el primer valor `BarCodeRegionParameters` es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality/) | Devuelve un valor que indica si el primer valor `BarCodeRegionParameters` es diferente del segundo. |

## Ejemplos

Este ejemplo muestra cómo obtener el ángulo del código de barras y los valores del cuadrilátero delimitador

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


