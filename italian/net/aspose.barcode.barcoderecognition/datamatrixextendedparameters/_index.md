---
title: "Classe DataMatrixExtendedParameters"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters. Memorizza dati speciali del codice a barre DataMatrix riconosciuto"
type: docs
weight: 220
url: /it/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

Memorizza dati speciali del codice a barre DataMatrix riconosciuto

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Verifica se tutti i parametri hanno solo valori predefiniti |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | Ottiene l'ID del codice a barre DataMatrix in modalità append strutturata. L'ID inizia da 1 e deve essere minore o uguale al numero di codici a barre. Il valore predefinito è -1. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | Ottiene il conteggio dei codici a barre DataMatrix in modalità append strutturata. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | Ottiene l'ID del codice a barre DataMatrix in modalità append strutturata. L'ID inizia da 1 e deve essere minore o uguale al numero di codici a barre. Il valore predefinito è -1. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `DataMatrixExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | Restituisce il codice hash per questa istanza. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | Restituisce una rappresentazione stringa leggibile dall'uomo di questo `DataMatrixExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | Restituisce un valore che indica se il primo valore `DataMatrixExtendedParameters` è uguale al secondo. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | Restituisce un valore che indica se il primo valore `DataMatrixExtendedParameters` è diverso dal secondo. |

## Esempi

Questo esempio mostra come ottenere i valori grezzi di DataMatrix

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### Vedi anche

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


