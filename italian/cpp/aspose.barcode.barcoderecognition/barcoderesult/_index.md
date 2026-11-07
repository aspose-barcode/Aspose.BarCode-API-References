---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult classe"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult classe. Memorizza i dati del codice a barre riconosciuti come tipo SingleDecodeType, **System::String** codetext, BarCodeRegionParameters region e altri parametri in C++."
type: docs
weight: 700
url: /it/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


Memorizza i dati del codice a barre riconosciuti come tipo [SingleDecodeType](../singledecodetype/), **System::String** codetext, regione [BarCodeRegionParameters](../barcoderegionparameters/) e altri parametri

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | Crea una copia della classe [BarCodeResult](./). |
| [Clone](./clone/)() override | Crea una copia della classe [BarCodeResult](./). |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [BarCodeResult](./) specificato. |
| [get_CodeBytes](./get_codebytes/)() const | Ottiene i byte del codice codificato |
| [get_CodeText](./get_codetext/)() const | Ottiene il testo del codice |
| [get_CodeType](./get_codetype/)() const | Ottiene il tipo di codice a barre |
| [get_CodeTypeName](./get_codetypename/)() | Ottiene il nome del tipo di codice a barre |
| [get_Confidence](./get_confidence/)() const | Ottiene il livello di confidenza del riconoscimento del codice a barre riconosciuto |
| [get_Extended](./get_extended/)() const | Ottiene i parametri estesi del codice a barre riconosciuto |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | Ottiene i risultati della valutazione della qualità del simbolo ISO/IEC per il codice a barre riconosciuto. |
| [get_ReadingQuality](./get_readingquality/)() const | Ottiene la qualità di lettura. Funziona per codici a barre 1D e postali. |
| [get_Region](./get_region/)() const | Ottiene la regione del codice a barre |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | Ottiene il testo del codice con codifica. |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [BarCodeResult](./). |
## Osservazioni


Questo esempio mostra come ottenere [BarCodeResult](./).
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
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
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
