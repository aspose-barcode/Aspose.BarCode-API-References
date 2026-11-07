---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class. Rappresenta la regione del codice a barre riconosciuto e l'angolo del codice a barre in C++."
type: docs
weight: 600
url: /it/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


Rappresenta la regione del codice a barre riconosciuto e l'angolo del codice a barre

```cpp
class BarCodeRegionParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Angle](./get_angle/)() const | Restituisce l'angolo del codice a barre (0-360). |
| [get_Points](./get_points/)() const | Restituisce l'array di [Point](../) che delimita la regione del codice a barre |
| [get_Quadrangle](./get_quadrangle/)() const | Restituisce il [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) che delimita la regione del codice a barre |
| [get_Rectangle](./get_rectangle/)() const | Restituisce il **System::Drawing::Rectangle** che delimita la regione del codice a barre |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [BarCodeRegionParameters](./). |
## Osservazioni


Questo esempio mostra come ottenere l'angolo del codice a barre e i valori del quadrilatero di delimitazione
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
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
