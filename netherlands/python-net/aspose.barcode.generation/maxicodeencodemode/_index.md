---
title: "MaxiCodeEncodeMode"
second_title: "Aspose.Sildes voor Python via .NET API‑referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.generation/maxicodeencodemode/
---

## MaxiCodeEncodeMode enumeration

Coderingsmodus voor MaxiCode-streepjescodes.

## Members
| Lidnaam | Beschrijving |
| :- | :- |
| AUTO | In de automatische modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. <br/>            Unicode‑tekens worden opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie.<br/>            Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. |
| EXTENDED |  |
| BINARY | In de binaire modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. <br/>            Als een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid. |
| ECI | In de ECI-modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie.<br/>            Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid.<br/>            Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. |

### Zie ook

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

