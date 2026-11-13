---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator zur Erzeugung von Barcode‑Bildern im Backend.

Der Typ BarcodeGenerator stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| BarcodeGenerator(type) | Initialisiert eine neue Instanz der Klasse BarcodeGenerator |
| BarcodeGenerator(type, code_text) | Initialisiert eine neue Instanz der Klasse BarcodeGenerator |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Parameter | Generierungsparameter. |
| barcode_type | Barcode-Symbologie-Typ. |
| code_text | Zu kodierender Text. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| set_code_text(code_bytes) | Setzt den Codetext als Byte-Sequenz. |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | Speichert das Barcode-Bild in einen Stream in einem bestimmten Format. |
| save(filename, format) | Speichert das Barcode-Bild in eine bestimmte Datei in einem bestimmten Format. |
| save(filename) | Speichert das Barcode-Bild in eine bestimmte Datei in einem bestimmten Format. |
| export_to_xml(xml_file) | Exportiert BarCode-Eigenschaften in die angegebene XML-Datei |
| export_to_xml(xml) | Exportiert BarCode-Eigenschaften in den angegebenen XML-Stream |
| import_from_xml(xml_file) | Importiert BarCode-Eigenschaften aus der angegebenen XML-Datei und erstellt eine BarcodeGenerator-Instanz. |
| import_from_xml(xml) | Importiert BarCode-Eigenschaften aus dem angegebenen XML-Stream und erstellt eine BarcodeGenerator-Instanz. |
| generate_bar_code_image() | Erzeugt das Barcode-Bild mit den aktuellen Einstellungen. |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

