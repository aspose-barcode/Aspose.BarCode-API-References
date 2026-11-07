---
title: "enum"
linktitle: "GS1ValidationErrorCode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " enum. Identificeert een GS1-elementreeks, Digital Link-URI of waardeverificatiefout in C++."
type: docs
weight: 600
url: /nl/cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


Identificeert een GS1-elementreeks, Digital Link-URI of waardeverificatiefout.

```cpp
enum class GS1ValidationErrorCode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| EmptyElementString | 0 | De opgegeven GS1-elementreeks is leeg. |
| MissingOpeningParenthesis | 1 | Een openingshaakje dat een Application Identifier moet beginnen, ontbreekt. |
| MissingClosingParenthesis | 2 | Een Application Identifier heeft geen sluitingshaakje. |
| InvalidApplicationIdentifier | 3 | Een Application Identifier bevat niet twee tot vier ASCII-cijfers. |
| UnknownApplicationIdentifier | 4 | De opgegeven Application Identifier is niet gedefinieerd in het ondersteunde GS1 Syntax Dictionary. |
| MissingValue | 5 | Een Application Identifier is aanwezig zonder een waarde. |
| InvalidEscapeSequence | 6 | Een waarde bevat een niet-ondersteunde escape‑reeks. Alleen ( wordt ondersteund. |
| ValueTooShort | 7 | Een waarde is korter dan de minimale lengte die is gedefinieerd voor zijn Application Identifier. |
| ValueTooLong | 8 | Een waarde is langer dan de maximale lengte die is gedefinieerd voor zijn Application Identifier. |
| InvalidCharacter | 9 | Een waarde bevat een teken dat buiten de toegestane tekenset voor zijn component valt. |
| InvalidChecksum | 10 | Een numerieke of alfanumerieke checksum is ongeldig. |
| InvalidDate | 11 | Een datumcomponent is geen geldige datum volgens de regels die zijn gedefinieerd voor zijn Application Identifier. |
| InvalidTime | 12 | Een tijdcomponent valt buiten het toegestane bereik of heeft een ongeldige structuur. |
| InvalidCodeListValue | 13 | Een componentwaarde is niet aanwezig in de toegestane gesloten codelijst. |
| InvalidComponentLength | 14 | Een component voldoet niet aan zijn component‑specifieke lengtestructuur. |
| TruncatedComponent | 15 | Een vaste‑lengte component eindigt voordat alle vereiste tekens aanwezig zijn. |
| UnexpectedData | 16 | Er blijven gegevens over nadat alle componenten die zijn gedefinieerd voor de Application Identifier zijn verwerkt. |
| InvalidValue | 17 | Een component schendt een inhoudsregel waarvoor geen specifiekere validatiefoutcode bestaat. |
| GcpPrefixTooShort | 18 | Een component is te kort om de minimale viercijferige structurele GS1 Company Prefix te bevatten. |
| InvalidGcpPrefix | 19 | De structurele GS1 Company Prefix bevat een teken dat geen ASCII-cijfer is. |
| InvalidDigitalLinkUri | 20 | De opgegeven waarde is geen goed gevormde absolute GS1 Digital Link URI. |
| UnsupportedDigitalLinkScheme | 21 | Een GS1 Digital Link URI gebruikt een schema anders dan HTTP of HTTPS. |
| MissingDigitalLinkPrimaryKey | 22 | Een GS1 Digital Link URI-pad bevat geen ondersteunde primaire sleutel. |
| InvalidDigitalLinkPath | 23 | Een GS1 Digital Link URI-pad bestaat niet uit geldige AI- en waardepaaren. |
| InvalidDigitalLinkQualifier | 24 | Een pad Application Identifier is op die positie geen toegestane qualifier. |
| InvalidDigitalLinkQueryParameter | 25 | Een GS1 Digital Link query‑parameter is ongeldig. |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | Een Application Identifier is niet toegestaan als een GS1 Digital Link data‑attribuut. |
| InvalidPercentEncoding | 27 | Een GS1 Digital Link URI‑component bevat ongeldige percent‑codering. |
| MultipleDigitalLinkPrimaryKeys | 28 | Er kan meer dan één element worden geselecteerd als de primaire sleutel van de GS1 Digital Link. |
| UnsupportedElementCombination | 29 | De opgegeven combinatie van GS1‑elementen wordt niet ondersteund door de geselecteerde symbologie of coderingsmodus. |

## Zie ook

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
