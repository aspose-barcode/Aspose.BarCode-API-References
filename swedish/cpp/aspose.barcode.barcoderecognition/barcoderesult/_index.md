---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult class"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult klass. Lagrar igenkända streckkoddata som SingleDecodeType-typ, System::String kodtext, BarCodeRegionParameters-region och andra parametrar i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


Lagrar igenkända streckkoddata som [SingleDecodeType](../singledecodetype/) typ, **System::String** kodtext, [BarCodeRegionParameters](../barcoderegionparameters/) region och andra parametrar

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | Skapar en kopia av [BarCodeResult](./)-klassen. |
| [Clone](./clone/)() override | Skapar en kopia av [BarCodeResult](./)-klassen. |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [BarCodeResult](./)-värde. |
| [get_CodeBytes](./get_codebytes/)() const | Hämtar de kodade byte. |
| [get_CodeText](./get_codetext/)() const | Hämtar kodtexten |
| [get_CodeType](./get_codetype/)() const | Hämtar streckkodstypen |
| [get_CodeTypeName](./get_codetypename/)() | Hämtar namnet på streckkodstypen |
| [get_Confidence](./get_confidence/)() const | Hämtar igenkänningskonfidensnivån för den igenkända streckkoden |
| [get_Extended](./get_extended/)() const | Hämtar utökade parametrar för den igenkända streckkoden |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | Hämtar ISO/IEC-symbolkvalitetsutvärderingsresultaten för den igenkända streckkoden. |
| [get_ReadingQuality](./get_readingquality/)() const | Hämtar läskvaliteten. Fungerar för 1D- och poststreckkoder. |
| [get_Region](./get_region/)() const | Hämtar streckkodsområdet |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | Hämtar kodtexten med kodning. |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av denna [BarCodeResult](./). |
## Anmärkningar


Detta exempel visar hur man erhåller [BarCodeResult](./).
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

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
