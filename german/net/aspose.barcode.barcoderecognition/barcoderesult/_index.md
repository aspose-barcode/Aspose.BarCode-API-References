---
title: "Klasse BarCodeResult"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeResult Klasse. Speichert erkannte Barcode-Daten wie den SingleDecodeType-Typ, den String‑Codetext, BarCodeRegionParameters‑Region und weitere Parameter."
type: docs
weight: 100
url: /de/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Speichert erkannte Barcode-Daten wie den [`SingleDecodeType`](../singledecodetype/) Typ, den String‑Codetext, die [`BarCodeRegionParameters`](../barcoderegionparameters/) Region und weitere Parameter.

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | Erstellt eine Kopie der `BarCodeResult`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | Liefert die codierten Code‑Bytes |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | Liefert den Code‑Text |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | Liefert den Barcode‑Typ |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | Liefert den Namen des Barcode-Typs |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | Liefert das Erkennungs‑Vertrauensniveau des erkannten Barcodes |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | Liefert erweiterte Parameter des erkannten Barcodes |
| [IsoSymbolQuality](../../aspose.barcode.barcoderecognition/barcoderesult/isosymbolquality/) { get; } | Liefert die ISO/IEC‑Symbolqualitätsbewertungsergebnisse für den erkannten Barcode. |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | Liefert die Lesegüte. Funktioniert für 1D‑ und Post‑Barcodes. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | Liefert den Barcode‑Bereich |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | Erstellt eine Kopie der Klasse `BarCodeResult`. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `BarCodeResult`‑Wert entspricht. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `BarCodeResult`‑Wert entspricht. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | Liefert den Code‑Text mit Kodierung. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `BarCodeResult` zurück. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | Gibt einen Wert zurück, der angibt, ob der erste `BarCodeResult`‑Wert dem zweiten entspricht. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | Gibt einen Wert zurück, der angibt, ob der erste `BarCodeResult`‑Wert vom zweiten abweicht. |

## Beispiele

Dieses Beispiel zeigt, wie man ein BarCodeResult erhält.

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

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


