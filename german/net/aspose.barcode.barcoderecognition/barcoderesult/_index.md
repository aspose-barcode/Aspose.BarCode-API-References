---
title: BarCodeResult
second_title: Aspose.BarCode für .NET-API-Referenz
description: Speichert erkannte Barcodedaten wieSingleDecodeType./singledecodetype TypString Codetext BarCodeRegionParameters./barcoderegionparameters Region und andere Parameter
type: docs
weight: 90
url: /de/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Speichert erkannte Barcodedaten wie[`SingleDecodeType`](../singledecodetype) Typ,String Codetext, [`BarCodeRegionParameters`](../barcoderegionparameters) Region und andere Parameter

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [BarCodeResult](barcoderesult)(BarCodeResult) | Erstellt eine Kopie der[`BarCodeResult`](../barcoderesult) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes) { get; } | Ruft die codierten Codebytes ab |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext) { get; } | Ruft den Codetext ab |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype) { get; } | Ruft den Barcodetyp ab |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename) { get; } | Ruft den Namen des Barcodetyps ab |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence) { get; } | Ruft das Erkennungskonfidenzniveau des erkannten Barcodes ab |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended) { get; } | Ruft erweiterte Parameter des erkannten Barcodes ab |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality) { get; } | Ruft die Lesequalität ab. Funktioniert für 1D- und Post-Barcodes. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region) { get; } | Ruft die Barcoderegion ab |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone)() | Erstellt eine Kopie von[`BarCodeResult`](../barcoderesult) Klasse. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals)(BarCodeResult) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einer angegebenen ist[`BarCodeResult`](../barcoderesult) wert. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals_1)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einer angegebenen ist[`BarCodeResult`](../barcoderesult) wert. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext)(Encoding) | Ruft den Codetext mit Codierung ab. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode)() | Gibt den Hashcode für diese Instanz zurück. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring)() | Gibt eine für Menschen lesbare Zeichenfolgendarstellung davon zurück[`BarCodeResult`](../barcoderesult) . |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality) | Gibt einen Wert zurück, der angibt, ob der erste[`BarCodeResult`](../barcoderesult) Wert ist gleich der Sekunde. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality) | Gibt einen Wert zurück, der angibt, ob der erste[`BarCodeResult`](../barcoderesult) Wert unterscheidet sich vom zweiten. |

### Beispiele

Dieses Beispiel zeigt, wie man BarCodeResult erhält.

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

### Siehe auch

* namensraum [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
