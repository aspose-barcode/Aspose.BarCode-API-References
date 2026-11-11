---
title: "Clase Pdf417ExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.Pdf417ExtendedParameters. Almacena información de metadatos MacroPdf417 del código de barras reconocido."
type: docs
weight: 340
url: /es/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

Almacena información de metadatos MacroPdf417 del código de barras reconocido

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsCode128Emulation](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/iscode128emulation/) { get; } | Indicador que señala que el código de barras MicroPdf417 está codificado con palabras de código de emulación Code 128 908, 909, 910 o 911. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Comprueba si todos los parámetros tienen solo valores predeterminados |
| [IsLinked](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/islinked/) { get; } | Indicador que señala que el código de barras debe estar vinculado a un código de barras 1D. |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/isreaderinitialization/) { get; } | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee/) { get; } | Nombre del destinatario Macro PDF417 (opcional). |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum/) { get; } | Suma de verificación Macro PDF417 (opcional). |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid/) { get; } | Obtiene el ID del archivo del código de barras, solo disponible con MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename/) { get; } | Nombre de archivo Macro PDF417 (opcional). |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize/) { get; } | Tamaño de archivo Macro PDF417 (opcional). |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid/) { get; } | Obtiene el ID del segmento del código de barras, solo disponible con MacroPdf417. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount/) { get; } | Obtiene el recuento de segmentos del código de barras macro pdf417. Valor predeterminado es -1. |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender/) { get; } | Nombre del remitente Macro PDF417 (opcional). |
| [MacroPdf417Terminator](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417terminator/) { get; } | Indica si el segmento es el último segmento de un archivo Macro PDF417. |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp/) { get; } | Marca de tiempo Macro PDF417 (opcional). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `Pdf417ExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring/)() | Devuelve una representación en forma de cadena legible por humanos de este `Pdf417ExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality/) | Devuelve un valor que indica si el primer valor de `Pdf417ExtendedParameters` es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality/) | Devuelve un valor que indica si el primer valor de `Pdf417ExtendedParameters` es diferente al segundo. |

## Ejemplos

Este ejemplo muestra cómo obtener los metadatos de Macro Pdf417.

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

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


