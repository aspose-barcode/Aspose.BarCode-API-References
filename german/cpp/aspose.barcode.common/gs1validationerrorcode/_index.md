---
title: "enum"
linktitle: "GS1ValidationErrorCode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " enum. Identifiziert einen GS1-Element-String, Digital Link URI oder Validierungsfehler des Werts in C++."
type: docs
weight: 600
url: /de/cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


Identifiziert einen GS1-Element-String, eine Digital-Link-URI oder einen Validierungsfehler des Wertes.

```cpp
enum class GS1ValidationErrorCode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| EmptyElementString | 0 | Der bereitgestellte GS1-Element-String ist leer. |
| MissingOpeningParenthesis | 1 | Eine öffnende Klammer, die einen Anwendungsidentifikator beginnen sollte, fehlt. |
| MissingClosingParenthesis | 2 | Ein Anwendungsidentifikator hat keine schließende Klammer. |
| InvalidApplicationIdentifier | 3 | Ein Anwendungsidentifikator enthält nicht zwei bis vier ASCII-Ziffern. |
| UnknownApplicationIdentifier | 4 | Der bereitgestellte Anwendungsidentifikator ist im unterstützten GS1-Syntax-Wörterbuch nicht definiert. |
| MissingValue | 5 | Ein Anwendungsidentifikator ist ohne Wert vorhanden. |
| InvalidEscapeSequence | 6 | Ein Wert enthält eine nicht unterstützte Escape-Sequenz. Nur ( wird unterstützt. |
| ValueTooShort | 7 | Ein Wert ist kürzer als die für seinen Anwendungsidentifikator definierte Mindestlänge. |
| ValueTooLong | 8 | Ein Wert ist länger als die für seine Anwendungskennung definierte maximale Länge. |
| Ungültiges Zeichen | 9 | Ein Wert enthält ein Zeichen, das nicht im für seine Komponente zulässigen Zeichensatz enthalten ist. |
| Ungültige Prüfsumme | 10 | Eine numerische oder alphabetische Prüfsumme ist ungültig. |
| Ungültiges Datum | 11 | Eine Datums-Komponente ist nach den für die Anwendungskennung definierten Regeln kein sinnvolles Datum. |
| Ungültige Zeit | 12 | Eine Zeitkomponente liegt außerhalb ihres zulässigen Bereichs oder hat eine ungültige Struktur. |
| Ungültiger Codelistenwert | 13 | Ein Komponentenwert ist in der zulässigen geschlossenen Code‑Liste nicht vorhanden. |
| Ungültige Komponentenlänge | 14 | Eine Komponente erfüllt nicht die komponentenspezifische Längenstruktur. |
| Abgeschnittene Komponente | 15 | Eine Komponente fester Länge endet, bevor alle erforderlichen Zeichen vorhanden sind. |
| Unerwartete Daten | 16 | Daten bleiben übrig, nachdem alle für die Anwendungskennung definierten Komponenten verarbeitet wurden. |
| InvalidValue | 17 | Eine Komponente verletzt eine Inhaltsregel, für die kein spezifischerer Validierungsfehlercode vorhanden ist. |
| GcpPrefixTooShort | 18 | Eine Komponente ist zu kurz, um das mindestens vierstellige strukturelle GS1 Company Prefix zu enthalten. |
| InvalidGcpPrefix | 19 | Das strukturelle GS1 Company Prefix enthält ein Zeichen, das keine ASCII-Ziffer ist. |
| InvalidDigitalLinkUri | 20 | Der bereitgestellte Wert ist kein wohlgeformter absoluter GS1 Digital Link URI. |
| UnsupportedDigitalLinkScheme | 21 | Ein GS1 Digital Link URI verwendet ein Schema, das nicht HTTP oder HTTPS ist. |
| MissingDigitalLinkPrimaryKey | 22 | Ein GS1 Digital Link URI-Pfad enthält keinen unterstützten Primärschlüssel. |
| InvalidDigitalLinkPath | 23 | Ein GS1 Digital Link URI-Pfad besteht nicht aus gültigen AI- und Wertpaaren. |
| InvalidDigitalLinkQualifier | 24 | Ein Pfad-Anwendungsidentifikator ist an dieser Stelle kein zulässiger Qualifizierer. |
| InvalidDigitalLinkQueryParameter | 25 | Ein GS1 Digital Link-Abfrageparameter ist fehlerhaft. |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | Ein Anwendungsidentifikator ist als GS1 Digital Link-Datenattribut nicht zulässig. |
| InvalidPercentEncoding | 27 | Ein GS1 Digital Link-URI-Komponente enthält fehlerhafte Prozentkodierung. |
| MultipleDigitalLinkPrimaryKeys | 28 | Mehr als ein Element könnte als primärer Schlüssel des GS1 Digital Link ausgewählt werden. |
| UnsupportedElementCombination | 29 | Die bereitgestellte Kombination von GS1-Elementen wird von der ausgewählten Symbolik oder dem Codierungsmodus nicht unterstützt. |

## Siehe auch

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
