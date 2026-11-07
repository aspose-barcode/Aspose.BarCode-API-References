---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters classe"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters classe. Memorizza le informazioni di metadati MacroPdf417 del codice a barre riconosciuto in C++."
type: docs
weight: 2800
url: /it/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


Memorizza informazioni di metadati MacroPdf417 del codice a barre riconosciuto

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Flag che indica che il codice a barre MicroPdf417 è codificato con i codici di emulazione Code 128 908, 909, 910 o 911. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** se tutti i parametri hanno solo valori predefiniti |
| [get_IsLinked](./get_islinked/)() const | Flag che indica che il codice a barre deve essere collegato a un codice a barre 1D. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Nome del destinatario Macro PDF417 (opzionale). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Checksum Macro PDF417 (opzionale). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | Ottiene l'ID file del codice a barre, disponibile solo con MacroPdf417. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Nome file Macro PDF417 (opzionale). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Dimensione file Macro PDF417 (opzionale). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Ottiene l'ID segmento del codice a barre, disponibile solo con MacroPdf417. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Ottiene il conteggio dei segmenti del codice a barre macro pdf417. Il valore predefinito è -1. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Nome del mittente Macro PDF417 (opzionale). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Indica se il segmento è l'ultimo segmento di un file Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Marca temporale Macro PDF417 (opzionale). |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [Pdf417ExtendedParameters](./). |
## Osservazioni


Questo esempio mostra come ottenere i metadati Macro Pdf417.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

## Vedi anche

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
