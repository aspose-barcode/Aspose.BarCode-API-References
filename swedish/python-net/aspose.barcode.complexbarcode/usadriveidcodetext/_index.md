---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

Klass för kodning och avkodning av texten som är inbäddad i USA Driving License PDF417‑koden.

Typen USADriveIdCodetext exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| USADriveIdCodetext() | Initierar en ny instans av klassen USADriveIdCodetext |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| issuer_identification_number | Detta nummer identifierar unikt <br/>            den utfärdande jurisdiktionen och kan erhållas genom att kontakta ISO<br/>            Utfärdarmyndigheten (AAMVA).  Det fullständiga 6-siffriga IIN bör kodas. |
| aamva_version_number | AAMVA versionsnummer 00-99 |
| jurisdiction_version_number | Jurisdiktionens versionsnummer 00-99 |
| number_of_entries | Antal 00-99 av underfiler |
| subfile_designator | Innehåller information om följande underfiler, typer, offset och längder. <br/>            Viktigt: endast typ, offset och längd kommer att ställas in automatiskt. |
| mandatory_elements | Obligatoriska element (fält) på kortet |
| optional_elements | Valfria element (fält) på kortet |
| jurisdiction_specific_subfile | Jurisdiktionens specifika fält |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| get_constructed_codetext() | Konstruera kodtext från USA DL-data |
| init_from_string(constructed_codetext) | Initiera USA DL-objekt från kodtext |
| get_barcode_type() | Returnerar streckkodstyp för USA DL (Pdf417) |
| save_to_xml(stream) | Sparar till XML |

### Se även

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

