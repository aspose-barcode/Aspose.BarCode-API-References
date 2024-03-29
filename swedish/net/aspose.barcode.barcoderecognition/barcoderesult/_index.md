---
title: BarCodeResult
second_title: Aspose.BarCode för .NET API-referens
description: Lagrar igenkänd streckkodsdata somSingleDecodeType./singledecodetype typString kodtext BarCodeRegionParameters./barcoderegionparameters region och andra parametrar
type: docs
weight: 90
url: /sv/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Lagrar igenkänd streckkodsdata som[`SingleDecodeType`](../singledecodetype) typ,String kodtext, [`BarCodeRegionParameters`](../barcoderegionparameters) region och andra parametrar

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BarCodeResult](barcoderesult)(BarCodeResult) | Skapar en kopia av[`BarCodeResult`](../barcoderesult) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes) { get; } | Hämtar den kodade kodbyten |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext) { get; } | Hämtar kodtexten |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype) { get; } | Hämtar streckkodstypen |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename) { get; } | Hämtar namnet på streckkodstypen |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence) { get; } | Får igenkänningskonfidensnivå för den erkända streckkoden |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended) { get; } | Får utökade parametrar för erkänd streckkod |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality) { get; } | Får läskvaliteten. Fungerar för 1D och poststreckkoder. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region) { get; } | Hämtar streckkodsregionen |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone)() | Skapar en kopia av[`BarCodeResult`](../barcoderesult) class. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals)(BarCodeResult) | Returnerar ett värde som anger om denna instans är lika med en specificerad[`BarCodeResult`](../barcoderesult) värde. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals_1)(object) | Returnerar ett värde som anger om denna instans är lika med en specificerad[`BarCodeResult`](../barcoderesult) värde. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext)(Encoding) | Hämtar kodtexten med kodning. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode)() | Returnerar hashkoden för denna instans. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring)() | Returnerar en mänsklig läsbar strängrepresentation av detta[`BarCodeResult`](../barcoderesult) . |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality) | Returnerar ett värde som anger om det första[`BarCodeResult`](../barcoderesult) värdet är lika med sekunden. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality) | Returnerar ett värde som anger om det första[`BarCodeResult`](../barcoderesult) värdet skiljer sig från det andra. |

### Exempel

Detta exempel visar hur man får streckkodsresultat.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
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
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### Se även

* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
