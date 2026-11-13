---
title: "GS1DigitalLink"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

Representerar GS1 Digital Link-kodtext för kodning och avkodning som en ordnad sekvens av<br/>            Application Identifier-element. Källordning och upprepade Application Identifier‑element bevaras.<br/>            Den konstruerade kodtexten är en okomprimerad GS1 Digital Link-URI.<br/>            Icke‑GS1‑frågeparametrar och URI‑fragment ignoreras vid parsning.

Typen GS1DigitalLink exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| GS1DigitalLink(uri_stem) | Initierar en ny instans av klassen GS1DigitalLink |
| GS1DigitalLink(uri_stem, primary_application_identifier) | Initierar en ny instans av klassen GS1DigitalLink |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| uri_stem | Hämtar den absoluta URI-prefixen före GS1:s primära nyckelvägssegment.<br/>            Stammen innehåller ingen frågesträng eller fragment. |
| primary_application_identifier | Hämtar den applikationsidentifierare som används som Digital Link:s primära nyckel.<br/>            Null betyder att den primära nyckeln väljs automatiskt när URI:n konstrueras. |
| barcode_type | Hämtar eller anger streckkodstypen som används för att koda denna GS1 Digital Link.<br/>            Stödda typer är QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF och Code128.<br/>            Standardvärdet är QR. |
| count | Hämtar antalet Application Identifier-element. |
| element | Hämtar en kopia av alla element i källordning. |
## Indexer
| Namn | Beskrivning |
| :- | :- |
| [index] | Hämtar ett element efter dess position i den ordnade sekvensen. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| create(uri_stem, codetext) | Skapar en GS1 Digital Link genom att kopiera alla element från GS1 codetext och välja<br/>            den enda tillgängliga primära nyckeln. |
| create(uri_stem, codetext, primary_application_identifier) | Skapar en GS1 Digital Link genom att kopiera alla element från GS1 codetext och välja<br/>            den enda tillgängliga primära nyckeln. |
| get_first(application_identifier) | Hämtar det första värdet för en Application Identifier. |
| get_all(application_identifier) | Hämtar alla värden för en Application Identifier i källordning. |
| add(application_identifier, value) | Lägger till ett validerat Application Identifier-element. |
| validate(value) | Validerar en okomprimerad GS1 Digital Link-URI utan att konstruera ett objekt. |
| parse(value) | Analyserar en okomprimerad GS1 Digital Link-URI. |
| try_parse(value, result, validation_result) | Försöker analysera en okomprimerad GS1 Digital Link-URI och returnerar strukturerade valideringsfel. |
| to_gs1_codetext() | Skapar en oberoende GS1 codetext som innehåller de aktuella GS1-elementen.<br/>            Information som endast gäller URI inkluderas inte. |
| to_uri_string() | Formaterar det aktuella objektets tillstånd som en okomprimerad GS1 Digital Link-URI. |
| get_constructed_codetext() | Konstruerar den okomprimerade GS1 Digital Link-URI:n. |
| init_from_string(constructed_codetext) | Initierar den här instansen från en okomprimerad GS1 Digital Link-URI.<br/>            Befintligt tillstånd ersätts först efter att den angivna URI:n har analyserats framgångsrikt.<br/>            Den valda streckkodstypen bevaras. |
| get_barcode_type() | Hämtar streckkodstypen som används för att koda denna GS1 Digital Link. |

### Se även

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

