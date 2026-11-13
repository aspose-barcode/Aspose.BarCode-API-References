---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

Klasse zum Codieren und Decodieren des in den 4‑State Royal Mailmark-Code eingebetteten Textes.

Der MailmarkCodetext-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| MailmarkCodetext() | Initialisiert eine neue Instanz der MailmarkCodetext-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| format | "0" – Null oder Test<br/>            "1" – Brief<br/>            "2" – Großer Brief |
| version_id | Derzeit "1" – Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z für zukünftige Verwendung reserviert) |
| klass | "0" - Null oder Test<br/>            "1" - 1C (Einzelhandel)<br/>            "2" - 2C (Einzelhandel)<br/>            "3" - 3C (Einzelhandel)<br/>            "4" - Premium (RetailPublishing Mail) (für potenzielle zukünftige Verwendung)<br/>            "5" - Deferred (Einzelhandel)<br/>            "6" - Air (Einzelhandel) (für potenzielle zukünftige Verwendung)<br/>            "7" - Surface (Einzelhandel) (für potenzielle zukünftige Verwendung)<br/>            "8" - Premium (Netzwerkzugriff)<br/>            "9" - Standard (Netzwerkzugriff) |
| supply_chain_id | Maximale Werte sind 99 für Barcode C und 999999 für Barcode L. |
| item_id | Maximaler Wert ist 99999999. |
| destination_post_code_and_dps | Der PC und DP müssen dem PAF-Format entsprechen.<br/>            Neun Zeichen lange Zeichenkette, die das internationale "XY11     " bezeichnet (beachten Sie die 5 nachfolgenden Leerzeichen) oder ein Muster<br/>            von Zeichen, das einen nationalen Sortiercode bezeichnet.<br/>            Ein nationaler Sortiercode besteht aus einer Außen-Postleitzahl, einer Innen-Postleitzahl und einem Lieferpunkt‑Suffix. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| get_constructed_codetext() | Erstelle Codetext aus Mailmark-Daten. |
| init_from_string(constructed_codetext) | Initialisiert Mailmark-Daten aus dem erstellten Codetext. |
| get_barcode_type() | Liest den Barcode-Typ. |

### Siehe auch

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

