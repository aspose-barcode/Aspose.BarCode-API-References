---
title: "BarCodeReader"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader incapsula un'immagine che può contenere uno o più codici a barre, quindi può eseguire l'operazione ReadBarCodes per rilevare i codici a barre.

Il tipo BarCodeReader espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| BarCodeReader() | Inizializza una nuova istanza della classe [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) con valori predefiniti.<br/>            Richiede di impostare l'immagine (SetBitmapImage()) prima di chiamare il metodo ReadBarCodes(). |
| BarCodeReader(image) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(image, decode_types) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(image, type) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(image, area, decode_types) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(image, area, type) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(image, areas, decode_types) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(image, areas, type) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(filename) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(filename, decode_types) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(filename, type) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(stream) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(stream, type) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(stream, decode_types) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(frame, areas, type) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(frame, areas, decode_types) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(frame, area, type) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(frame, area, decode_types) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(frame, type) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(frame, decode_types) | Inizializza una nuova istanza della classe BarCodeReader |
| BarCodeReader(frame) | Inizializza una nuova istanza della classe BarCodeReader |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| processor_settings | Ottiene le impostazioni per l'uso dei core del processore. |
| timeout | Ottiene o imposta il timeout del processo di riconoscimento in millisecondi. |
| found_bar_codes | Ottiene l'array di [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) riconosciuti |
| found_count | Ottiene il conteggio dei codici a barre riconosciuti |
| quality_settings | QualitySettings permette di configurare manualmente la qualità e la velocità del riconoscimento.<br/>            È possibile impostare rapidamente QualitySettings tramite preset incorporati: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes oppure configurare manualmente opzioni separate.<br/>            Il valore predefinito di QualitySettings è NormalQuality. |
| barcode_settings | I principali parametri di decodifica BarCode. Contiene parametri che influenzano i dati riconosciuti. |
| bar_code_read_type | Ottiene o imposta il tipo di decodifica del codice a barre utilizzato per il riconoscimento.<br/>            Deve essere impostato prima di chiamare [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
## Metodi
| Nome | Descrizione |
| :- | :- |
| set_bar_code_image(value) | Imposta l'immagine bitmap per il riconoscimento. <br/>            Deve essere chiamato prima del metodo ReadBarCodes(). |
| set_bar_code_image(value, areas) | Imposta l'immagine bitmap e le aree per il riconoscimento. <br/>            Deve essere chiamato prima del metodo ReadBarCodes(). |
| set_bar_code_image(value, area) | Imposta l'immagine bitmap e le aree per il riconoscimento. <br/>            Deve essere chiamato prima del metodo ReadBarCodes(). |
| set_bar_code_image(filename) | Imposta il file immagine per il riconoscimento. <br/>            Deve essere chiamato prima del metodo ReadBarCodes(). |
| set_bar_code_image(stream) | Imposta lo stream dell'immagine per il riconoscimento. <br/>            Deve essere chiamato prima del metodo ReadBarCodes(). |
| set_bar_code_image(frame, area) | Imposta il frame di luminanza e l'area per il riconoscimento. Deve essere chiamato prima del metodo [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame, areas) | Imposta il frame di luminanza e le aree per il riconoscimento. Deve essere chiamato prima del metodo [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame) | Imposta il frame di luminanza e l'area per il riconoscimento. Deve essere chiamato prima del metodo [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| export_to_xml(xml_file) | Esporta le proprietà BarCode nel file XML specificato |
| export_to_xml(xml_stream) | Esporta le proprietà BarCode nello stream XML specificato |
| import_from_xml(xml_file) | Importa le proprietà BarCode dal file XML specificato e le applica all'istanza corrente di BarCodeReader. |
| import_from_xml(xml_stream) | Importa le proprietà BarCode dallo stream XML specificato e le applica all'istanza corrente di BarCodeReader. |
| abort() | La funzione richiede la terminazione della sessione di riconoscimento corrente da un altro thread. Abort è un metodo non bloccante e restituisce il controllo subito dopo la chiamata. <br/>            Il metodo dovrebbe essere usato quando il processo di riconoscimento è troppo lungo. |
| read_bar_codes() | Legge [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s dall'immagine. |
| set_bar_code_read_type(barcode_types) | Imposta l'array di tipo [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) per il riconoscimento. <br/>            Deve essere chiamato prima del metodo ReadBarCodes(). |

### Vedi anche

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

