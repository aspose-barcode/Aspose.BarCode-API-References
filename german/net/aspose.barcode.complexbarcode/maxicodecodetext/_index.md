---
title: "Klasse MaxiCodeCodetext"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeCodetext Klasse. Basisklasse zum Codieren und Dekodieren des in den MaxiCode-Code eingebetteten Textes."
type: docs
weight: 680
url: /de/net/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class

Basisklasse für das Codieren und Dekodieren des in den MaxiCode‑Code eingebetteten Textes.

```csharp
public abstract class MaxiCodeCodetext : IComplexCodetext
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | Liest oder setzt die ECI‑Kodierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1. |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | Liest oder setzt einen MaxiCode‑Kodierungsmodus. Standardwert: Auto. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Liest den Barcode‑Typ. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodecodetext/getconstructedcodetext/)() | Erstellt den Codetext |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | Liest den MaxiCode‑Modus. |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/maxicodecodetext/initfromstring/)(string) | Initialisiert die Instanz aus dem erstellten Codetext. |

## Beispiele

Dieses Beispiel zeigt, wie man rohen MaxiCode-Codetext in eine MaxiCodeCodetext-Instanz dekodiert.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### Siehe auch

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


