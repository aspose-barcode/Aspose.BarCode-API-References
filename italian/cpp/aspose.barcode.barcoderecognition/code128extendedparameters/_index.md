---
title: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class. Memorizza dati speciali del codice a barre Code128 riconosciuto in C++."
type: docs
weight: 1300
url: /it/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


Memorizza dati speciali del codice a barre Code128 riconosciuto

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | Ottiene l'array [Code128DataPortion](../code128dataportion/) del codice a barre Code128 riconosciuto |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** se tutti i parametri hanno solo valori predefiniti |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [Code128ExtendedParameters](./). |
## Osservazioni


Rappresenta la regione del codice a barre riconosciuto e l'angolo del codice a barre

Questo esempio mostra come ottenere i valori grezzi di code128
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

## Vedi anche

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
