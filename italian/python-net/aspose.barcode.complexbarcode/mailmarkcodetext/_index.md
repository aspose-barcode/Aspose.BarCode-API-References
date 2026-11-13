---
title: "MailmarkCodetext"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mailmark a 4 stati.

Il tipo MailmarkCodetext espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| MailmarkCodetext() | Inizializza una nuova istanza della classe MailmarkCodetext |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| format | \"0\" – Nullo o Test<br/>            \"1\" – Lettera<br/>            \"2\" – Lettera Grande |
| version_id | Attualmente \"1\" – Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro) |
| klass | \"0\" - Nullo o Test<br/>            \"1\" - 1C (Vendita al dettaglio)<br/>            \"2\" - 2C (Vendita al dettaglio)<br/>            \"3\" - 3C (Vendita al dettaglio)<br/>            \"4\" - Premium (Mail di RetailPublishing) (per uso futuro potenziale)<br/>            \"5\" - Deferred (Vendita al dettaglio)<br/>            \"6\" - Air (Vendita al dettaglio) (per uso futuro potenziale)<br/>            \"7\" - Surface (Vendita al dettaglio) (per uso futuro potenziale)<br/>            \"8\" - Premium (Accesso di rete)<br/>            \"9\" - Standard (Accesso di rete) |
| supply_chain_id | I valori massimi sono 99 per il Barcode C e 999999 per il Barcode L. |
| item_id | Il valore massimo è 99999999. |
| destination_post_code_and_dps | Il PC e il DP devono conformarsi a un formato PAF.<br/>            Stringa di nove caratteri che indica l'internazionale \"XY11     \" (nota i 5 spazi finali) o un modello<br/>            di caratteri che indica un codice di smistamento domestico.<br/>            Un codice di smistamento domestico è composto da un codice postale esterno, un codice postale interno e un suffisso del punto di consegna. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| get_constructed_codetext() | Costruisci il codetext dai dati Mailmark. |
| init_from_string(constructed_codetext) | Inizializza i dati Mailmark dal codetext costruito. |
| get_barcode_type() | Ottiene il tipo di codice a barre. |

### Vedi anche

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

