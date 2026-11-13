---
title: "GS1Codetext"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

Representerar GS1-kodtext för kodning och avkodning som en ordnad sekvens av<br/>            Application Identifier-element. Källordning och upprepade Application Identifier‑element<br/>            bevaras. Den hakparentes‑representerade formen har formatet (AI)värde(AI)värde.<br/>            En bokstavlig öppningsparentes '(' i ett värde måste skrivas som \(; detta är den<br/>            enda stödda escape‑sekvensen. En avslutande parentes ')' i ett värde kräver inte<br/>            någon escaping.

Typen GS1Codetext visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| GS1Codetext() | Initierar en ny instans av klassen GS1Codetext |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| barcode_type | Hämtar eller anger streckkodstypen som används för att koda denna GS1‑kodtext.<br/>            Stödda typer är GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix,<br/>            GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR och GS1 DataBar‑typer.<br/>            Standardvärdet är GS1Code128. |
| count | Hämtar antalet Application Identifier-element. |
| element | Hämtar en kopia av alla element i källordning. |
## Indexer
| Namn | Beskrivning |
| :- | :- |
| [index] | Hämtar ett element efter dess position i den ordnade sekvensen. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| get_first(application_identifier) | Hämtar det första värdet för en Application Identifier. |
| get_all(application_identifier) | Hämtar alla värden för en Application Identifier i källordning. |
| add(application_identifier, value) | Lägger till ett validerat Application Identifier-element. |
| validate(value) | Validerar en hakparentes‑omsluten GS1‑elementsträng i formatet (AI)värde(AI)värde utan<br/>            att konstruera ett objekt. Ett bokstavligt '(' inuti ett värde måste skrivas som \(; ingen<br/>            annan escape‑sekvens stöds, och ')' kräver ingen escaping. |
| parse(value) | Analyserar en hakparentes‑omsluten GS1‑elementsträng i formatet (AI)värde(AI)värde. Ett bokstavligt<br/>            '(' inuti ett värde måste skrivas som \(; ingen annan escape‑sekvens stöds,<br/>            och ')' kräver ingen escaping. |
| try_parse(value, result, validation_result) | Försöker analysera en hakparentes‑omsluten GS1‑elementsträng i formatet (AI)värde(AI)värde<br/>            och returnerar strukturerade valideringsfel. Ett bokstavligt '(' inuti ett värde måste<br/>            skrivas som \(; ingen annan escape‑sekvens stöds, och ')' kräver inte<br/>            escaping. |
| get_constructed_codetext() | Konstruerar den hakparentes‑omslutna GS1‑kodtexten i formatet (AI)värde(AI)värde.<br/>            Bokstavliga öppningsparenteser i värden escapas som \(. |
| init_from_string(constructed_codetext) | Initierar denna instans från en hakparentes‑omsluten GS1‑kodtext i formatet (AI)värde(AI)värde.<br/>            Befintliga element ersätts först efter att den angivna kodtexten har analyserats framgångsrikt. |
| get_barcode_type() | Hämtar streckkodstypen som används för att koda denna GS1‑kodtext. |

### Se även

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

