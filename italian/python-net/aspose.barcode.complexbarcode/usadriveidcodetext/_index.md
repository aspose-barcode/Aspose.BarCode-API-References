---
title: "USADriveIdCodetext"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

Classe per la codifica e la decodifica del testo incorporato nel codice PDF417 della patente di guida USA.

Il tipo USADriveIdCodetext espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| USADriveIdCodetext() | Inizializza una nuova istanza della classe USADriveIdCodetext |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| issuer_identification_number | Questo numero identifica univocamente <br/>            la giurisdizione emittente e può essere ottenuto contattando l'ISO<br/>            Issuing Authority (AAMVA).  Il IIN completo a 6 cifre dovrebbe essere codificato. |
| aamva_version_number | Numero di versione AAMVA 00-99 |
| jurisdiction_version_number | Numero di versione della giurisdizione 00-99 |
| number_of_entries | Numero 00-99 di subfile |
| subfile_designator | Contiene informazioni sui seguenti subfile, tipi, offset e lunghezze. <br/>            Importante: impostare solo il tipo, l'offset e la lunghezza verranno impostati automaticamente. |
| mandatory_elements | Elementi obbligatori (campi) della carta |
| optional_elements | Elementi opzionali (campi) della carta |
| jurisdiction_specific_subfile | Campi specifici della giurisdizione |
## Metodi
| Nome | Descrizione |
| :- | :- |
| get_constructed_codetext() | Costruisci il codetesto dai dati della patente USA |
| init_from_string(constructed_codetext) | Inizializza l'oggetto USA DL dal codetesto |
| get_barcode_type() | Restituisce il tipo di codice a barre della USA DL (Pdf417) |
| save_to_xml(stream) | Salva in XML |

### Vedi anche

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

