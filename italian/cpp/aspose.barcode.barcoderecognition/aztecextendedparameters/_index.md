---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class. Memorizza dati speciali del codice a barre Aztec riconosciuto in C++."
type: docs
weight: 300
url: /it/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Memorizza dati speciali del codice a barre Aztec riconosciuto

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** se tutti i parametri hanno solo valori predefiniti |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Ottiene l'ID del codice a barre Aztec in modalità structured append. L'ID parte da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Ottiene il conteggio dei codici a barre Aztec in modalità structured append. Il valore predefinito è 0. Il conteggio deve essere un valore da 1 a 26. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Ottiene l'ID file della modalità structured append Aztec. Il valore predefinito è una stringa vuota |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione della stringa leggibile dall'uomo di questo [AztecExtendedParameters](./). |
## Osservazioni


Questo esempio mostra come ottenere i valori grezzi Aztec
```cpp
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

## Vedi anche

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
