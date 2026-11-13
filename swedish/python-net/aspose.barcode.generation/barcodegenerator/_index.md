---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator för generering av streckkodsbilder i backend.

Typen BarcodeGenerator exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| BarcodeGenerator(type) | Initierar en ny instans av klassen BarcodeGenerator |
| BarcodeGenerator(type, code_text) | Initierar en ny instans av klassen BarcodeGenerator |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| parametrar | Genereringsparametrar. |
| barcode_type | Typ av streckkodssymbolik. |
| code_text | Text som ska kodas. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| set_code_text(code_bytes) | Ange kodtext som en sekvens av byte. |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | Spara streckkodsbild till ström i ett specifikt format. |
| save(filename, format) | Spara streckkodsbild till en specifik fil i ett specifikt format. |
| save(filename) | Spara streckkodsbild till en specifik fil i ett specifikt format. |
| export_to_xml(xml_file) | Exporterar BarCode-egenskaper till den angivna xml-filen |
| export_to_xml(xml) | Exporterar BarCode-egenskaper till den angivna xml-strömmen |
| import_from_xml(xml_file) | Importerar BarCode-egenskaper från den angivna xml-filen och skapar en BarcodeGenerator-instans. |
| import_from_xml(xml) | Importerar BarCode-egenskaper från den angivna xml-strömmen och skapar en BarcodeGenerator-instans. |
| generate_bar_code_image() | Generera streckkodsbilden med de aktuella inställningarna. |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

