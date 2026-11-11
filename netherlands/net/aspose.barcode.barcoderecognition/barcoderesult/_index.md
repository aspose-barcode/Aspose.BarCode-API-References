---
title: "Klasse BarCodeResult"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeResult class. Slaat herkende barcode-gegevens op, zoals SingleDecodeType type, String codetext, BarCodeRegionParameters regio en andere parameters."
type: docs
weight: 100
url: /nl/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Slaat herkende barcode-gegevens op, zoals [`SingleDecodeType`](../singledecodetype/) type, String codetext, [`BarCodeRegionParameters`](../barcoderegionparameters/) regio en andere parameters.

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | Maakt een kopie van de `BarCodeResult` class. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | Haalt de gecodeerde code-bytes op |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | Haalt de code-tekst op |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | Haalt het barcode-type op |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | Haalt de naam van het barcode-type op |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | Haalt het herkennings-vertrouwensniveau van de herkende barcode op |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | Haalt uitgebreide parameters van de herkende barcode op |
| [IsoSymbolQuality](../../aspose.barcode.barcoderecognition/barcoderesult/isosymbolquality/) { get; } | Haalt de ISO/IEC-symboolkwaliteitsbeoordelingsresultaten op voor de herkende barcode. |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | Haalt de leeskwaliteit op. Werkt voor 1D- en postbarcode. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | Haalt de barcode-regio op |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | Maakt een kopie van de `BarCodeResult`-klasse. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `BarCodeResult`-waarde. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `BarCodeResult`-waarde. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | Haalt de code-tekst op met codering. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | Retourneert de hashcode voor deze instantie. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `BarCodeResult`. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | Retourneert een waarde die aangeeft of de eerste `BarCodeResult`-waarde gelijk is aan de tweede. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | Retourneert een waarde die aangeeft of de eerste `BarCodeResult`-waarde verschilt van de tweede. |

## Voorbeelden

Dit voorbeeld toont hoe u BarCodeResult kunt verkrijgen.

```csharp
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

### Zie ook

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


