---
title: "AztecParameters"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/aztecparameters/
---

## AztecParameters class

Parametri Aztec.

Il tipo AztecParameters espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| encode_mode | Ottiene o imposta una modalità di codifica Aztec. <br/>            Valore predefinito: Auto. |
| eci_encoding | Ottiene o imposta la codifica ECI. Utilizzata quando AztecEncodeMode è Auto.<br/>            Valore predefinito: ISO-8859-1 |
| structured_append_barcode_id | ID del codice a barre per la modalità Structured Append del codice a barre Aztec. L'ID del codice a barre deve essere nell'intervallo da 1 al numero totale di codici a barre.<br/>            Valore predefinito: 0 |
| structured_append_barcodes_count | Il conteggio dei codici a barre per la modalità Structured Append del codice a barre Aztec. Il conteggio dei codici a barre deve essere compreso tra 1 e 26.<br/>            Valore predefinito: 0 |
| structured_append_file_id | ID file per la modalità Structured Append del codice a barre Aztec (campo opzionale). L'ID file non deve contenere spazi.<br/>            Valore predefinito: stringa vuota |
| error_level | Livello di correzione degli errori dei tipi di codice a barre Aztec.<br/>            Il valore deve essere compreso tra 5 e 95. |
| symbol_mode | Ottiene o imposta una modalità Symbol Aztec.<br/>            Valore predefinito: AztecSymbolMode.Auto. |
| layers_count | Ottiene o imposta il conteggio dei livelli del simbolo Aztec. Il conteggio dei livelli deve essere compreso tra 1 e 3 per la modalità Compact e<br/>            compreso tra 1 e 32 per la modalità Full Range.<br/>            Valore predefinito: 0 (auto). |
| is_reader_initialization | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo<br/>            come programmazione per l'inizializzazione del lettore. |
| aspect_ratio | Rapporto altezza/larghezza del modulo 2D BarCode. |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

