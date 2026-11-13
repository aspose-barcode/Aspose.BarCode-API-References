---
title: "GS1Codetext"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

Rappresenta il codetext GS1 per la codifica e la decodifica come una sequenza ordinata di<br/>            elementi Application Identifier. L'ordine di origine e gli Application Identifier ripetuti<br/>            sono preservati. La rappresentazione tra parentesi ha la forma (AI)valore(AI)valore.<br/>            Una parentesi aperta letterale '(' all'interno di un valore deve essere scritta come \(; questa è la<br/>            sola sequenza di escape supportata. Una parentesi chiusa ')' all'interno di un valore non<br/>            richiede escape.

Il tipo GS1Codetext espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| GS1Codetext() | Inizializza una nuova istanza della classe GS1Codetext |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| barcode_type | Ottiene o imposta il tipo di codice a barre utilizzato per codificare questo testo GS1.<br/>            I tipi supportati sono GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix,<br/>            GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR e i tipi GS1 DataBar.<br/>            Il valore predefinito è GS1Code128. |
| conteggio | Restituisce il numero di elementi dell'Identificatore di Applicazione. |
| elementi | Restituisce una copia di tutti gli elementi nell'ordine di origine. |
## Indexer
| Nome | Descrizione |
| :- | :- |
| [index] | Restituisce un elemento in base alla sua posizione nella sequenza ordinata. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| get_first(application_identifier) | Restituisce il primo valore per un Identificatore di Applicazione. |
| get_all(application_identifier) | Restituisce tutti i valori per un Identificatore di Applicazione nell'ordine di origine. |
| add(application_identifier, value) | Aggiunge un elemento di Identificatore di Applicazione convalidato. |
| validate(value) | Convalida una stringa di elemento GS1 tra parentesi nella forma (AI)valore(AI)valore senza<br/>            costruire un oggetto. Un '(' letterale all'interno di un valore deve essere scritto come \(; nessuna<br/>            altra sequenza di escape è supportata, e ')' non richiede escape. |
| parse(value) | Analizza una stringa di elemento GS1 tra parentesi nella forma (AI)valore(AI)valore. Un '(' letterale<br/>            all'interno di un valore deve essere scritto come \(; nessun altra sequenza di escape è supportata,<br/>            e ')' non richiede escape. |
| try_parse(value, result, validation_result) | Tenta di analizzare una stringa di elemento GS1 tra parentesi nella forma (AI)valore(AI)valore<br/>            e restituisce errori di convalida strutturati. Un '(' letterale all'interno di un valore deve essere<br/>            scritto come \(; nessuna altra sequenza di escape è supportata, e ')' non richiede<br/>            escape. |
| get_constructed_codetext() | Costruisce il testo codificato GS1 tra parentesi nella forma (AI)valore(AI)valore.<br/>            Le parentesi di apertura letterali nei valori sono escape come \(. |
| init_from_string(constructed_codetext) | Inizializza questa istanza dal testo codificato GS1 tra parentesi nella forma (AI)valore(AI)valore.<br/>            Gli elementi esistenti vengono sostituiti solo dopo che il testo fornito è stato analizzato con successo. |
| get_barcode_type() | Ottiene il tipo di codice a barre utilizzato per codificare questo testo GS1. |

### Vedi anche

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

