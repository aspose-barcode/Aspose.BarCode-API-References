---
title: "BarcodeGenerator"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator per la generazione di immagini barcode sul backend.

Il tipo BarcodeGenerator espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| BarcodeGenerator(type) | Inizializza una nuova istanza della classe BarcodeGenerator |
| BarcodeGenerator(type, code_text) | Inizializza una nuova istanza della classe BarcodeGenerator |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| parameters | Parametri di generazione. |
| barcode_type | Tipo di simbologia del codice a barre. |
| code_text | Testo da codificare. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| set_code_text(code_bytes) | Imposta il testo del codice come sequenza di byte. |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | Salva l'immagine del codice a barre su stream in formato specifico. |
| save(filename, format) | Salva l'immagine del codice a barre su file specifico in formato specifico. |
| save(filename) | Salva l'immagine del codice a barre su file specifico in formato specifico. |
| export_to_xml(xml_file) | Esporta le proprietà BarCode nel file XML specificato |
| export_to_xml(xml) | Esporta le proprietà BarCode nello stream XML specificato |
| import_from_xml(xml_file) | Importa le proprietà BarCode dal file XML specificato e crea un'istanza di BarcodeGenerator. |
| import_from_xml(xml) | Importa le proprietà BarCode dallo stream XML specificato e crea un'istanza di BarcodeGenerator. |
| generate_bar_code_image() | Genera l'immagine del codice a barre con le impostazioni correnti. |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

