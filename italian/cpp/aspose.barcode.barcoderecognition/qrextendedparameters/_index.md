---
title: "Classe Aspose::BarCode::BarCodeRecognition::QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Classe Aspose::BarCode::BarCodeRecognition::QRExtendedParameters. Memorizza le informazioni Structured Append del QR del codice a barre riconosciuto in C++."
type: docs
weight: 2900
url: /it/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


Memorizza le informazioni Structured Append del [QR](../../aspose.barcode.barcoderecognition.qr/) del codice a barre riconosciuto

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | Livello di correzione errori Reed-Solomon del codice a barre riconosciuto. Da basso a alto: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** se tutti i parametri hanno solo valori predefiniti |
| [get_MicroQRVersion](./get_microqrversion/)() const | Versione del MicroQR Code riconosciuto. Da M1 a M4. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | Versione del RectMicroQR Code riconosciuto. Da R7x43 a R17x139. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | Ottiene l'indice del codice a barre in modalità structured append del [QR](../../aspose.barcode.barcoderecognition.qr/). L'indice parte da 0. Il valore predefinito è -1. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | Ottiene la quantità di codici a barre in modalità structured append del [QR](../../aspose.barcode.barcoderecognition.qr/). Il valore predefinito è -1. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | Ottiene i dati di parità della modalità structured append del [QR](../../aspose.barcode.barcoderecognition.qr/). Il valore predefinito è -1. |
| [get_Version](./get_version/)() const | Versione del [QR](../../aspose.barcode.barcoderecognition.qr/) Code riconosciuto. Da Version1 a Version40. |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [QRExtendedParameters](./). |
## Osservazioni


Questo esempio mostra come ottenere i dati Structured Append del [QR](../../aspose.barcode.barcoderecognition.qr/)
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

## Vedi anche

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
