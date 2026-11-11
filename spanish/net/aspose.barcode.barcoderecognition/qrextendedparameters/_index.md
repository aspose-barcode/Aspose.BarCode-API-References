---
title: "Clase QRExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.QRExtendedParameters. Almacena información de QR Structured Append del código de barras reconocido"
type: docs
weight: 350
url: /es/net/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class

Almacena información de Structured Append de QR del código de barras reconocido

```csharp
public sealed class QRExtendedParameters : BaseExtendedParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ErrorLevel](../../aspose.barcode.barcoderecognition/qrextendedparameters/errorlevel/) { get; } | Nivel de corrección de errores Reed-Solomon del código de barras reconocido. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Comprueba si todos los parámetros tienen solo valores predeterminados |
| [MicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/microqrversion/) { get; } | Versión del MicroQR Code reconocido. De M1 a M4. |
| [RectMicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/rectmicroqrversion/) { get; } | Versión del RectMicroQR Code reconocido. De R7x43 a R17x139. |
| [StructuredAppendModeBarCodeIndex](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodeindex/) { get; } | Obtiene el índice del código de barras del modo QR structured append. El índice comienza en 0. El valor predeterminado es -1. |
| [StructuredAppendModeBarCodesQuantity](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodesquantity/) { get; } | Obtiene la cantidad de códigos de barras del modo QR structured append. El valor predeterminado es -1. |
| [StructuredAppendModeParityData](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodeparitydata/) { get; } | Obtiene los datos de paridad del modo QR structured append. El valor predeterminado es -1. |
| [Version](../../aspose.barcode.barcoderecognition/qrextendedparameters/version/) { get; } | Versión del QR Code reconocido. De Version1 a Version40. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/qrextendedparameters/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `QRExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/qrextendedparameters/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/qrextendedparameters/tostring/)() | Devuelve una representación en cadena legible por humanos de este `QRExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_equality/) | Devuelve un valor que indica si el primer valor `QRExtendedParameters` es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_inequality/) | Devuelve un valor que indica si el primer valor `QRExtendedParameters` es diferente del segundo. |

## Ejemplos

Este ejemplo muestra cómo obtener los datos de QR Structured Append

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

### Ver también

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


