---
title: QRExtendedParameters
second_title: Referencia de API de Aspose.BarCode para .NET
description: Almacena una información de anexo estructurado QR del código de barras reconocido
type: docs
weight: 230
url: /es/net/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class

Almacena una información de anexo estructurado QR del código de barras reconocido

```csharp
public sealed class QRExtendedParameters : BaseExtendedParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Comprueba si todos los parámetros tienen solo valores predeterminados |
| [QRStructuredAppendModeBarCodeIndex](../../aspose.barcode.barcoderecognition/qrextendedparameters/qrstructuredappendmodebarcodeindex) { get; } | Obtiene el índice del código de barras en modo anexo estructurado QR. El índice comienza desde 0. El valor predeterminado es -1. |
| [QRStructuredAppendModeBarCodesQuantity](../../aspose.barcode.barcoderecognition/qrextendedparameters/qrstructuredappendmodebarcodesquantity) { get; } | Obtiene la cantidad de códigos de barras en modo anexo estructurado QR. El valor predeterminado es -1. |
| [QRStructuredAppendModeParityData](../../aspose.barcode.barcoderecognition/qrextendedparameters/qrstructuredappendmodeparitydata) { get; } | Obtiene los datos de paridad del modo de anexo estructurado de QR. El valor predeterminado es -1. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/qrextendedparameters/equals)(object) | Devuelve un valor que indica si esta instancia es igual a una especificada[`QRExtendedParameters`](../qrextendedparameters) valor. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/qrextendedparameters/gethashcode)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/qrextendedparameters/tostring)() | Devuelve una representación de cadena legible por humanos de este[`QRExtendedParameters`](../qrextendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_equality) | Devuelve un valor que indica si el primer[`QRExtendedParameters`](../qrextendedparameters) el valor es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_inequality) | Devuelve un valor que indica si la primera[`QRExtendedParameters`](../qrextendedparameters) el valor es diferente del segundo. |

### Ejemplos

Este ejemplo muestra cómo obtener datos de Anexo estructurado QR

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

* class [BaseExtendedParameters](../baseextendedparameters)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
