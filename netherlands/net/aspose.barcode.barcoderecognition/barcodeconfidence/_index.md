---
title: BarCodeConfidence
second_title: Aspose.BarCode voor .NET API-referentie
description: Bevat betrouwbaarheidsniveau voor herkenning
type: docs
weight: 40
url: /nl/net/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enumeration

Bevat betrouwbaarheidsniveau voor herkenning

```csharp
public enum BarCodeConfidence
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Herkenningsvertrouwen van streepjescode waarbij codetekst niet correct werd herkend of streepjescode werd gedetecteerd als mogelijk nep |
| Moderate | `80` | Herkenningszekerheid van streepjescode (meestal 1D-streepjescodes) met zwakke controlesom of zelfs zonder. Could bevat enkele verkeerde herkenningen in codetext of zelfs valse herkenningen if is laag |
| Strong | `100` | Herkenningsvertrouwen die werd bevestigd met BCH-codes zoals Reed-Solomon. Er mogen geen fouten zijn in gelezen codetekst of valse herkenningen |

### Voorbeelden

Dit voorbeeld laat zien hoe BarCodeConfidence is veranderd, afhankelijk van het type streepjescode

```csharp
[C#]
// Matig vertrouwen
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
    }
}

// Sterk vertrouwen
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}
[VB.NET]
'Matig vertrouwen
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Sterk vertrouwen
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

### Zie ook

* naamruimte [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
