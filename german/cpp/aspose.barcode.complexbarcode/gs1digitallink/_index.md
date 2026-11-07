---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class. Stellt den GS1 Digital Link‑Codetext für das Codieren und Decodieren als geordnete Sequenz von Application Identifier‑Elementen dar. Die Quellreihenfolge und wiederholte Application Identifier werden beibehalten. Der konstruierte Codetext ist ein unkomprimierter GS1 Digital Link‑URI. Nicht‑GS1‑Abfrageparameter und URI‑Fragmente werden beim Parsen in C++ ignoriert."
type: docs
weight: 600
url: /de/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


Stellt GS1 Digital Link‑Codetext für das Kodieren und Dekodieren als geordnete Sequenz von Application‑Identifier‑Elementen dar. Quellreihenfolge und wiederholte Application‑Identifier werden beibehalten. Der konstruierte Codetext ist ein unkomprimierter GS1 Digital Link‑URI. Nicht‑GS1‑Abfrageparameter und URI‑Fragmente werden beim Parsen ignoriert.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Fügt ein validiertes Application Identifier‑Element hinzu. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | Erstellt einen GS1 Digital Link, indem alle Elemente aus dem GS1‑Codetext kopiert und der einzige verfügbare Primärschlüssel ausgewählt werden. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | Erstellt einen GS1 Digital Link, indem alle Elemente aus dem GS1‑Codetext kopiert und der angegebene Primärschlüssel verwendet werden. |
| [get_BarcodeType](./get_barcodetype/)() const | Liefert den Barcode‑Typ, der zum Codieren dieses GS1 Digital Link verwendet wird. Unterstützte Typen sind QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF und Code128. Der Standardwert ist QR. |
| [get_Count](./get_count/)() | Liefert die Anzahl der Application Identifier‑Elemente. |
| [get_Elements](./get_elements/)() | Liefert eine Kopie aller Elemente in Quellreihenfolge. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Liefert den Application Identifier, der als Primärschlüssel des Digital Link verwendet wird. Null bedeutet, dass der Primärschlüssel automatisch ausgewählt wird, wenn der URI erstellt wird. |
| [get_UriStem](./get_uristem/)() const | Liefert das absolute URI‑Präfix vor dem Pfadsegment des GS1‑Primärschlüssels. Der Stamm enthält keinen Abfrage‑String oder Fragment. |
| [GetAll](./getall/)(System::String) | Liefert alle Werte für einen Application Identifier in Quellreihenfolge. |
| [GetBarcodeType](./getbarcodetype/)() override | Liefert den Barcode-Typ, der zum Codieren dieses GS1 Digital Link verwendet wird. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Erstellt die unkomprimierte GS1 Digital Link-URI. |
| [GetFirst](./getfirst/)(System::String) | Liefert den ersten Wert für einen Application Identifier. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | Initialisiert einen leeren GS1 Digital Link mit dem angegebenen URI-Stamm. Der Primärschlüssel wird automatisch ausgewählt, wenn genau ein Primärschlüssel-Kandidat vorhanden ist. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | Initialisiert einen leeren GS1 Digital Link mit dem angegebenen URI-Stamm und Primärschlüssel. |
| [idx_get](./idx_get/)(int32_t) | Liefert ein Element anhand seiner Position in der geordneten Sequenz. |
| [InitFromString](./initfromstring/)(System::String) override | Initialisiert diese Instanz aus einer unkomprimierten GS1 Digital Link-URI. Der vorhandene Zustand wird erst ersetzt, nachdem die bereitgestellte URI erfolgreich geparst wurde. Der ausgewählte Barcode-Typ bleibt erhalten. |
| static [Parse](./parse/)(System::String) | Parst eine unkomprimierte GS1 Digital Link-URI. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Setzt den Barcode-Typ, der zum Codieren dieses GS1 Digital Link verwendet wird. Unterstützte Typen sind QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF und Code128. Der Standardwert ist QR. |
| [ToGS1Codetext](./togs1codetext/)() | Erstellt einen unabhängigen GS1-Codetext, der die aktuellen GS1-Elemente enthält. Informationen, die nur die URI betreffen, werden nicht einbezogen. |
| [ToString](./tostring/)() const override | Gibt die unkomprimierte GS1 Digital Link-URI zurück. |
| [ToUriString](./touristring/)() | Formatiert den aktuellen Objektzustand als unkomprimierte GS1 Digital Link-URI. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Versucht, eine unkomprimierte GS1 Digital Link-URI zu parsen und gibt strukturierte Validierungsfehler zurück. |
| static [Validate](./validate/)(System::String) | Validiert eine unkomprimierte GS1 Digital Link-URI, ohne ein Objekt zu erstellen. |
## Siehe auch

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
