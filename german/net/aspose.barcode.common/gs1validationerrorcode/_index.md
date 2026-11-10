---
title: "Enum GS1ValidationErrorCode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode-Enum. Identifiziert einen Validierungsfehler einer GS1-Elementzeichenkette, Digital Link URI oder eines Werts."
type: docs
weight: 430
url: /de/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

Identifiziert einen GS1-Element-String, eine Digital‑Link‑URI oder einen Validierungsfehler des Werts.

```csharp
public enum GS1ValidationErrorCode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| EmptyElementString | `0` | Die bereitgestellte GS1-Elementzeichenkette ist leer. |
| MissingOpeningParenthesis | `1` | Eine öffnende Klammer, die einen Anwendungsidentifikator beginnen sollte, fehlt. |
| MissingClosingParenthesis | `2` | Ein Anwendungsidentifikator hat keine schließende Klammer. |
| InvalidApplicationIdentifier | `3` | Ein Anwendungsidentifikator enthält nicht zwei bis vier ASCII-Ziffern. |
| UnknownApplicationIdentifier | `4` | Der bereitgestellte Anwendungsidentifikator ist im unterstützten GS1-Syntaxwörterbuch nicht definiert. |
| MissingValue | `5` | Ein Anwendungsidentifikator ist ohne Wert vorhanden. |
| InvalidEscapeSequence | `6` | Ein Wert enthält eine nicht unterstützte Escape-Sequenz. Nur \( wird unterstützt. |
| ValueTooShort | `7` | Ein Wert ist kürzer als die für seinen Anwendungsidentifikator definierte Mindestlänge. |
| ValueTooLong | `8` | Ein Wert ist länger als die für seinen Anwendungsidentifikator definierte Höchstlänge. |
| InvalidCharacter | `9` | Ein Wert enthält ein Zeichen, das außerhalb des für seine Komponente zulässigen Zeichensatzes liegt. |
| InvalidChecksum | `10` | Eine numerische oder alphabetische Prüfziffer ist ungültig. |
| InvalidDate | `11` | Eine Datums­komponente ist nach den für ihren Anwendungsidentifikator definierten Regeln kein sinnvolles Datum. |
| InvalidTime | `12` | Eine Zeitkomponente liegt außerhalb ihres zulässigen Bereichs oder hat eine ungültige Struktur. |
| InvalidCodeListValue | `13` | Ein Komponentenwert ist nicht in der zulässigen geschlossenen Code-Liste enthalten. |
| InvalidComponentLength | `14` | Eine Komponente erfüllt nicht die komponentenspezifische Längenstruktur. |
| TruncatedComponent | `15` | Eine Komponente fester Länge endet, bevor alle erforderlichen Zeichen vorhanden sind. |
| UnexpectedData | `16` | Daten verbleiben, nachdem alle für den Anwendungsidentifikator definierten Komponenten verarbeitet wurden. |
| InvalidValue | `17` | Eine Komponente verletzt eine Inhaltsregel, für die kein spezifischerer Validierungsfehlercode existiert. |
| GcpPrefixTooShort | `18` | Eine Komponente ist zu kurz, um das minimale vierstellige strukturelle GS1-Unternehmenspräfix zu enthalten. |
| InvalidGcpPrefix | `19` | Der strukturelle GS1 Company Prefix enthält ein Zeichen, das keine ASCII‑Ziffer ist. |
| InvalidDigitalLinkUri | `20` | Der bereitgestellte Wert ist kein wohlgeformter absoluter GS1 Digital Link URI. |
| UnsupportedDigitalLinkScheme | `21` | Ein GS1 Digital Link URI verwendet ein Schema, das nicht HTTP oder HTTPS ist. |
| MissingDigitalLinkPrimaryKey | `22` | Ein GS1 Digital Link URI-Pfad enthält keinen unterstützten Primärschlüssel. |
| InvalidDigitalLinkPath | `23` | Ein GS1 Digital Link URI-Pfad besteht nicht aus gültigen AI‑ und Werte‑Paaren. |
| InvalidDigitalLinkQualifier | `24` | Ein Pfad‑Application Identifier ist an dieser Stelle kein zulässiger Qualifikator. |
| InvalidDigitalLinkQueryParameter | `25` | Ein GS1 Digital Link‑Abfrageparameter ist fehlerhaft. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | Ein Application Identifier ist als GS1 Digital Link‑Datenattribut nicht zulässig. |
| InvalidPercentEncoding | `27` | Eine GS1 Digital Link URI‑Komponente enthält fehlerhafte Prozentkodierung. |
| MultipleDigitalLinkPrimaryKeys | `28` | Mehr als ein Element könnte als GS1 Digital Link‑Primärschlüssel ausgewählt werden. |
| UnsupportedElementCombination | `29` | Die bereitgestellte Kombination von GS1‑Elementen wird von der ausgewählten Symbolik oder dem Kodierungsmodus nicht unterstützt. |

### Siehe auch

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


