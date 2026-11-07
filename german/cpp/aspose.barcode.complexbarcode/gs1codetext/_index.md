---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext class"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext class. Stellt GS1-Codetext für das Codieren und Dekodieren als geordnete Sequenz von Application Identifier-Elementen dar. Quellreihenfolge und wiederholte Application Identifier werden beibehalten. Die geklammerte Darstellung hat die Form (AI)value(AI)value. Eine wörtliche öffnende Klammer ''('' innerhalb eines Wertes muss als ( geschrieben werden; dies ist die einzige unterstützte Escape-Sequenz. Eine schließende Klammer '')'' innerhalb eines Wertes muss in C++ nicht escaped werden."
type: docs
weight: 500
url: /de/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


Stellt GS1‑Codetext für das Kodieren und Dekodieren als geordnete Sequenz von Application‑Identifier‑Elementen dar. Quellreihenfolge und wiederholte Application‑Identifier werden beibehalten. Die geklammerte Darstellung hat die Form (AI)Wert(AI)Wert. Eine wörtliche öffnende Klammer '(' innerhalb eines Wertes muss als (; geschrieben werden – dies ist die einzige unterstützte Escape‑Sequenz. Eine schließende Klammer ')' innerhalb eines Wertes muss nicht escaped werden.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Fügt ein validiertes Application Identifier‑Element hinzu. |
| [get_BarcodeType](./get_barcodetype/)() const | Liefert den Barcode-Typ, der zum Codieren dieses GS1-Codetexts verwendet wird. Unterstützte Typen sind GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR und GS1 DataBar-Typen. Der Standardwert ist GS1Code128. |
| [get_Count](./get_count/)() | Liefert die Anzahl der Application Identifier‑Elemente. |
| [get_Elements](./get_elements/)() | Liefert eine Kopie aller Elemente in Quellreihenfolge. |
| [GetAll](./getall/)(System::String) | Liefert alle Werte für einen Application Identifier in Quellreihenfolge. |
| [GetBarcodeType](./getbarcodetype/)() override | Liefert den Barcode-Typ, der zum Codieren dieses GS1-Codetexts verwendet wird. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Erstellt den geklammerten GS1-Codetext in der Form (AI)value(AI)value. Wörtliche öffnende Klammern in Werten werden als ( escaped. |
| [GetFirst](./getfirst/)(System::String) | Liefert den ersten Wert für einen Application Identifier. |
| [GS1Codetext](./gs1codetext/)() | Initialisiert einen leeren GS1-Codetext. |
| [idx_get](./idx_get/)(int32_t) | Liefert ein Element anhand seiner Position in der geordneten Sequenz. |
| [InitFromString](./initfromstring/)(System::String) override | Initialisiert diese Instanz aus einem geklammerten GS1-Codetext in der Form (AI)value(AI)value. Vorhandene Elemente werden erst ersetzt, nachdem der bereitgestellte Codetext erfolgreich geparst wurde. |
| static [Parse](./parse/)(System::String) | Parst einen geklammerten GS1-Element-String in der Form (AI)value(AI)value. Eine wörtliche '(' innerhalb eines Wertes muss als ( geschrieben werden; keine andere Escape-Sequenz wird unterstützt, und ')' muss nicht escaped werden. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Setzt den Barcode-Typ, der zum Codieren dieses GS1-Codetexts verwendet wird. Unterstützte Typen sind GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR und GS1 DataBar-Typen. Der Standardwert ist GS1Code128. |
| [ToString](./tostring/)() const override | Gibt die geklammerte GS1-Darstellung in der Form (AI)Wert(AI)Wert zurück. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Versucht, einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert zu analysieren und gibt strukturierte Validierungsfehler zurück. Ein wörtliches '(' innerhalb eines Wertes muss als ( geschrieben werden; andere Escape-Sequenzen werden nicht unterstützt, und ')' muss nicht escaped werden. |
| static [Validate](./validate/)(System::String) | Validiert einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert, ohne ein Objekt zu erstellen. Ein wörtliches '(' innerhalb eines Wertes muss als ( geschrieben werden; andere Escape-Sequenzen werden nicht unterstützt, und ')' muss nicht escaped werden. |
## Siehe auch

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
