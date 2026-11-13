---
title: "Mailmark2DCodetext"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mail 2D Mailmark.

Il tipo Mailmark2DCodetext espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Mailmark2DCodetext() | Inizializza una nuova istanza della classe Mailmark2DCodetext |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| upu_country_id | Identifica l'ID Paese UPU. Lunghezza massima: 4 caratteri. |
| information_type_id | Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. |
| version_id | Identifica la versione del codice a barre in base a ciascun ID Tipo di Informazione. |
| klass | Identifica la classe dell'elemento. |
| supply_chain_id | Identifica il gruppo unico di clienti coinvolti nella spedizione.<br/>            Valore massimo: 9999999. |
| item_id | Identifica l'elemento unico all'interno dell'ID della catena di fornitura.<br/>            Ogni codice a barre Mailmark deve contenere un ID<br/>            in modo da poter essere identificato univocamente per almeno 90 giorni.<br/>            Valore massimo: 99999999. |
| destination_post_code_and_dps | Contiene il codice postale dell'indirizzo di consegna con DPS<br/>            Se interno, il codice postale/DP contiene il seguente numero di caratteri.<br/>            Area (1 o 2 caratteri) Distretto (1 o 2 caratteri)<br/>            Settore (1 carattere) Unità (2 caratteri) DPS (2 caratteri).<br/>            Il codice postale e il DPS devono rispettare un formato PAF® valido. |
| rts_flag | Flag che indica quale livello di servizio Return to Sender è richiesto. |
| return_to_sender_post_code | Contiene il codice postale Return to Sender ma senza DPS.<br/>            Il CP (senza DPS) deve rispettare un formato PAF®. |
| customer_content | Spazio opzionale per uso del cliente. |
| customer_content_encode_mode | Modalità di codifica del codice a barre Datamatrix.<br/>            Valore predefinito: EncodeMode.C40. |
| data_matrix_type | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| get_constructed_codetext() | Costruisci il codetext dai dati Mailmark. |
| init_from_string(constructed_codetext) | Inizializza i dati Mailmark dal codetext costruito. |
| get_barcode_type() | Ottiene il tipo di codice a barre. |

### Vedi anche

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

