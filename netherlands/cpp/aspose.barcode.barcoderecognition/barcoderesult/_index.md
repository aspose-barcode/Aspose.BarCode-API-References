---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult class"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult class. Slaat herkende barcodegegevens op zoals SingleDecodeType type, System::String codetext, BarCodeRegionParameters regio en andere parameters in C++."
type: docs
weight: 700
url: /nl/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


Slaat herkende barcodegegevens op zoals [SingleDecodeType](../singledecodetype/) type, **System::String** codetext, [BarCodeRegionParameters](../barcoderegionparameters/) regio en andere parameters

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | Maakt een kopie van de [BarCodeResult](./) klasse. |
| [Clone](./clone/)() override | Maakt een kopie van de [BarCodeResult](./) klasse. |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BarCodeResult](./) waarde. |
| [get_CodeBytes](./get_codebytes/)() const | Haalt de gecodeerde codebytes op. |
| [get_CodeText](./get_codetext/)() const | Haalt de code-tekst op. |
| [get_CodeType](./get_codetype/)() const | Haalt het barcode-type op. |
| [get_CodeTypeName](./get_codetypename/)() | Haalt de naam van het barcode-type op. |
| [get_Confidence](./get_confidence/)() const | Haalt het herkenningsvertrouwensniveau van de herkende barcode op. |
| [get_Extended](./get_extended/)() const | Haalt uitgebreide parameters van de herkende barcode op. |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | Haalt de ISO/IEC symboolkwaliteitsbeoordelingsresultaten voor de herkende barcode op. |
| [get_ReadingQuality](./get_readingquality/)() const | Haalt de leeskwaliteit op. Werkt voor 1D- en postbarcode. |
| [get_Region](./get_region/)() const | Haalt de barcode-regio op. |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | Haalt de code-tekst op met codering. |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [BarCodeResult](./). |
## Opmerkingen


Dit voorbeeld laat zien hoe u [BarCodeResult](./) verkrijgt.
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

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
