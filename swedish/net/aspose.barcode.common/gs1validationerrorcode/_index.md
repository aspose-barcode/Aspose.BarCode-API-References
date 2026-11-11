---
title: "Enum GS1ValidationErrorCode"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode enum. Identifierar ett GS1-elementsträng Digital Link URI eller värdevalideringsfel"
type: docs
weight: 430
url: /sv/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

Identifierar ett GS1-elementsträng, Digital Link URI eller värdevalideringsfel.

```csharp
public enum GS1ValidationErrorCode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| EmptyElementString | `0` | Den angivna GS1-elementsträngen är tom. |
| MissingOpeningParenthesis | `1` | En öppningsparentes som skulle inleda en Application Identifier saknas. |
| MissingClosingParenthesis | `2` | En Application Identifier har ingen avslutande parentes. |
| InvalidApplicationIdentifier | `3` | En Application Identifier innehåller inte två till fyra ASCII-siffror. |
| UnknownApplicationIdentifier | `4` | Den angivna Application Identifier är inte definierad i det stödjade GS1 Syntax‑lexikonet. |
| MissingValue | `5` | En Application Identifier finns utan ett värde. |
| InvalidEscapeSequence | `6` | Ett värde innehåller en ej stödjande escape‑sekvens. Endast \( stöds. |
| ValueTooShort | `7` | Ett värde är kortare än den minsta längden som definierats för dess Application Identifier. |
| ValueTooLong | `8` | Ett värde är längre än den maximala längden som definierats för dess Application Identifier. |
| InvalidCharacter | `9` | Ett värde innehåller ett tecken som ligger utanför teckenuppsättningen som är tillåten för dess komponent. |
| InvalidChecksum | `10` | En numerisk eller alfabetisk kontrollsumma är ogiltig. |
| InvalidDate | `11` | En datumkomponent är inte ett meningsfullt datum enligt reglerna som definierats för dess Application Identifier. |
| InvalidTime | `12` | En tidskomponent ligger utanför dess tillåtna intervall eller har en ogiltig struktur. |
| InvalidCodeListValue | `13` | Ett komponentvärde finns inte i dess tillåtna slutna kodlista. |
| InvalidComponentLength | `14` | En komponent uppfyller inte dess komponent‑specifika längdstruktur. |
| TruncatedComponent | `15` | En fastlängds‑komponent avslutas innan alla obligatoriska tecken är närvarande. |
| UnexpectedData | `16` | Data återstår efter att alla komponenter som definierats för Application Identifier har konsumerats. |
| InvalidValue | `17` | En komponent bryter mot en innehållsregel som inte har någon mer specifik valideringsfelkod. |
| GcpPrefixTooShort | `18` | En komponent är för kort för att innehålla det minsta fyrsiffriga strukturella GS1 Company Prefix. |
| InvalidGcpPrefix | `19` | Den strukturella GS1 Company Prefix innehåller ett tecken som inte är en ASCII-siffra. |
| InvalidDigitalLinkUri | `20` | Det angivna värdet är inte en välformad absolut GS1 Digital Link-URI. |
| UnsupportedDigitalLinkScheme | `21` | En GS1 Digital Link-URI använder ett schema som inte är HTTP eller HTTPS. |
| MissingDigitalLinkPrimaryKey | `22` | En GS1 Digital Link-URI-sökväg innehåller inte en stödjande primärnyckel. |
| InvalidDigitalLinkPath | `23` | En GS1 Digital Link-URI-sökväg består inte av giltiga AI- och värdepar. |
| InvalidDigitalLinkQualifier | `24` | En sökvägs Application Identifier är inte en tillåten kvalificerare på den positionen. |
| InvalidDigitalLinkQueryParameter | `25` | En GS1 Digital Link-frågeparameter är felaktigt formaterad. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | En Application Identifier är inte tillåten som ett GS1 Digital Link-dataattribut. |
| InvalidPercentEncoding | `27` | En GS1 Digital Link-URI-komponent innehåller felaktig procentkodning. |
| MultipleDigitalLinkPrimaryKeys | `28` | Mer än ett element kan väljas som GS1 Digital Link primärnyckel. |
| UnsupportedElementCombination | `29` | Den angivna kombinationen av GS1-element stöds inte av den valda symboliken eller kodningsläget. |

### Se även

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


