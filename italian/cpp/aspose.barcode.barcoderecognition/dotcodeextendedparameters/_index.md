---
title: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters classe"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters classe. Memorizza dati speciali del codice a barre DotCode riconosciuto in C++."
type: docs
weight: 2000
url: /it/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


Memorizza dati speciali del codice a barre DotCode riconosciuto

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** se tutti i parametri hanno solo valori predefiniti |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Restituisce l'ID del codice a barre DotCode in modalità di aggiunta strutturata. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Restituisce il conteggio dei codici a barre DotCode in modalità di aggiunta strutturata. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [DotCodeExtendedParameters](./). |
## Osservazioni


Questo esempio mostra come ottenere i valori grezzi di DotCode
```cpp
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

## Vedi anche

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
