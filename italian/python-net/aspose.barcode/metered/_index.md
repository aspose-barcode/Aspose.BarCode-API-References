---
title: "Metered"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode/metered/
---

## Metered class

Fornisce metodi per impostare la chiave a consumo.

Il tipo Metered espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Metered() | Inizializza una nuova istanza della classe Metered |
## Metodi
| Nome | Descrizione |
| :- | :- |
| set_metered_key(public_key, private_key) | Imposta la chiave pubblica e privata a consumo.<br/>            Se acquisti una licenza a consumo, all'avvio dell'applicazione, questa API dovrebbe essere chiamata; normalmente è sufficiente. <br/>            Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata in stato di valutazione, <br/>            per evitare tale caso, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente questa API. |
| get_consumption_quantity() | Restituisce la dimensione del file di consumo |
| get_consumption_credit() | Restituisce il credito di consumo |
| get_product_name() | Restituisce il nome del prodotto con licenza |
| is_metered_licensed() | Verifica se la licenza a consumo è attiva |

### Vedi anche

* namespace [aspose.barcode](/barcode/python-net/aspose.barcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

