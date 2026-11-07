---
title: "Classe Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Classe Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters. Memorizza dati speciali del codice a barre DataMatrix riconosciuto in C++."
type: docs
weight: 1500
url: /it/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


Memorizza dati speciali del codice a barre [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) riconosciuto

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** se tutti i parametri hanno solo valori predefiniti |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Ottiene l'ID del codice a barre [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) in modalità structured append. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Ottiene il conteggio dei codici a barre [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) in modalità structured append. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Ottiene l'ID del codice a barre [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) in modalità structured append. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1. |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [DataMatrixExtendedParameters](./). |
## Osservazioni


Questo esempio mostra come ottenere i valori grezzi [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/).
```cpp
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

## Vedi anche

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
