---
title: "enum"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Enum. Enthält das Erkennungs‑Vertrauensniveau in C++."
type: docs
weight: 3500
url: /de/cpp/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enum


Enthält das Erkennungs‑Vertrauensniveau.

```cpp
enum class BarCodeConfidence : int32_t
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) Vertrauen des Barcodes, bei dem der Codetext nicht korrekt erkannt wurde oder der Barcode als möglicher Fake erkannt wurde |
|  | Moderate | 80 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) Vertrauen des Barcodes (hauptsächlich 1D‑Barcodes) mit schwacher Prüfsumme oder sogar ohne. Könnte einige Fehlinterpretationen im Codetext oder sogar falsche Erkennungen enthalten, wenn |

ist niedrig |
| Strong | 100 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) Vertrauen, das mit BCH‑Codes wie Reed–Solomon bestätigt wurde. Es dürfen keine Fehler im gelesenen Codetext oder falsche Erkennungen auftreten. |

## Hinweise


Dieses Beispiel zeigt, wie sich BarCodeConfidence je nach Barcode‑Typ ändert.
```cpp
[C#]
//Mäßiges Vertrauen
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

//Starkes Vertrauen
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

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
