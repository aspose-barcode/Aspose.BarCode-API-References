---
title: "SecondaryAndAdditionalData"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Classe per la memorizzazione dei dati secondari e aggiuntivi HIBC LIC.

Il tipo SecondaryAndAdditionalData espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| SecondaryAndAdditionalData() | Inizializza una nuova istanza della classe SecondaryAndAdditionalData |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| expiry_date_format | Identifica il formato della data di scadenza. |
| expiry_date | Identifica la data di scadenza. Verrà utilizzata se ExpiryDateFormat non è impostato su None. |
| lot_number | Identifica il numero di lotto o di batch. Il numero di lotto/batch deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. |
| serial_number | Identifica il numero di serie. Il numero di serie deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. |
| date_of_manufacture | Identifica la data di produzione.<br/>            La data di produzione può essere impostata a DateTime.MinValue per non utilizzare questo campo.<br/>            Valore predefinito: DateTime.MinValue |
| quantity | Identifica la quantità, deve essere un valore intero da 0 a 500. <br/>            La quantità può essere impostata a -1 per non utilizzare questo campo.<br/>            Valore predefinito: -1 |
## Metodi
| Nome | Descrizione |
| :- | :- |
| parse_from_string(secondary_data_codetext) | Istanzia dati secondari e supplementari aggiuntivi dal formato stringa secondo la specifica HIBC LIC. |

### Vedi anche

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

