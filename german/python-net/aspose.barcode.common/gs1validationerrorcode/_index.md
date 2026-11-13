---
title: "GS1ValidationErrorCode"
second_title: "Aspose.Sildes für Python über .NET API‑Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Identifiziert einen GS1-Element-String, Digital Link URI oder einen Validierungsfehler des Wertes.

## Members
| Member‑Name | Beschreibung |
| :- | :- |
| EMPTY_ELEMENT_STRING | Der bereitgestellte GS1-Element-String ist leer. |
| MISSING_OPENING_PARENTHESIS | Eine öffnende Klammer, die einen Application Identifier beginnen sollte, fehlt. |
| MISSING_CLOSING_PARENTHESIS | Ein Application Identifier hat keine schließende Klammer. |
| INVALID_APPLICATION_IDENTIFIER | Ein Application Identifier enthält nicht zwei bis vier ASCII-Ziffern. |
| UNKNOWN_APPLICATION_IDENTIFIER | Der bereitgestellte Application Identifier ist im unterstützten GS1 Syntax Dictionary nicht definiert. |
| MISSING_VALUE | Ein Application Identifier ist ohne Wert vorhanden. |
| INVALID_ESCAPE_SEQUENCE | Ein Wert enthält eine nicht unterstützte Escape-Sequenz. Nur \( wird unterstützt. |
| VALUE_TOO_SHORT | Ein Wert ist kürzer als die für seinen Application Identifier definierte Mindestlänge. |
| VALUE_TOO_LONG | Ein Wert ist länger als die für seinen Application Identifier definierte maximale Länge. |
| INVALID_CHARACTER | Ein Wert enthält ein Zeichen, das außerhalb des für seine Komponente zulässigen Zeichensatzes liegt. |
| INVALID_CHECKSUM | Eine numerische oder alphabetische Prüfsumme ist ungültig. |
| INVALID_DATE | Eine Datums-Komponente ist nach den für ihren Application Identifier definierten Regeln kein sinnvolles Datum. |
| INVALID_TIME | Eine Zeitkomponente liegt außerhalb ihres zulässigen Bereichs oder hat eine ungültige Struktur. |
| INVALID_CODE_LIST_VALUE | Ein Komponentenwert ist in seiner zulässigen geschlossenen Code-Liste nicht vorhanden. |
| INVALID_COMPONENT_LENGTH | Eine Komponente erfüllt nicht ihre komponentenspezifische Längenstruktur. |
| TRUNCATED_COMPONENT | Eine Festlängenkomponente endet, bevor alle erforderlichen Zeichen vorhanden sind. |
| UNEXPECTED_DATA | Daten bleiben übrig, nachdem alle für den Anwendungsidentifikator definierten Komponenten verarbeitet wurden. |
| INVALID_VALUE | Eine Komponente verletzt eine Inhaltsregel, für die kein spezifischerer Validierungsfehlercode vorhanden ist. |
| GCP_PREFIX_TOO_SHORT | Eine Komponente ist zu kurz, um das minimale vierstellige strukturelle GS1 Company Prefix zu enthalten. |
| INVALID_GCP_PREFIX | Das strukturelle GS1 Company Prefix enthält ein Zeichen, das keine ASCII-Ziffer ist. |
| INVALID_DIGITAL_LINK_URI | Der bereitgestellte Wert ist kein wohlgeformter absoluter GS1 Digital Link URI. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | Ein GS1 Digital Link URI verwendet ein Schema, das nicht HTTP oder HTTPS ist. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | Ein GS1 Digital Link URI-Pfad enthält keinen unterstützten Primärschlüssel. |
| INVALID_DIGITAL_LINK_PATH | Ein GS1 Digital Link URI-Pfad besteht nicht aus gültigen AI- und Wertpaaren. |
| INVALID_DIGITAL_LINK_QUALIFIER | Ein Pfad-Anwendungsidentifikator ist an dieser Position kein zulässiger Qualifizierer. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | Ein GS1 Digital Link-Abfrageparameter ist fehlerhaft. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | Ein Application Identifier ist als GS1 Digital Link-Datenattribut nicht zulässig. |
| INVALID_PERCENT_ENCODING | Ein GS1 Digital Link-URI‑Komponente enthält fehlerhafte Prozentkodierung. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | Mehr als ein Element könnte als GS1 Digital Link‑Primärschlüssel ausgewählt werden. |
| UNSUPPORTED_ELEMENT_COMBINATION | Die bereitgestellte Kombination von GS1‑Elementen wird von der ausgewählten Symbolik oder dem Codierungsmodus nicht unterstützt. |

### Siehe auch

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

