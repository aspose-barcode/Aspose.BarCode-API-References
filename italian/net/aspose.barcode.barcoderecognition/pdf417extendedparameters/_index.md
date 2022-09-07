---
title: Pdf417ExtendedParameters
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Memorizza le informazioni sui metadati MacroPdf417 del codice a barre riconosciuto
type: docs
weight: 220
url: /it/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

Memorizza le informazioni sui metadati MacroPdf417 del codice a barre riconosciuto

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Verifica se tutti i parametri hanno solo valori predefiniti |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee) { get; } | Nome del destinatario della macro PDF417 (opzionale). |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum) { get; } | Macro PDF417 checksum (opzionale). |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid) { get; } | Ottiene l'ID file del codice a barre, disponibile solo con MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename) { get; } | Nome file Macro PDF417 (opzionale). |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize) { get; } | Dimensione file Macro PDF417 (opzionale). |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid) { get; } | Ottiene l'ID del segmento del codice a barre, disponibile solo con MacroPdf417. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount) { get; } | Ottiene il conteggio dei segmenti di codice a barre macro pdf417. Il valore predefinito è -1. |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender) { get; } | Macro PDF417 nome mittente (opzionale). |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp) { get; } | Macro PDF417 timestamp (opzionale). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals)(object) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato[`Pdf417ExtendedParameters`](../pdf417extendedparameters) valore. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode)() | Restituisce il codice hash per questa istanza. |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring)() | Restituisce una rappresentazione di stringa leggibile dall'uomo di questo[`Pdf417ExtendedParameters`](../pdf417extendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality) | Restituisce un valore che indica se il primo[`Pdf417ExtendedParameters`](../pdf417extendedparameters) il valore è uguale al secondo. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality) | Restituisce un valore che indica se il primo[`Pdf417ExtendedParameters`](../pdf417extendedparameters) il valore è diverso dal secondo. |

### Esempi

Questo esempio mostra come ottenere i metadati Macro Pdf417

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

### Guarda anche

* class [BaseExtendedParameters](../baseextendedparameters)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
