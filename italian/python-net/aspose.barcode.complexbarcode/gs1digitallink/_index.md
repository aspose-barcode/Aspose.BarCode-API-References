---
title: "GS1DigitalLink"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

Rappresenta il codetext GS1 Digital Link per la codifica e la decodifica come una sequenza ordinata di<br/>            elementi Application Identifier. L'ordine di origine e gli Application Identifier ripetuti sono preservati.<br/>            Il codetext costruito è un URI GS1 Digital Link non compresso.<br/>            I parametri di query non GS1 e i frammenti URI sono ignorati durante l'analisi.

Il tipo GS1DigitalLink espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| GS1DigitalLink(uri_stem) | Inizializza una nuova istanza della classe GS1DigitalLink |
| GS1DigitalLink(uri_stem, primary_application_identifier) | Inizializza una nuova istanza della classe GS1DigitalLink |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| uri_stem | Restituisce il prefisso URI assoluto prima del segmento di percorso della chiave primaria GS1.<br/>            Il prefisso non contiene una stringa di query o un frammento. |
| primary_application_identifier | Restituisce l'Identificatore di Applicazione utilizzato come chiave primaria del Digital Link.<br/>            Null indica che la chiave primaria viene selezionata automaticamente quando l'URI è costruito. |
| barcode_type | Ottiene o imposta il tipo di codice a barre utilizzato per codificare questo GS1 Digital Link.<br/>            I tipi supportati sono QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF e Code128.<br/>            Il valore predefinito è QR. |
| conteggio | Restituisce il numero di elementi dell'Identificatore di Applicazione. |
| elementi | Restituisce una copia di tutti gli elementi nell'ordine di origine. |
## Indexer
| Nome | Descrizione |
| :- | :- |
| [index] | Restituisce un elemento in base alla sua posizione nella sequenza ordinata. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| create(uri_stem, codetext) | Crea un GS1 Digital Link copiando tutti gli elementi dal codetext GS1 e selezionando<br/>            l'unica chiave primaria disponibile. |
| create(uri_stem, codetext, primary_application_identifier) | Crea un GS1 Digital Link copiando tutti gli elementi dal codetext GS1 e selezionando<br/>            l'unica chiave primaria disponibile. |
| get_first(application_identifier) | Restituisce il primo valore per un Identificatore di Applicazione. |
| get_all(application_identifier) | Restituisce tutti i valori per un Identificatore di Applicazione nell'ordine di origine. |
| add(application_identifier, value) | Aggiunge un elemento di Identificatore di Applicazione convalidato. |
| validate(value) | Convalida un URI GS1 Digital Link non compresso senza costruire un oggetto. |
| parse(value) | Analizza un URI GS1 Digital Link non compresso. |
| try_parse(value, result, validation_result) | Tenta di analizzare un URI GS1 Digital Link non compresso e restituisce errori di convalida strutturati. |
| to_gs1_codetext() | Crea un codetext GS1 indipendente contenente gli attuali elementi GS1.<br/>            Le informazioni solo URI non sono incluse. |
| to_uri_string() | Formatta lo stato corrente dell'oggetto come un URI GS1 Digital Link non compresso. |
| get_constructed_codetext() | Costruisce l'URI GS1 Digital Link non compresso. |
| init_from_string(constructed_codetext) | Inizializza questa istanza da un URI GS1 Digital Link non compresso.<br/>            Lo stato esistente viene sostituito solo dopo che l'URI fornito è stato analizzato con successo.<br/>            Il tipo di codice a barre selezionato è preservato. |
| get_barcode_type() | Restituisce il tipo di codice a barre utilizzato per codificare questo GS1 Digital Link. |

### Vedi anche

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

