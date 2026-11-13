---
title: "GS1ValidationErrorCode"
second_title: "Aspose.Sildes voor Python via .NET API‑referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Identificeert een GS1-elementreeks, Digital Link-URI of waardeverificatiefout.

## Members
| Lidnaam | Beschrijving |
| :- | :- |
| EMPTY_ELEMENT_STRING | De opgegeven GS1-elementreeks is leeg. |
| MISSING_OPENING_PARENTHESIS | Een openingshaakje dat een Application Identifier moet beginnen, ontbreekt. |
| MISSING_CLOSING_PARENTHESIS | Een Application Identifier heeft geen sluitend haakje. |
| INVALID_APPLICATION_IDENTIFIER | Een Application Identifier bevat niet twee tot vier ASCII-cijfers. |
| UNKNOWN_APPLICATION_IDENTIFIER | De opgegeven Application Identifier is niet gedefinieerd in het ondersteunde GS1 Syntax Dictionary. |
| MISSING_VALUE | Een Application Identifier is aanwezig zonder een waarde. |
| INVALID_ESCAPE_SEQUENCE | Een waarde bevat een niet-ondersteunde escape‑reeks. Alleen \\( is ondersteund. |
| VALUE_TOO_SHORT | Een waarde is korter dan de minimale lengte die is gedefinieerd voor zijn Application Identifier. |
| VALUE_TOO_LONG | Een waarde is langer dan de maximale lengte die is gedefinieerd voor zijn Application Identifier. |
| INVALID_CHARACTER | Een waarde bevat een teken buiten de tekenset die is toegestaan voor zijn component. |
| INVALID_CHECKSUM | Een numerieke of alfabetische checksum is ongeldig. |
| INVALID_DATE | Een datumcomponent is geen geldige datum volgens de regels die zijn gedefinieerd voor zijn Application Identifier. |
| INVALID_TIME | Een tijdcomponent valt buiten het toegestane bereik of heeft een ongeldige structuur. |
| INVALID_CODE_LIST_VALUE | Een componentwaarde is niet aanwezig in de toegestane gesloten codelijst. |
| INVALID_COMPONENT_LENGTH | Een component voldoet niet aan zijn component‑specifieke lengtestructuur. |
| TRUNCATED_COMPONENT | Een component met vaste lengte eindigt voordat alle vereiste tekens aanwezig zijn. |
| UNEXPECTED_DATA | Er blijven gegevens over nadat alle componenten die voor de Application Identifier zijn gedefinieerd, zijn verwerkt. |
| INVALID_VALUE | Een component schendt een inhoudsregel waarvoor geen specifiekere validatiefoutcode bestaat. |
| GCP_PREFIX_TOO_SHORT | Een component is te kort om het minimale viercijferige structurele GS1 Company Prefix te bevatten. |
| INVALID_GCP_PREFIX | Het structurele GS1 Company Prefix bevat een teken dat geen ASCII‑cijfer is. |
| INVALID_DIGITAL_LINK_URI | De opgegeven waarde is geen goed gevormde absolute GS1 Digital Link URI. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | Een GS1 Digital Link URI gebruikt een schema anders dan HTTP of HTTPS. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | Een GS1 Digital Link URI-pad bevat geen ondersteunde primaire sleutel. |
| INVALID_DIGITAL_LINK_PATH | Een GS1 Digital Link URI-pad bestaat niet uit geldige AI‑ en waardepaaren. |
| INVALID_DIGITAL_LINK_QUALIFIER | Een pad‑Application Identifier is geen toegestane qualifier op die positie. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | Een GS1 Digital Link query‑parameter is onjuist geformatteerd. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | Een Application Identifier is niet toegestaan als een GS1 Digital Link data‑attribuut. |
| INVALID_PERCENT_ENCODING | Een GS1 Digital Link URI‑component bevat onjuiste percent‑codering. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | Er kan meer dan één element worden geselecteerd als de primaire sleutel van de GS1 Digital Link. |
| UNSUPPORTED_ELEMENT_COMBINATION | De opgegeven combinatie van GS1‑elementen wordt niet ondersteund door de geselecteerde symbologie of coderingsmodus. |

### Zie ook

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

