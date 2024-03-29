---
title: DataBarExtendedParameters
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Memorizza una DataBar informazioni aggiuntive del codice a barre riconosciuto
type: docs
weight: 180
url: /it/net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

Memorizza una DataBar informazioni aggiuntive del codice a barre riconosciuto

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent) { get; } | Ottiene il flag del componente composito DataBar 2D. Il valore predefinito è falso. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Verifica se tutti i parametri hanno solo valori predefiniti |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals)(object) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato[`DataBarExtendedParameters`](../databarextendedparameters) valore. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode)() | Restituisce il codice hash per questa istanza. |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring)() | Restituisce una rappresentazione di stringa leggibile dall'uomo di questo[`DataBarExtendedParameters`](../databarextendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality) | Restituisce un valore che indica se il primo[`DataBarExtendedParameters`](../databarextendedparameters) il valore è uguale al secondo. |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality) | Restituisce un valore che indica se il primo[`DataBarExtendedParameters`](../databarextendedparameters) il valore è diverso dal secondo. |

### Esempi

Questo esempio mostra come ottenere informazioni aggiuntive su DataBar

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

### Guarda anche

* class [BaseExtendedParameters](../baseextendedparameters)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
