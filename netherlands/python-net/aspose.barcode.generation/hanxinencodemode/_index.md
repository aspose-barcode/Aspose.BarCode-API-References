---
title: "HanXinEncodeMode"
second_title: "Aspose.Sildes voor Python via .NET API‑referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Han Xin Code coderingsmodus. Het wordt aanbevolen Auto te gebruiken met ASCII-/Chinese tekens of Unicode voor Unicode‑tekens.

## Members
| Lidnaam | Beschrijving |
| :- | :- |
| AUTO | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. <br/>            Unicode‑tekens worden gecodeerd met GB18030‑codering volgens de HanXin-barcode‑specificatie. |
| BINARY | In de binaire modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. <br/>            Als een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid. |
| ECI | In de ECI-modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie.<br/>            Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid.<br/>            Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. |
| UNICODE | Unicode-modus biedt een manier om elke tekstgegevensreferentie weer te geven naar UTF8‑codering/karakterset in Han Xin Code. |
| URI | URI-modus geeft aan dat de gegevens die in Han Xin Code worden weergegeven een Uniform Resource Identifier (URI) zijn<br/>            verwijzing naar RFC 3986. |
| EXTENDED | Extended-modus staat combinaties van interne modi toe: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            Codetext kan handmatig worden opgebouwd met prefixen en dubbele backslashes, bijv.: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" of met de HanXinExtCodetextBuilder.<br/>            Als de codetext een ECI-fragment bevat, mogen daarna alleen de volgende modi in die codetext voorkomen na het ECI-fragment:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### Zie ook

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

