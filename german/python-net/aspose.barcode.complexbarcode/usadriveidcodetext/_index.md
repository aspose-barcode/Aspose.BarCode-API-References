---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

Klasse zum Codieren und Decodieren des in den USA-Führerschein PDF417-Code eingebetteten Textes.

Der Typ USADriveIdCodetext stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| USADriveIdCodetext() | Initialisiert eine neue Instanz der USADriveIdCodetext-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| issuer_identification_number | Diese Nummer identifiziert eindeutig <br/>            die ausstellende Gerichtsbarkeit und kann durch Kontaktaufnahme mit der ISO<br/>            Ausstellungsbehörde(AAMVA) erhalten werden.  Der vollständige 6‑stellige IIN sollte codiert werden. |
| aamva_version_number | AAMVA Versionsnummer 00-99 |
| jurisdiction_version_number | Jurisdiktion Versionsnummer 00-99 |
| number_of_entries | Anzahl 00-99 der Unterdateien |
| subfile_designator | Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. <br/>            Wichtig: Nur Typ, Offset und Länge setzen, werden automatisch festgelegt. |
| mandatory_elements | Obligatorische Elemente (Felder) der Karte |
| optional_elements | Optionale Elemente (Felder) der Karte |
| jurisdiction_specific_subfile | Jurisdiktion-spezifische Felder |
## Methoden
| Name | Beschreibung |
| :- | :- |
| get_constructed_codetext() | Erstelle Codetext aus USA DL-Daten |
| init_from_string(constructed_codetext) | Initialisiere USA DL-Objekt aus Codetext |
| get_barcode_type() | Gibt den Barcode-Typ von USA DL zurück (Pdf417) |
| save_to_xml(stream) | Speichert in XML |

### Siehe auch

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

