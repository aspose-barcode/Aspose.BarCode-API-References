---
title: "Klasse MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeStructuredCodetext Klasse. Basisklasse für das Codieren und Decodieren des in den MaxiCode-Code eingebetteten Textes für die Modi 2 und 3."
type: docs
weight: 740
url: /de/net/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class

Basisklasse für das Codieren und Dekodieren des in den MaxiCode‑Code eingebetteten Textes für die Modi 2 und 3.

```csharp
public abstract class MaxiCodeStructuredCodetext : MaxiCodeCodetext
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CountryCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/countrycode/) { get; set; } | Identifiziert den 3‑stelligen Ländercode. |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | Liest oder setzt die ECI‑Kodierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1. |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | Liest oder setzt einen MaxiCode‑Kodierungsmodus. Standardwert: Auto. |
| [PostalCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/postalcode/) { get; set; } | Identifiziert die Postleitzahl. Muss 9 Ziffern im Modus 2 oder 6 alphanumerische Zeichen im Modus 3 sein. |
| [SecondMessage](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/secondmessage/) { get; set; } | Identifiziert die zweite Nachricht des Barcodes. |
| [ServiceCategory](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/servicecategory/) { get; set; } | Identifiziert die 3‑stellige Servicekategorie. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `MaxiCodeStructuredCodetext`‑Wert entspricht. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Liest den Barcode‑Typ. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/getconstructedcodetext/)() | Erstellt den Codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | Liest den MaxiCode‑Modus. |
| override [InitFromString](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/initfromstring/)(string) | Initialisiert die Instanz aus dem erstellten Codetext. |

## Beispiele

Dieses Beispiel zeigt, wie roher MaxiCode‑Codetext in eine MaxiCodeStructuredCodetext‑Instanz dekodiert wird.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

### Siehe auch

* class [MaxiCodeCodetext](../maxicodecodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


