---
title: BarCodeResult
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Memorizza dati di codici a barre riconosciuti comeSingleDecodeType./singledecodetype genereString testo in codice BarCodeRegionParameters./barcoderegionparameters regione e altri parametri
type: docs
weight: 90
url: /it/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Memorizza dati di codici a barre riconosciuti come[`SingleDecodeType`](../singledecodetype) genere,String testo in codice, [`BarCodeRegionParameters`](../barcoderegionparameters) regione e altri parametri

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BarCodeResult](barcoderesult)(BarCodeResult) | Crea una copia di[`BarCodeResult`](../barcoderesult) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes) { get; } | Ottiene i byte di codice codificati |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext) { get; } | Ottiene il testo del codice |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype) { get; } | Ottiene il tipo di codice a barre |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename) { get; } | Ottiene il nome del tipo di codice a barre |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence) { get; } | Ottiene il livello di affidabilità del riconoscimento del codice a barre riconosciuto |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended) { get; } | Ottiene parametri estesi del codice a barre riconosciuto |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality) { get; } | Ottiene la qualità di lettura. Funziona con codici a barre 1D e postali. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region) { get; } | Ottiene la regione del codice a barre |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone)() | Crea una copia di[`BarCodeResult`](../barcoderesult) classe. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals)(BarCodeResult) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato[`BarCodeResult`](../barcoderesult) valore. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals_1)(object) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato[`BarCodeResult`](../barcoderesult) valore. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext)(Encoding) | Ottiene il testo del codice con la codifica. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode)() | Restituisce il codice hash per questa istanza. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring)() | Restituisce una rappresentazione di stringa leggibile dall'uomo di questo[`BarCodeResult`](../barcoderesult) . |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality) | Restituisce un valore che indica se il primo[`BarCodeResult`](../barcoderesult) il valore è uguale al secondo. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality) | Restituisce un valore che indica se il primo[`BarCodeResult`](../barcoderesult) il valore è diverso dal secondo. |

### Esempi

Questo esempio mostra come ottenere BarCodeResult.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### Guarda anche

* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
