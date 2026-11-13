---
title: "DataMatrixEncodeMode"
second_title: "Aspose.Sildes voor Python via .NET API‑referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

Coderingsmodus van de DataMatrix-encoder, standaard Auto

## Members
| Lidnaam | Beschrijving |
| :- | :- |
| AUTO | In de automatische modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. <br/>            Unicode‑tekens worden opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie.<br/>            Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. |
| ASCII | Codeert één alfanumeriek of twee numerieke tekens per byte |
| C40 | Gebruikt C40-codering. Codeert hoofdletter alfanumeriek, kleine letters en speciale tekens |
| TEXT | Gebruikt Text-codering. Codeert alfanumeriek met kleine letters, hoofdletters en speciale tekens |
| EDIFACT | Gebruikt EDIFACT-codering. Gebruikt zes bits per teken, codeert cijfers, hoofdletters en veel leestekens, maar ondersteunt geen kleine letters. |
| ANSIX12 | Gebruikt ANSI X12-codering. |
| EXTENDED |  |
| BASE256 | Codeer 8‑bit waarden |
| BINARY | In de binaire modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. <br/>            Als een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid. |
| ECI | In de ECI-modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie.<br/>            Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid.<br/>            Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. |

### Zie ook

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

