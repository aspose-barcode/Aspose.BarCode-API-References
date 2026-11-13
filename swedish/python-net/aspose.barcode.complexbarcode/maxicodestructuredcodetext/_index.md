---
title: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Bas‑klass för kodning och avkodning av texten som är inbäddad i MaxiCode‑koden för lägena 2 och 3.

Typen MaxiCodeStructuredCodetext exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| encode_mode | Hämtar eller anger ett MaxiCode-kodningsläge. <br/>            Standardvärde: Auto. |
| eci_encoding | Hämtar eller anger ECI-kodning. Används när MaxiCodeEncodeMode är Auto.<br/>            Standardvärde: ISO-8859-1 |
| postal_code | Identifierar postnumret. Måste vara 9 siffror i läge 2 eller <br/>            6 alfanumeriska tecken i läge 3. |
| country_code | Identifierar 3‑siffrig landskod. |
| service_category | Identifierar 3-siffrig servicekategori. |
| second_message | Identifierar det andra meddelandet i streckkoden. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| get_mode() | Hämtar MaxiCode-läge. |
| get_constructed_codetext() | Skapar kodtext |
| init_from_string(constructed_codetext) | Initierar instans från konstruerad kodtext. |
| get_barcode_type() | Hämtar streckkodstyp. |

### Se även

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

