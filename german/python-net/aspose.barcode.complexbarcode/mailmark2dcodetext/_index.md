---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Klasse zum Codieren und Decodieren des in den Royal Mail 2D Mailmark-Code eingebetteten Textes.

Der Typ Mailmark2DCodetext stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Mailmark2DCodetext() | Initialisiert eine neue Instanz der Klasse Mailmark2DCodetext |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| upu_country_id | Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen. |
| information_type_id | Identifiziert die Royal Mail Mailmark-Barcode-Nutzlast für jeden Produkttyp. |
| version_id | Identifiziert die Barcode-Version, die für jede Informations‑Typ‑ID relevant ist. |
| klass | Identifiziert die Klasse des Elements. |
| supply_chain_id | Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist.<br/>            Maximaler Wert: 9999999. |
| item_id | Identifiziert das eindeutige Element innerhalb der Supply‑Chain‑ID.<br/>            Jeder Mailmark‑Barcode muss eine ID enthalten<br/>            damit er für mindestens 90 Tage eindeutig identifiziert werden kann.<br/>            Maximaler Wert: 99999999. |
| destination_post_code_and_dps | Enthält die Postleitzahl der Lieferadresse mit DPS<br/>            Bei Inland enthält die Postleitzahl/DP die folgende Anzahl von Zeichen.<br/>            Gebiet (1 oder 2 Zeichen) Bezirk (1 oder 2 Zeichen)<br/>            Sektor (1 Zeichen) Einheit (2 Zeichen) DPS (2 Zeichen).<br/>            Die Postleitzahl und DPS müssen einem gültigen PAF®‑Format entsprechen. |
| rts_flag | Flag, das angibt, welche Ebene des Rücksendeservices angefordert wird. |
| return_to_sender_post_code | Enthält die Rücksende-Postleitzahl, jedoch kein DPS.<br/>            Die PLZ (ohne DPS) muss einem PAF®‑Format entsprechen. |
| customer_content | Optionaler Raum zur Nutzung durch den Kunden. |
| customer_content_encode_mode | Kodierungsmodus des Datamatrix‑Barcodes.<br/>            Standardwert: EncodeMode.C40. |
| data_matrix_type | Der 2D‑Mailmark‑Typ definiert die Größe des Data‑Matrix‑Barcodes. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| get_constructed_codetext() | Erstelle Codetext aus Mailmark-Daten. |
| init_from_string(constructed_codetext) | Initialisiert Mailmark-Daten aus dem erstellten Codetext. |
| get_barcode_type() | Liest den Barcode-Typ. |

### Siehe auch

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

