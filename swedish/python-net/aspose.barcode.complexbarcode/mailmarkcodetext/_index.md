---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

Klass för kodning och avkodning av texten som är inbäddad i 4‑states Royal Mailmark‑koden.

Typen MailmarkCodetext exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| MailmarkCodetext() | Initierar en ny instans av klassen MailmarkCodetext |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| format | "0" – Null eller Test<br/>            "1" – Brev<br/>            "2" – Stort brev |
| version_id | För närvarande "1" – För Mailmark streckkod (0 och 2 till 9 samt A till Z reserverade för framtida bruk) |
| klass | "0" - Null eller Test<br/>            "1" - 1C (Detaljhandel)<br/>            "2" - 2C (Detaljhandel)<br/>            "3" - 3C (Detaljhandel)<br/>            "4" - Premium (RetailPublishing Mail) (för potentiellt framtida bruk)<br/>            "5" - Uppskjuten (Detaljhandel)<br/>            "6" - Air (Detaljhandel) (för potentiellt framtida bruk)<br/>            "7" - Surface (Detaljhandel) (för potentiellt framtida bruk)<br/>            "8" - Premium (Nätverksåtkomst)<br/>            "9" - Standard (Nätverks åtkomst) |
| supply_chain_id | Maximala värden är 99 för Streckkod C och 999999 för Streckkod L. |
| item_id | Maximalt värde är 99999999. |
| destination_post_code_and_dps | PC och DP måste följa ett PAF-format.<br/>            Nio tecken lång sträng som anger internationell "XY11     " (observera de 5 efterföljande mellanslagen) eller ett mönster<br/>            av tecken som anger en inhemsk sorteringskod.<br/>            En inhemsk sorteringskod består av ett utåtriktat postnummer, ett inåtriktat postnummer och ett leveranspunktsuffix. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| get_constructed_codetext() | Konstruera kodtext från Mailmark-data. |
| init_from_string(constructed_codetext) | Initierar Mailmark-data från konstruerad kodtext. |
| get_barcode_type() | Hämtar streckkodstyp. |

### Se även

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

