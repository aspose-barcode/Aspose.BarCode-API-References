---
title: "GS1ValidationErrorCode"
second_title: "Aspose.Sildes för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Identifierar en GS1-elementsträng, Digital Link-URI eller ett värdevalideringsfel.

## Members
| Medlemsnamn | Beskrivning |
| :- | :- |
| EMPTY_ELEMENT_STRING | Den angivna GS1-elementsträngen är tom. |
| MISSING_OPENING_PARENTHESIS | En öppningsparentes som ska inleda en Application Identifier saknas. |
| MISSING_CLOSING_PARENTHESIS | En Application Identifier har ingen avslutande parentes. |
| INVALID_APPLICATION_IDENTIFIER | En Application Identifier innehåller inte två till fyra ASCII-siffror. |
| UNKNOWN_APPLICATION_IDENTIFIER | Den angivna Application Identifier är inte definierad av den stödjade GS1 Syntax Dictionary. |
| MISSING_VALUE | En Application Identifier finns utan ett värde. |
| INVALID_ESCAPE_SEQUENCE | Ett värde innehåller en ej stödd escape-sekvens. Endast \( stöds. |
| VALUE_TOO_SHORT | Ett värde är kortare än den minsta längden som definierats för dess Application Identifier. |
| VALUE_TOO_LONG | Ett värde är längre än den maximala längden som definierats för dess Application Identifier. |
| INVALID_CHARACTER | Ett värde innehåller ett tecken som ligger utanför den teckenuppsättning som är tillåten för dess komponent. |
| INVALID_CHECKSUM | En numerisk eller alfabetisk kontrollsumma är ogiltig. |
| INVALID_DATE | En datumkomponent är inte ett meningsfullt datum enligt reglerna som definierats för dess Application Identifier. |
| INVALID_TIME | En tidskomponent är utanför sitt tillåtna intervall eller har en ogiltig struktur. |
| INVALID_CODE_LIST_VALUE | Ett komponentvärde finns inte i dess tillåtna slutna kodlista. |
| INVALID_COMPONENT_LENGTH | En komponent uppfyller inte dess komponentspecifika längdstruktur. |
| TRUNCATED_COMPONENT | En komponent med fast längd avslutas innan alla obligatoriska tecken är närvarande. |
| UNEXPECTED_DATA | Data återstår efter att alla komponenter som definierats för applikationsidentifieraren har konsumerats. |
| INVALID_VALUE | En komponent bryter mot en innehållsregel som saknar en mer specifik valideringsfelkod. |
| GCP_PREFIX_TOO_SHORT | En komponent är för kort för att innehålla det minsta fyrsiffriga strukturella GS1-företagsprefixet. |
| INVALID_GCP_PREFIX | Det strukturella GS1-företagsprefixet innehåller ett tecken som inte är en ASCII-siffra. |
| INVALID_DIGITAL_LINK_URI | Det angivna värdet är inte en välformad absolut GS1 Digital Link-URI. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | En GS1 Digital Link-URI använder ett schema annat än HTTP eller HTTPS. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | En GS1 Digital Link-URI-sökväg innehåller inte en stödjande primärnyckel. |
| INVALID_DIGITAL_LINK_PATH | En GS1 Digital Link-URI-sökväg består inte av giltiga AI- och värdepar. |
| INVALID_DIGITAL_LINK_QUALIFIER | En sökvägsapplikationsidentifierare är inte en tillåten kvalificerare på den positionen. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | En GS1 Digital Link-frågeparameter är felaktig. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | En Application Identifier är inte tillåten som ett dataattribut i GS1 Digital Link. |
| INVALID_PERCENT_ENCODING | En komponent i en GS1 Digital Link URI innehåller felaktig procentkodning. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | Mer än ett element kan väljas som den primära nyckeln i GS1 Digital Link. |
| UNSUPPORTED_ELEMENT_COMBINATION | Den angivna kombinationen av GS1-element stöds inte av den valda symbolen eller kodningsläget. |

### Se även

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

