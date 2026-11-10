---
title: "Klasse GS1DigitalLink"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink Klasse. Stellt GS1 Digital Link Codetext für das Codieren und Dekodieren als geordnete Sequenz von Application Identifier‑Elementen dar. Quellreihenfolge und wiederholte Application Identifier werden beibehalten. Der konstruierte Codetext ist ein unkomprimierter GS1 Digital Link‑URI. Nicht‑GS1‑Abfrageparameter und URI‑Fragmente werden beim Parsen ignoriert."
type: docs
weight: 540
url: /de/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

Stellt GS1‑Digital‑Link‑Codetext für die Kodierung und Dekodierung als geordnete Sequenz von Application‑Identifier‑Elementen dar. Die Quellreihenfolge und wiederholte Application Identifier werden beibehalten. Der erzeugte Codetext ist eine unkomprimierte GS1‑Digital‑Link‑URI. Nicht‑GS1‑Abfrageparameter und URI‑Fragmente werden beim Parsen ignoriert.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Initialisiert einen leeren GS1 Digital Link mit dem angegebenen URI‑Stamm. Der Primärschlüssel wird automatisch ausgewählt, wenn genau ein Primärschlüssel‑Kandidat vorhanden ist. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Initialisiert einen leeren GS1 Digital Link mit dem angegebenen URI‑Stamm und Primärschlüssel. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Liest oder setzt den Barcode‑Typ, der zum Codieren dieses GS1 Digital Link verwendet wird. Unterstützte Typen sind QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF und Code128. Der Standardwert ist QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Liest die Anzahl der Application Identifier‑Elemente. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Liest eine Kopie aller Elemente in Quellreihenfolge. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Liest ein Element anhand seiner Position in der geordneten Sequenz. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Liest den Application Identifier, der als Primärschlüssel des Digital Link verwendet wird. Null bedeutet, dass der Primärschlüssel automatisch ausgewählt wird, wenn der URI konstruiert wird. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | Liest das absolute URI‑Präfix vor dem Pfadsegment des GS1‑Primärschlüssels. Der Stamm enthält keinen Abfrage‑String oder Fragment. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | Erstellt einen GS1 Digital Link, indem alle Elemente aus dem GS1‑Codetext kopiert und der einzige verfügbare Primärschlüssel ausgewählt werden. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | Erstellt einen GS1 Digital Link, indem alle Elemente aus dem GS1‑Codetext kopiert und der angegebene Primärschlüssel verwendet werden. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Parst einen unkomprimierten GS1 Digital Link‑URI. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Fügt ein validiertes Application Identifier‑Element hinzu. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Liest alle Werte für einen Application Identifier in Quellreihenfolge. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Liest den Barcode‑Typ, der zum Codieren dieses GS1 Digital Link verwendet wird. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Konstruiert den unkomprimierten GS1 Digital Link‑URI. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Liest den ersten Wert für einen Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Initialisiert diese Instanz aus einem unkomprimierten GS1 Digital Link‑URI. Der vorhandene Zustand wird erst ersetzt, nachdem der bereitgestellte URI erfolgreich geparst wurde. Der ausgewählte Barcode‑Typ bleibt erhalten. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Erstellt einen unabhängigen GS1‑Codetext, der die aktuellen GS1‑Elemente enthält. URI‑nur‑Informationen werden nicht einbezogen. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Gibt den unkomprimierten GS1 Digital Link‑URI zurück. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Formatiert den aktuellen Objektzustand als unkomprimierten GS1 Digital Link‑URI. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Versucht, einen unkomprimierten GS1 Digital Link‑URI zu parsen und gibt strukturierte Validierungsfehler zurück. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Validiert einen unkomprimierten GS1 Digital Link‑URI, ohne ein Objekt zu erstellen. |

### Siehe auch

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


