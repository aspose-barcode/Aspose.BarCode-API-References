---
title: "Class AztecExtendedParameters"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.BarCodeRecognition.AztecExtendedParameters class. Memorizza dati speciali del codice a barre Aztec riconosciuto"
type: docs
weight: 40
url: /it/net/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class

Memorizza dati speciali del codice a barre Aztec riconosciuto

```csharp
public sealed class AztecExtendedParameters : BaseExtendedParameters
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Verifica se tutti i parametri hanno solo valori predefiniti |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/aztecextendedparameters/isreaderinitialization/) { get; } | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodeid/) { get; } | Ottiene l'ID del codice a barre in modalità append strutturata Aztec. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è 0. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodescount/) { get; } | Ottiene il conteggio dei codici a barre in modalità append strutturata Aztec. Il valore predefinito è 0. Il conteggio deve essere un valore da 1 a 26. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendfileid/) { get; } | Ottiene l'ID file della modalità append strutturata Aztec. Il valore predefinito è una stringa vuota |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/aztecextendedparameters/equals/)(object) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `AztecExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/aztecextendedparameters/gethashcode/)() | Restituisce il codice hash per questa istanza. |
| override [ToString](../../aspose.barcode.barcoderecognition/aztecextendedparameters/tostring/)() | Restituisce una rappresentazione stringa leggibile dall'uomo di questo `AztecExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_equality/) | Restituisce un valore che indica se il primo valore `AztecExtendedParameters` è uguale al secondo. |
| [operator !=](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_inequality/) | Restituisce un valore che indica se il primo valore `AztecExtendedParameters` è diverso dal secondo. |

## Esempi

Questo esempio mostra come ottenere i valori raw Aztec

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

### Vedi anche

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


