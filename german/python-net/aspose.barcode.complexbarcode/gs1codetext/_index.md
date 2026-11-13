---
title: "GS1Codetext"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

Stellt GS1-Codetext für das Codieren und Decodieren als geordnete Sequenz von<br/>            Application Identifier-Elementen dar. Die Quellreihenfolge und wiederholte Application Identifier<br/>            werden beibehalten. Die geklammerte Darstellung hat die Form (AI)Wert(AI)Wert.<br/>            Eine wörtliche öffnende Klammer '(' innerhalb eines Wertes muss als \\(; geschrieben werden, dies ist die<br/>            einzige unterstützte Escape-Sequenz. Eine schließende Klammer ')' innerhalb eines Wertes muss<br/>            nicht escaped werden.

Der GS1Codetext-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| GS1Codetext() | Initialisiert eine neue Instanz der Klasse GS1Codetext |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| barcode_type | Liest oder setzt den Barcode-Typ, der zum Codieren dieses GS1-Codetextes verwendet wird.<br/>            Unterstützte Typen sind GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix,<br/>            GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR und GS1 DataBar Typen.<br/>            Der Standardwert ist GS1Code128. |
| Anzahl | Liefert die Anzahl der Anwendungsidentifikator-Elemente. |
| Elemente | Gibt eine Kopie aller Elemente in Quellreihenfolge zurück. |
## Indexer
| Name | Beschreibung |
| :- | :- |
| [index] | Gibt ein Element anhand seiner Position in der geordneten Sequenz zurück. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| get_first(application_identifier) | Gibt den ersten Wert für einen Anwendungsidentifikator zurück. |
| get_all(application_identifier) | Gibt alle Werte für einen Anwendungsidentifikator in Quellreihenfolge zurück. |
| add(application_identifier, value) | Fügt ein validiertes Anwendungsidentifikator‑Element hinzu. |
| validate(value) | Validiert einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert ohne<br/>            ein Objekt zu erstellen. Ein wörtliches '(' innerhalb eines Wertes muss als \\( geschrieben werden; keine<br/>            andere Escape-Sequenz wird unterstützt, und ')' muss nicht escaped werden. |
| parse(value) | Parst einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert. Ein wörtliches<br/>            '(' innerhalb eines Wertes muss als \\( geschrieben werden; keine andere Escape-Sequenz wird unterstützt,<br/>            und ')' muss nicht escaped werden. |
| try_parse(value, result, validation_result) | Versucht, einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert zu parsen<br/>            und gibt strukturierte Validierungsfehler zurück. Ein wörtliches '(' innerhalb eines Wertes muss<br/>            als \\( geschrieben werden; keine andere Escape-Sequenz wird unterstützt, und ')' muss nicht<br/>            escaped werden. |
| get_constructed_codetext() | Konstruiert den geklammerten GS1-Codetext in der Form (AI)Wert(AI)Wert.<br/>            Literal öffnende Klammern in Werten werden als \\( escaped. |
| init_from_string(constructed_codetext) | Initialisiert diese Instanz aus einem geklammerten GS1-Codetext in der Form (AI)Wert(AI)Wert.<br/>            Vorhandene Elemente werden erst ersetzt, nachdem der bereitgestellte Codetext erfolgreich geparst wurde. |
| get_barcode_type() | Liest den Barcode-Typ, der zum Codieren dieses GS1-Codetextes verwendet wird. |

### Siehe auch

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

