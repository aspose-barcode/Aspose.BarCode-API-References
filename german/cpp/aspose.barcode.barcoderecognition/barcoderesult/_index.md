---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult Klasse"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult Klasse. Speichert erkannte Barcode-Daten wie SingleDecodeType Typ, **System::String** codetext, BarCodeRegionParameters Region und weitere Parameter in C++."
type: docs
weight: 700
url: /de/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


Speichert erkannte Barcode-Daten wie den Typ [SingleDecodeType](../singledecodetype/), **System::String** codetext, die Region [BarCodeRegionParameters](../barcoderegionparameters/) und weitere Parameter.

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | Erstellt eine Kopie der Klasse [BarCodeResult](./). |
| [Clone](./clone/)() override | Erstellt eine Kopie der Klasse [BarCodeResult](./). |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BarCodeResult](./)-Wert entspricht. |
| [get_CodeBytes](./get_codebytes/)() const | Liefert die kodierten Code‑Bytes. |
| [get_CodeText](./get_codetext/)() const | Liefert den Code‑Text. |
| [get_CodeType](./get_codetype/)() const | Liefert den Barcode‑Typ. |
| [get_CodeTypeName](./get_codetypename/)() | Liefert den Namen des Barcode‑Typs. |
| [get_Confidence](./get_confidence/)() const | Liefert das Erkennungs‑Vertrauensniveau des erkannten Barcodes. |
| [get_Extended](./get_extended/)() const | Liefert erweiterte Parameter des erkannten Barcodes. |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | Liefert die ISO/IEC‑Symbolqualitäts‑Bewertungsergebnisse für den erkannten Barcode. |
| [get_ReadingQuality](./get_readingquality/)() const | Liefert die Lesegüte. Funktioniert für 1D‑ und Post‑Barcodes. |
| [get_Region](./get_region/)() const | Liefert die Barcode‑Region. |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | Liefert den Code‑Text mit Kodierung. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [BarCodeResult](./) zurück. |
## Hinweise


Dieses Beispiel zeigt, wie man [BarCodeResult](./) erhält.
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

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
