---
title: "enum"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode for C++ API-referens"
description: " enum. Innehåller igenkänningskonfidensnivå i C++."
type: docs
weight: 3500
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enum


Innehåller igenkänningskonfidensnivå.

```cpp
enum class BarCodeConfidence : int32_t
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) konfidens för streckkod där kodtexten inte identifierades korrekt eller streckkoden upptäcktes som möjlig förfalskning |
|  | Moderate | 80 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) konfidens för streckkod (mest 1D-streckkoder) med svag kontrollsumma eller utan den. Kan innehålla vissa felidentifieringar i kodtexten eller till och med falska identifieringar om |

är låg |
| Strong | 100 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) konfidens som bekräftades med BCH-koder som Reed–Solomon. Det får inte finnas fel i läst kodtext eller falska identifieringar |

## Anmärkningar


Detta exempel visar hur BarCodeConfidence förändras beroende på streckkodstyp
```cpp
[C#]
//Måttlig konfidens
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

//Hög konfidens
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

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
