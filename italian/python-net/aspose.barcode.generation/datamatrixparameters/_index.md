---
title: "DataMatrixParameters"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

Parametri DataMatrix.

Il tipo DataMatrixParameters espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| ecc_type | Ottiene o imposta un tipo ECC Datamatrix.<br/>            Valore predefinito: DataMatrixEccType.Ecc200. |
| version | Ottiene o imposta una dimensione del simbolo Datamatrix.<br/>            Valore predefinito: Version.Auto. |
| encode_mode | Modalità di codifica del codice a barre Datamatrix.<br/>            Valore predefinito: EncodeMode.Auto. |
| structured_append_barcode_id | ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix.<br/>            Valore predefinito: 0 |
| structured_append_barcodes_count | Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix.<br/>            Valore predefinito: 0 |
| structured_append_file_id | ID file per la modalità Structured Append del codice a barre Datamatrix.<br/>            Valore predefinito: 0 |
| is_reader_programming | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo<br/>            come programmazione per l'inizializzazione del lettore.<br/>            Valore predefinito: false |
| macro_characters | I valori Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali.<br/>            Possono essere usati solo con DataMatrixEccType.Ecc200 o DataMatrixEccType.EccAuto.<br/>            Non possono essere usati con EncodeTypes.GS1DataMatrix<br/>            Valore predefinito: MacroCharacters.None. |
| aspect_ratio | Rapporto altezza/larghezza del modulo 2D BarCode. |
| eci_encoding | Ottiene o imposta la codifica ECI. Utilizzata quando EncodeMode è Auto.<br/>            Valore predefinito: ISO-8859-1 |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

