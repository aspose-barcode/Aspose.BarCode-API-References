---
title: Pdf417ExtendedParameters
second_title: Referencia de API de Aspose.BarCode para .NET
description: Almacena una información de metadatos MacroPdf417 del código de barras reconocido
type: docs
weight: 220
url: /es/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

Almacena una información de metadatos MacroPdf417 del código de barras reconocido

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Comprueba si todos los parámetros tienen solo valores predeterminados |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee) { get; } | Macro PDF417 nombre del destinatario (opcional). |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum) { get; } | Macro PDF417 checksum (opcional). |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid) { get; } | Obtiene el ID de archivo del código de barras, solo disponible con MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename) { get; } | Nombre del archivo Macro PDF417 (opcional). |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize) { get; } | Tamaño de archivo Macro PDF417 (opcional). |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid) { get; } | Obtiene el ID de segmento del código de barras, solo disponible con MacroPdf417. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount) { get; } | Obtiene el recuento de segmentos de código de barras macro pdf417. El valor predeterminado es -1. |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender) { get; } | Macro PDF417 nombre del remitente (opcional). |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp) { get; } | Marca de tiempo Macro PDF417 (opcional). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals)(object) | Devuelve un valor que indica si esta instancia es igual a una especificada[`Pdf417ExtendedParameters`](../pdf417extendedparameters) valor. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring)() | Devuelve una representación de cadena legible por humanos de este[`Pdf417ExtendedParameters`](../pdf417extendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality) | Devuelve un valor que indica si el primer[`Pdf417ExtendedParameters`](../pdf417extendedparameters) el valor es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality) | Devuelve un valor que indica si la primera[`Pdf417ExtendedParameters`](../pdf417extendedparameters) el valor es diferente del segundo. |

### Ejemplos

Este ejemplo muestra cómo obtener metadatos Macro Pdf417

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

### Ver también

* class [BaseExtendedParameters](../baseextendedparameters)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
