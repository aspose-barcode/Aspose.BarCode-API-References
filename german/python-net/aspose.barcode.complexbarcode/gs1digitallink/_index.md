---
title: "GS1DigitalLink"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

Stellt GS1 Digital Link-Codetext für das Codieren und Decodieren als geordnete Sequenz von<br/>            Application Identifier-Elementen dar. Die Quellreihenfolge und wiederholte Application Identifier werden beibehalten.<br/>            Der konstruierte Codetext ist ein unkomprimierter GS1 Digital Link-URI.<br/>            Nicht-GS1-Abfrageparameter und URI-Fragmente werden beim Parsen ignoriert.

Der GS1DigitalLink-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| GS1DigitalLink(uri_stem) | Initialisiert eine neue Instanz der GS1DigitalLink-Klasse |
| GS1DigitalLink(uri_stem, primary_application_identifier) | Initialisiert eine neue Instanz der GS1DigitalLink-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| uri_stem | Liefert das absolute URI-Präfix vor dem Pfadsegment des GS1-Hauptschlüssels.<br/>            Der Stamm enthält keinen Abfrage-String oder Fragment. |
| primary_application_identifier | Liefert den Anwendungsidentifikator, der als primärer Schlüssel des Digital Link verwendet wird.<br/>            Null bedeutet, dass der primäre Schlüssel automatisch ausgewählt wird, wenn die URI erstellt wird. |
| barcode_type | Liefert oder setzt den Barcode-Typ, der zum Codieren dieses GS1 Digital Link verwendet wird.<br/>            Unterstützte Typen sind QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF und Code128.<br/>            Der Standardwert ist QR. |
| Anzahl | Liefert die Anzahl der Anwendungsidentifikator-Elemente. |
| Elemente | Gibt eine Kopie aller Elemente in Quellreihenfolge zurück. |
## Indexer
| Name | Beschreibung |
| :- | :- |
| [index] | Gibt ein Element anhand seiner Position in der geordneten Sequenz zurück. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| create(uri_stem, codetext) | Erstellt einen GS1 Digital Link, indem alle Elemente aus dem GS1‑Codetext kopiert und der einzige verfügbare Primärschlüssel ausgewählt wird.<br/>             |
| create(uri_stem, codetext, primary_application_identifier) | Erstellt einen GS1 Digital Link, indem alle Elemente aus dem GS1‑Codetext kopiert und der einzige verfügbare Primärschlüssel ausgewählt wird.<br/>             |
| get_first(application_identifier) | Gibt den ersten Wert für einen Anwendungsidentifikator zurück. |
| get_all(application_identifier) | Gibt alle Werte für einen Anwendungsidentifikator in Quellreihenfolge zurück. |
| add(application_identifier, value) | Fügt ein validiertes Anwendungsidentifikator‑Element hinzu. |
| validate(value) | Validiert eine unkomprimierte GS1 Digital Link‑URI, ohne ein Objekt zu erstellen. |
| parse(value) | Parst eine unkomprimierte GS1 Digital Link‑URI. |
| try_parse(value, result, validation_result) | Versucht, eine unkomprimierte GS1 Digital Link‑URI zu parsen und gibt strukturierte Validierungsfehler zurück. |
| to_gs1_codetext() | Erstellt einen unabhängigen GS1‑Codetext, der die aktuellen GS1‑Elemente enthält.<br/>            Informationen, die nur die URI betreffen, werden nicht einbezogen. |
| to_uri_string() | Formatiert den aktuellen Objektzustand als unkomprimierte GS1 Digital Link‑URI. |
| get_constructed_codetext() | Konstruiert die unkomprimierte GS1 Digital Link‑URI. |
| init_from_string(constructed_codetext) | Initialisiert diese Instanz aus einer unkomprimierten GS1 Digital Link‑URI.<br/>            Der vorhandene Zustand wird erst ersetzt, nachdem die bereitgestellte URI erfolgreich geparst wurde.<br/>            Der ausgewählte Barcode‑Typ bleibt erhalten. |
| get_barcode_type() | Gibt den Barcode‑Typ zurück, der zum Codieren dieses GS1 Digital Link verwendet wird. |

### Siehe auch

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

