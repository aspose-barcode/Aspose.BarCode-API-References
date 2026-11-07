---
title: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters classe"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters classe. Memorizza dati speciali del codice a barre 1D riconosciuto, come testo del codice separato e checksum, in C++."
type: docs
weight: 2700
url: /it/cpp/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class


Memorizza dati speciali del codice a barre 1D riconosciuto, come testo del codice separato e checksum

```cpp
class OneDExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_CheckSum](./get_checksum/)() const | Ottiene il checksum per i codici a barre 1D. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** se tutti i parametri hanno solo valori predefiniti |
| [get_Value](./get_value/)() const | Ottiene il testo del codice dei codici a barre 1D senza checksum. |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [OneDExtendedParameters](./). |
## Osservazioni


Questo esempio mostra come ottenere il valore e il checksum del codice a barre 1D.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## Vedi anche

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
