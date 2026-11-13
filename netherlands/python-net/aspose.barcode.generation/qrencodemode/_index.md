---
title: "QREncodeMode"
second_title: "Aspose.Sildes voor Python via .NET API‑referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

Coderingsmodus voor QR-streepjescodes.

## Members
| Lidnaam | Beschrijving |
| :- | :- |
| AUTO | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. <br/>            Unicode‑tekens worden, indien mogelijk, gecodeerd in kanji-modus, of ze worden opnieuw gecodeerd met de opgegeven ECIEncoding‑codering door invoeging van een ECI‑identificatie. <br/>            Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. |
| EXTENDED |  |
| BINARY | In de binaire modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. <br/>            Als een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid. |
| ECI | In de ECI-modus wordt het volledige bericht opnieuw gecodeerd met de opgegeven ECIEncoding‑codering door invoeging van een ECI‑identificatie. <br/>            Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. <br/>            Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. <br/>            Deze modus wordt niet ondersteund door MicroQR‑barcodes. |

### Zie ook

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

