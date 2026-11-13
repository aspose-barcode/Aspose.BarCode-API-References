---
title: "GS1Codetext"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

Stelt GS1-codetekst voor voor coderen en decoderen als een geordende reeks van<br/>            Application Identifier‑elementen. De bronvolgorde en herhaalde Application Identifiers<br/>            worden behouden. De haakjesweergave heeft de vorm (AI)waarde(AI)waarde.<br/>            Een letterlijke openingshaak '(' binnen een waarde moet worden geschreven als \(; dit is de<br/>            enige ondersteunde escape‑sequentie. Een sluitingshaak ')' binnen een waarde hoeft<br/>            niet te worden geescaped.

Het type GS1Codetext exposeert de volgende leden:
## Constructors
| Name | Beschrijving |
| :- | :- |
| GS1Codetext() | Initialiseert een nieuw exemplaar van de klasse GS1Codetext |
## Properties
| Name | Beschrijving |
| :- | :- |
| barcode_type | Haalt het barcode-type op of stelt het in dat wordt gebruikt om deze GS1-codetekst te coderen.<br/>            Ondersteunde types zijn GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix,<br/>            GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR en GS1 DataBar types.<br/>            De standaardwaarde is GS1Code128. |
| aantal | Haalt het aantal Application Identifier-elementen op. |
| elementen | Haalt een kopie op van alle elementen in bronvolgorde. |
## Indexer
| Name | Beschrijving |
| :- | :- |
| [index] | Haalt een element op op basis van zijn positie in de geordende reeks. |
## Methods
| Name | Beschrijving |
| :- | :- |
| get_first(application_identifier) | Haalt de eerste waarde op voor een Application Identifier. |
| get_all(application_identifier) | Haalt alle waarden op voor een Application Identifier in bronvolgorde. |
| add(application_identifier, value) | Voegt een gevalideerd Application Identifier-element toe. |
| validate(value) | Valideert een tussen haakjes geplaatste GS1-elementreeks in de vorm (AI)waarde(AI)waarde zonder<br/>            een object te construeren. Een letterlijke '(' binnen een waarde moet worden geschreven als \(; geen<br/>            andere escape‑reeks wordt ondersteund, en ')' hoeft niet te worden geescaped. |
| parse(value) | Parseert een tussen haakjes geplaatste GS1-elementreeks in de vorm (AI)waarde(AI)waarde. Een letterlijke<br/>            '(' binnen een waarde moet worden geschreven als \(; geen andere escape‑reeks wordt ondersteund,<br/>            en ')' hoeft niet te worden geescaped. |
| try_parse(value, result, validation_result) | Probeert een tussen haakjes geplaatste GS1-elementreeks in de vorm (AI)waarde(AI)waarde<br/>            te parseren en retourneert gestructureerde validatiefouten. Een letterlijke '(' binnen een waarde moet<br/>            worden geschreven als \(; geen andere escape‑reeks wordt ondersteund, en ')' hoeft niet te worden<br/>            geescaped. |
| get_constructed_codetext() | Construeert de tussen haakjes geplaatste GS1-codetekst in de vorm (AI)waarde(AI)waarde.<br/>            Letterlijke openingshaakjes in waarden worden geescaped als \(. |
| init_from_string(constructed_codetext) | Initialiseert dit exemplaar vanuit een tussen haakjes geplaatste GS1-codetekst in de vorm (AI)waarde(AI)waarde.<br/>            Bestaande elementen worden alleen vervangen nadat de opgegeven codetekst succesvol is geparseerd. |
| get_barcode_type() | Haalt het barcode-type op dat wordt gebruikt om deze GS1-codetekst te coderen. |

### Zie ook

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

