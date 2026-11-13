---
title: "GS1DigitalLink"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

Stelt GS1 Digital Link-codetekst voor voor coderen en decoderen als een geordende reeks van<br/>            Application Identifier‑elementen. De bronvolgorde en herhaalde Application Identifiers worden behouden.<br/>            De geconstrueerde codetekst is een ongecomprimeerde GS1 Digital Link‑URI.<br/>            Niet‑GS1 query‑parameters en URI‑fragmenten worden genegeerd bij het parseren.

Het GS1DigitalLink-type exposeert de volgende leden:
## Constructors
| Name | Beschrijving |
| :- | :- |
| GS1DigitalLink(uri_stem) | Initialiseert een nieuw exemplaar van de GS1DigitalLink-klasse |
| GS1DigitalLink(uri_stem, primary_application_identifier) | Initialiseert een nieuw exemplaar van de GS1DigitalLink-klasse |
## Properties
| Name | Beschrijving |
| :- | :- |
| uri_stem | Haalt het absolute URI-voorvoegsel op vóór het GS1 primaire sleutelpadsegment.<br/>            De stam bevat geen querystring of fragment. |
| primary_application_identifier | Haalt de Application Identifier op die wordt gebruikt als de primaire sleutel van de Digital Link.<br/>            Null betekent dat de primaire sleutel automatisch wordt geselecteerd wanneer de URI wordt geconstrueerd. |
| barcode_type | Haalt het type barcode op of stelt het in dat wordt gebruikt om deze GS1 Digital Link te coderen.<br/>            Ondersteunde types zijn QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF en Code128.<br/>            De standaardwaarde is QR. |
| aantal | Haalt het aantal Application Identifier-elementen op. |
| elementen | Haalt een kopie op van alle elementen in bronvolgorde. |
## Indexer
| Name | Beschrijving |
| :- | :- |
| [index] | Haalt een element op op basis van zijn positie in de geordende reeks. |
## Methods
| Name | Beschrijving |
| :- | :- |
| create(uri_stem, codetext) | Maakt een GS1 Digital Link aan door alle elementen van de GS1-codetekst te kopiëren en de enige beschikbare primaire sleutel te selecteren<br/>            . |
| create(uri_stem, codetext, primary_application_identifier) | Maakt een GS1 Digital Link aan door alle elementen van de GS1-codetekst te kopiëren en de enige beschikbare primaire sleutel te selecteren<br/>            . |
| get_first(application_identifier) | Haalt de eerste waarde op voor een Application Identifier. |
| get_all(application_identifier) | Haalt alle waarden op voor een Application Identifier in bronvolgorde. |
| add(application_identifier, value) | Voegt een gevalideerd Application Identifier-element toe. |
| validate(value) | Valideert een ongecomprimeerde GS1 Digital Link-URI zonder een object te construeren. |
| parse(value) | Parseert een ongecomprimeerde GS1 Digital Link-URI. |
| try_parse(value, result, validation_result) | Probeert een ongecomprimeerde GS1 Digital Link-URI te parseren en retourneert gestructureerde validatiefouten. |
| to_gs1_codetext() | Maakt een onafhankelijk GS1-codetekst aan dat de huidige GS1-elementen bevat.<br/>            URI-only informatie wordt niet opgenomen. |
| to_uri_string() | Formatteert de huidige objectstatus als een ongecomprimeerde GS1 Digital Link-URI. |
| get_constructed_codetext() | Construeert de ongecomprimeerde GS1 Digital Link-URI. |
| init_from_string(constructed_codetext) | Initialiseert deze instantie vanuit een ongecomprimeerde GS1 Digital Link-URI.<br/>            Bestaande status wordt alleen vervangen nadat de opgegeven URI succesvol is geparseerd.<br/>            Het geselecteerde barcode-type wordt behouden. |
| get_barcode_type() | Haalt het barcode-type op dat wordt gebruikt om deze GS1 Digital Link te coderen. |

### Zie ook

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

