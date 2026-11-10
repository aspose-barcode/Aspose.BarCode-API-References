---
title: "Klasse GS1Codetext"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext Klasse. Stellt GS1‑Codetext für das Codieren und Dekodieren als geordnete Sequenz von Application Identifier‑Elementen dar. Quellreihenfolge und wiederholte Application Identifier werden beibehalten. Die klammerbasierte Darstellung hat die Form AIvalueAIvalue. Eine wörtliche öffnende Klammer innerhalb eines Wertes muss als geschrieben werden, dies ist die einzige unterstützte Escape‑Sequenz. Eine schließende Klammer innerhalb eines Wertes muss nicht escaped werden."
type: docs
weight: 530
url: /de/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

Stellt GS1‑Codetext für die Kodierung und Dekodierung als geordnete Sequenz von Application‑Identifier‑Elementen dar. Die Quellreihenfolge und wiederholte Application Identifier werden beibehalten. Die geklammerte Darstellung hat die Form (AI)Wert(AI)Wert. Eine wörtliche öffnende Klammer '(' innerhalb eines Wertes muss als \\(? geschrieben werden; dies ist die einzige unterstützte Escape‑Sequenz. Eine schließende Klammer ')' innerhalb eines Wertes muss nicht escaped werden.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Liest oder setzt den Barcode-Typ, der zum Codieren dieses GS1-Codetextes verwendet wird. Unterstützte Typen sind GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR und GS1 DataBar Typen. Der Standardwert ist GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Liest die Anzahl der Application Identifier‑Elemente. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Liest eine Kopie aller Elemente in Quellreihenfolge. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Liest ein Element anhand seiner Position in der geordneten Sequenz. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Parst einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert. Ein wörtliches '(' innerhalb eines Wertes muss als \( geschrieben werden; andere Escape-Sequenzen werden nicht unterstützt, und ')' muss nicht escaped werden. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Fügt ein validiertes Application Identifier‑Element hinzu. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Liest alle Werte für einen Application Identifier in Quellreihenfolge. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Liest den Barcode-Typ, der zum Codieren dieses GS1-Codetextes verwendet wird. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Erstellt den geklammerten GS1-Codetext in der Form (AI)Wert(AI)Wert. Wörtliche öffnende Klammern in Werten werden als \( escaped. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Liest den ersten Wert für einen Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Initialisiert diese Instanz aus einem geklammerten GS1-Codetext in der Form (AI)Wert(AI)Wert. Vorhandene Elemente werden erst ersetzt, nachdem der bereitgestellte Codetext erfolgreich geparst wurde. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Gibt die geklammerte GS1-Darstellung in der Form (AI)Wert(AI)Wert zurück. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Versucht, einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert zu parsen und gibt strukturierte Validierungsfehler zurück. Ein wörtliches '(' innerhalb eines Wertes muss als \( geschrieben werden; andere Escape-Sequenzen werden nicht unterstützt, und ')' muss nicht escaped werden. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Validiert einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert, ohne ein Objekt zu erstellen. Ein wörtliches '(' innerhalb eines Wertes muss als \( geschrieben werden; andere Escape-Sequenzen werden nicht unterstützt, und ')' muss nicht escaped werden. |

### Siehe auch

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


