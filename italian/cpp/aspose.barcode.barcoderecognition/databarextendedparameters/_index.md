---
title: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters class"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters classe. Memorizza informazioni aggiuntive DataBar del codice a barre riconosciuto in C++."
type: docs
weight: 1400
url: /it/cpp/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class


Memorizza informazioni aggiuntive DataBar del codice a barre riconosciuto

```cpp
class DataBarExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Is2DCompositeComponent](./get_is2dcompositecomponent/)() const | Ottiene il flag del componente composito 2D DataBar. Il valore predefinito è false. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** se tutti i parametri hanno solo valori predefiniti |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile da un umano di questo [DataBarExtendedParameters](./). |
## Osservazioni


Questo esempio mostra come ottenere le informazioni aggiuntive DataBar
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

## Vedi anche

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
