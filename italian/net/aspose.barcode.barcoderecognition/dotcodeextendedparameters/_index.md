---
title: "Classe DotCodeExtendedParameters"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.DotCodeExtendedParameters. Memorizza dati speciali del codice a barre DotCode riconosciuto"
type: docs
weight: 250
url: /it/net/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class

Memorizza dati speciali del codice a barre DotCode riconosciuto

```csharp
public sealed class DotCodeExtendedParameters : BaseExtendedParameters
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Verifica se tutti i parametri hanno solo valori predefiniti |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/isreaderinitialization/) { get; } | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false. |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodeid/) { get; } | Ottiene l'ID del codice a barre in modalità di aggiunta strutturata DotCode. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodescount/) { get; } | Ottiene il conteggio dei codici a barre in modalità di aggiunta strutturata DotCode. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/equals/)(object) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `DotCodeExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/gethashcode/)() | Restituisce il codice hash per questa istanza. |
| override [ToString](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/tostring/)() | Restituisce una rappresentazione stringa leggibile dall'uomo di questo `DotCodeExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_equality/) | Restituisce un valore che indica se il primo valore `DotCodeExtendedParameters` è uguale al secondo. |
| [operator !=](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_inequality/) | Restituisce un valore che indica se il primo valore `DotCodeExtendedParameters` è diverso dal secondo. |

## Esempi

Questo esempio mostra come ottenere i valori grezzi DotCode

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

### Vedi anche

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


