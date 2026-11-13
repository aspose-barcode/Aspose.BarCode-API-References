---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Klass för kodning och avkodning av texten som är inbäddad i Royal Mail 2D Mailmark‑koden.

Typen Mailmark2DCodetext exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| Mailmark2DCodetext() | Initierar en ny instans av klassen Mailmark2DCodetext |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| upu_country_id | Identifierar UPU Country ID. Maxlängd: 4 tecken. |
| information_type_id | Identifierar Royal Mail Mailmark streckkodens nyttolast för varje produkttyp. |
| version_id | Identifierar streckkodsversionen som är relevant för varje Information Type ID. |
| klass | Identifierar objektets klass. |
| supply_chain_id | Identifierar den unika gruppen av kunder som är involverade i utskicket.<br/>            Maxvärde: 9999999. |
| item_id | Identifierar det unika objektet inom Supply Chain ID.<br/>            Varje Mailmark-streckkod måste bära ett ID<br/>            så att det kan identifieras unikt i minst 90 dagar.<br/>            Maxvärde: 99999999. |
| destination_post_code_and_dps | Innehåller postnumret för leveransadressen med DPS<br/>            Om inlandet innehåller postnumret/DP följande antal tecken.<br/>            Område (1 eller 2 tecken) Distrikt (1 eller 2 tecken)<br/>            Sektor (1 tecken) Enhet (2 tecken) DPS (2 tecken).<br/>            Postnumret och DPS måste följa ett giltigt PAF®-format. |
| rts_flag | Flagga som indikerar vilken nivå av Return to Sender-tjänst som begärs. |
| return_to_sender_post_code | Innehåller Return to Sender-postkoden men ingen DPS.<br/>            PC:n (utan DPS) måste följa ett PAF®-format. |
| customer_content | Valfritt utrymme för kundens bruk. |
| customer_content_encode_mode | Kodningsläge för Datamatrix-streckkod.<br/>            Standardvärde: EncodeMode.C40. |
| data_matrix_type | 2D Mailmark-typ definierar storleken på Data Matrix-streckkoden. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| get_constructed_codetext() | Konstruera kodtext från Mailmark-data. |
| init_from_string(constructed_codetext) | Initierar Mailmark-data från konstruerad kodtext. |
| get_barcode_type() | Hämtar streckkodstyp. |

### Se även

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

