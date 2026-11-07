---
title: "enum"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " enum. Bevat het herkenningsvertrouwensniveau in C++."
type: docs
weight: 3500
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enum


Bevat herkenningsvertrouwensniveau

```cpp
enum class BarCodeConfidence : int32_t
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) vertrouwen van barcode waarbij de codetekst niet correct werd herkend of de barcode werd gedetecteerd als mogelijk nep. |
|  | Moderate | 80 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) vertrouwen van barcode (voornamelijk 1D-barcodes) met een zwakke checksum of zelfs zonder. Kan enkele misherkenningen in de codetekst bevatten of zelfs valse herkenningen als |

is laag |
| Strong | 100 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) vertrouwen dat bevestigd is met BCH-codes zoals Reed–Solomon. Er mogen geen fouten zijn in de gelezen codetekst of valse herkenningen. |

## Opmerkingen


Dit voorbeeld toont hoe BarCodeConfidence verandert, afhankelijk van het barcode-type.
```cpp
[C#]
//Matig vertrouwen
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
    }
}

//Sterk vertrouwen
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.QR))
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
'Moderate confidence
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Strong confidence
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
