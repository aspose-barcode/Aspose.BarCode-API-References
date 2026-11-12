---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Parametri PDF417."
type: docs
weight: 770
url: /it/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

Parametri PDF417. Contiene i parametri PDF417, MacroPDF417, MicroPDF417 e GS1MicroPdf417. MacroPDF417 richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono opzionali. MicroPDF417 in modalità Structured Append (stessa della modalità MacroPDF417) richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono opzionali. Questi esempi mostrano come codificare modalità non collegate UCC/EAN-128 in GS1MicroPdf417

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [getColumns()](#getcolumns) | Conteggio colonne. |
| [getECIEncoding()](#geteciencoding) | Identificatori di Interpretazione Canale Esteso. Viene usato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per |
| [getEncodeMode()](#getencodemode) | Identifica la modalità di codifica Pdf417. Valore predefinito: Auto. |
| [getErrorLevel()](#geterrorlevel) | Ottiene il tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8, level0 significa nessuna correzione errori |
| [getMacroCharacters()](#getmacrocharacters) | I valori dei caratteri macro 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con Micro |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per Structured A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Checksum del codice a barre MacroPdf417 (campo opzionale). Checksum del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append) |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Identificatori di Interpretazione del Canale Esteso. Si applica ai campi di testo Macro PDF417. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | ID file del codice a barre MacroPdf417 (campo obbligatorio). ID file del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Nome file del codice a barre MacroPdf417 (campo opzionale). Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Dimensione file MacroPdf417 (campo opzionale). Dimensione file MicroPDF417 (campo opzionale per la modalità Structured Append) La dimensione del file |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1. Codice a barre MicroPDF417 |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Conteggio segmenti del codice a barre MacroPdf417 (campo opzionale). Conteggio segmenti del codice a barre MicroPDF417 (campo opzionale per Structured A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Nome del mittente del codice a barre MacroPdf417 (campo opzionale). Nome del mittente del codice a barre MicroPDF417 (campo opzionale per Structured Append |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PD. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Timestamp del codice a barre MacroPdf417 (campo opzionale). Timestamp del codice a barre MicroPDF417 (campo opzionale per Structured Append mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Tipo di simbologia Pdf417 della modalità di compattazione del BarCode. Valore predefinito: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Identificatori di Interpretazione Canale Esteso. Viene usato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Identifica la modalità di codifica Pdf417. Valore predefinito: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | Ottiene il tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8, level0 significa nessuna correzione errori |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | Restituisce il nome del destinatario del codice a barre macro Pdf417. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | Restituisce il checksum del codice a barre macro Pdf417. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Identificatori di Interpretazione del Canale Esteso. Si applica ai campi di testo Macro PDF417. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Restituisce l'ID file del codice a barre macro Pdf417. Usato per MacroPdf417. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | Restituisce il nome file del codice a barre macro Pdf417. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | Restituisce la dimensione file del macro Pdf417. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | Restituisce l'ID segmento del codice a barre macro Pdf417, che parte da 0 fino a MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | Restituisce il conteggio dei segmenti del codice a barre macro Pdf417. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | Restituisce il nome del mittente del codice a barre macro Pdf417. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PD. |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | Restituisce il timestamp del codice a barre macro Pdf417. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio). |
| [getRows()](#getrows) | Conteggio righe. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Identifica l'ID del codice a barre DotCode in modalità structured append. L'ID parte da 1 e deve essere minore o uguale ai codici a barre |
| [getTruncate()](#gettruncate) | Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio). Conosciuto anche come CompactPDF417. Rigth row indicato |
| [isCode128Emulation()](#iscode128emulation) | Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione modalità 908 e |
| [isLinked()](#islinked) | Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica 906, 907 |
| [isReaderInitialization()](#isreaderinitialization) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore |
| [setAspectRatio()](#setaspectratio) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [setCode128Emulation()](#setcode128emulation) | Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione modalità 908 e |
| [setColumns()](#setcolumns) | Conteggio colonne. |
| [setECIEncoding()](#seteciencoding) | Identificatori di Interpretazione Canale Esteso. Viene usato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per |
| [setEncodeMode()](#setencodemode) | Identifica la modalità di codifica Pdf417. Valore predefinito: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Imposta il tipo di simbologia Pdf417 del livello di correzione errori del codice a barre, che varia da level0 a level8; level0 significa nessuna correzione errori |
| [setLinked()](#setlinked) | Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica 906, 907 |
| [setMacroCharacters()](#setmacrocharacters) | I valori dei caratteri macro 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con Micro |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per Structured A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | Checksum del codice a barre MacroPdf417 (campo opzionale). Checksum del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append) |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Identificatori di Interpretazione del Canale Esteso. Si applica ai campi di testo Macro PDF417. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | ID file del codice a barre MacroPdf417 (campo obbligatorio). ID file del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append |
| [setMacroPdf417FileName()](#setmacropdf417filename) | Nome file del codice a barre MacroPdf417 (campo opzionale). Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | Dimensione file MacroPdf417 (campo opzionale). Dimensione file MicroPDF417 (campo opzionale per la modalità Structured Append) La dimensione del file |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1. Codice a barre MicroPDF417 |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | Conteggio segmenti del codice a barre MacroPdf417 (campo opzionale). Conteggio segmenti del codice a barre MicroPDF417 (campo opzionale per Structured A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | Nome del mittente del codice a barre MacroPdf417 (campo opzionale). Nome del mittente del codice a barre MicroPDF417 (campo opzionale per Structured Append |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PD. |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | Timestamp del codice a barre MacroPdf417 (campo opzionale). Timestamp del codice a barre MicroPDF417 (campo opzionale per Structured Append mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Tipo di simbologia Pdf417 della modalità di compattazione del BarCode. Valore predefinito: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Identificatori di Interpretazione Canale Esteso. Viene usato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Identifica la modalità di codifica Pdf417. Valore predefinito: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Imposta il tipo di simbologia Pdf417 del livello di correzione errori del codice a barre, che varia da level0 a level8; level0 significa nessuna correzione errori |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | Imposta il nome del destinatario del codice a barre macro Pdf417. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | Imposta il checksum del codice a barre macro Pdf417. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Identificatori di Interpretazione del Canale Esteso. Si applica ai campi di testo Macro PDF417. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | Imposta l'ID file del codice a barre macro Pdf417. Utilizzato per MacroPdf417. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | Imposta il nome file del codice a barre macro Pdf417. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | Imposta la dimensione del file macro Pdf417. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | Imposta l'ID segmento del codice a barre macro Pdf417, che parte da 0 fino a MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | Imposta il conteggio dei segmenti del codice a barre macro Pdf417. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | Imposta il nome del mittente del codice a barre macro Pdf417. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PD. |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | Imposta il timestamp del codice a barre macro Pdf417. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio). |
| [setReaderInitialization(value)](#setreaderinitialization) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore |
| [setRows()](#setrows) | Conteggio righe. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Identifica l'ID del codice a barre DotCode in modalità structured append. L'ID parte da 1 e deve essere minore o uguale ai codici a barre |
| [setTruncate()](#settruncate) | Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio). Conosciuto anche come CompactPDF417. Rigth row indicato |
| [toString()](#tostring) | Restituisce una rappresentazione della stringa leggibile dall'uomo di questi Pdf417Parameters. |

### getAspectRatio() {#getaspectratio}

Rapporto Altezza/Larghezza del modulo BarCode 2D.

### getColumns() {#getcolumns}

Conteggio colonne.

### getECIEncoding() {#geteciencoding}

Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. Non applicato ai campi di testo Macro PDF417. L'implementazione attuale comprende tutte le codifiche di set di caratteri ben note.

### getEncodeMode() {#getencodemode}

Identifica la modalità di codifica Pdf417. Valore predefinito: Auto.

### getErrorLevel() {#geterrorlevel}

Ottiene il tipo di simbologia Pdf417 del livello di correzione errori del codice a barre, che varia da level0 a level8; level0 significa nessuna informazione di correzione errori, level8 indica la migliore correzione errori, che comporta un'immagine più grande.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

I valori dei Macro Caratteri 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con MicroPdf417 e codificano le modalità 916 e 917 di MicroPdf417. Valore predefinito: MacroCharacters.None. Questi esempi mostrano come codificare i Macro Caratteri in MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Checksum del codice a barre MacroPdf417 (campo opzionale). Checksum del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo checksum contiene il valore del checksum CRC a 16 bit (2 byte) usando il polinomio CCITT-16. x^16 + x^12 + x^5 + 1

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Identificatori di Interpretazione del Canale Esteso. Si applica ai campi di testo Macro PDF417.

### getMacroPdf417FileID() {#getmacropdf417fileid}

ID file del codice a barre MacroPdf417 (campo obbligatorio). ID file del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append).

### getMacroPdf417FileName() {#getmacropdf417filename}

Nome file del codice a barre MacroPdf417 (campo opzionale). Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Dimensione del file MacroPdf417 (campo opzionale). Dimensione del file MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo dimensione del file contiene la dimensione in byte dell'intero file sorgente.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1. ID segmento del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append).

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Conteggio dei segmenti del codice a barre MacroPdf417 (campo opzionale). Conteggio dei segmenti del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

### getMacroPdf417Sender() {#getmacropdf417sender}

Nome del mittente del codice a barre MacroPdf417 (campo opzionale). Nome del mittente del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PDF417.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Timestamp del codice a barre MacroPdf417 (campo opzionale). Timestamp del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

### getPdf417CompactionMode() {#getpdf417compactionmode}

Tipo di simbologia Pdf417 della modalità di compattazione del BarCode. Valore predefinito: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione attuale consiste di tutte le codifiche di set di caratteri conosciute.

### getPdf417EncodeMode() {#getpdf417encodemode}

Identifica la modalità di codifica Pdf417. Valore predefinito: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Ottiene il tipo di simbologia Pdf417 del livello di correzione errori del codice a barre, che varia da level0 a level8; level0 significa nessuna informazione di correzione errori, level8 indica la migliore correzione errori, che comporta un'immagine più grande.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Restituisce il nome del destinatario del codice a barre macro Pdf417.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Restituisce il checksum del codice a barre macro Pdf417.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Identificatori di Interpretazione del Canale Esteso. Si applica ai campi di testo Macro PDF417.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Restituisce l'ID file del codice a barre macro Pdf417. Usato per MacroPdf417.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Restituisce il nome file del codice a barre macro Pdf417.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Restituisce la dimensione file del macro Pdf417.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Restituisce l'ID segmento del codice a barre macro Pdf417, che parte da 0 fino a MacroSegmentsCount - 1.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Restituisce il conteggio dei segmenti del codice a barre macro Pdf417.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

Restituisce il nome del mittente del codice a barre macro Pdf417.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PDF417.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Restituisce il timestamp del codice a barre macro Pdf417.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio).

### getRows() {#getrows}

Conteggio righe.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Identifica l'ID del codice a barre DotCode in modalità structured append. L'ID inizia da 1 e deve essere minore o uguale al numero di codici a barre. Il valore predefinito è -1.

### getTruncate() {#gettruncate}

Indica se il tipo di simbologia Pdf417 del codice a barre è troncato (per ridurre lo spazio). Conosciuto anche come CompactPDF417. L'indicatore di riga destra e il pattern di stop destro sono rimossi in questa modalità.

### isCode128Emulation() {#iscode128emulation}

Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, può anche codificare 910 e 911 che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128. Questi esempi mostrano come codificare le modalità di emulazione Code 128 con FNC1 nella seconda posizione e senza. In questo modo MicroPdf417 può essere decodificato come codice a barre Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica le modalità “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato diverso da un EAN.UCC. Questi esempi mostrano come codificare le modalità \"Linked\" UCC/EAN-128 in GS1MicroPdf417 e il Flag di Collegamento (918) nei codici a barre MicroPdf417 e Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

Rapporto Altezza/Larghezza del modulo BarCode 2D.

### setCode128Emulation() {#setcode128emulation}

Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, può anche codificare 910 e 911 che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128. Questi esempi mostrano come codificare le modalità di emulazione Code 128 con FNC1 nella seconda posizione e senza. In questo modo MicroPdf417 può essere decodificato come codice a barre Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

Conteggio colonne.

### setECIEncoding() {#seteciencoding}

Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. Non applicato ai campi di testo Macro PDF417. L'implementazione attuale comprende tutte le codifiche di set di caratteri ben note.

### setEncodeMode() {#setencodemode}

Identifica la modalità di codifica Pdf417. Valore predefinito: Auto.

### setErrorLevel(value) {#seterrorlevel}

Imposta il tipo di simbologia Pdf417 del livello di correzione errori del codice a barre, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, il che comporta un'immagine più grande.

| Parametro | Descrizione |
| --- | --- |
| valore | Tipo di simbologia Pdf417 del livello di correzione errori del codice a barre, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, il che comporta un'immagine più grande. |

### setLinked() {#setlinked}

Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica le modalità “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato diverso da un EAN.UCC. Questi esempi mostrano come codificare le modalità \"Linked\" UCC/EAN-128 in GS1MicroPdf417 e il Flag di Collegamento (918) nei codici a barre MicroPdf417 e Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

I valori dei Macro Caratteri 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con MicroPdf417 e codificano le modalità 916 e 917 di MicroPdf417. Valore predefinito: MacroCharacters.None. Questi esempi mostrano come codificare i Macro Caratteri in MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

### setMacroPdf417Checksum() {#setmacropdf417checksum}

Checksum del codice a barre MacroPdf417 (campo opzionale). Checksum del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo checksum contiene il valore del checksum CRC a 16 bit (2 byte) usando il polinomio CCITT-16. x^16 + x^12 + x^5 + 1

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Identificatori di Interpretazione del Canale Esteso. Si applica ai campi di testo Macro PDF417.

### setMacroPdf417FileID() {#setmacropdf417fileid}

ID file del codice a barre MacroPdf417 (campo obbligatorio). ID file del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append).

### setMacroPdf417FileName() {#setmacropdf417filename}

Nome file del codice a barre MacroPdf417 (campo opzionale). Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

### setMacroPdf417FileSize() {#setmacropdf417filesize}

Dimensione del file MacroPdf417 (campo opzionale). Dimensione del file MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo dimensione del file contiene la dimensione in byte dell'intero file sorgente.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1. ID segmento del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append).

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

Conteggio dei segmenti del codice a barre MacroPdf417 (campo opzionale). Conteggio dei segmenti del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

### setMacroPdf417Sender() {#setmacropdf417sender}

Nome del mittente del codice a barre MacroPdf417 (campo opzionale). Nome del mittente del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

### setMacroPdf417Terminator() {#setmacropdf417terminator}

Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PDF417.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

Timestamp del codice a barre MacroPdf417 (campo opzionale). Timestamp del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

### setPdf417CompactionMode() {#setpdf417compactionmode}

Tipo di simbologia Pdf417 della modalità di compattazione del BarCode. Valore predefinito: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione attuale consiste di tutte le codifiche di set di caratteri conosciute.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Identifica la modalità di codifica Pdf417. Valore predefinito: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Imposta il tipo di simbologia Pdf417 del livello di correzione errori del codice a barre, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, il che comporta un'immagine più grande.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Imposta il nome del destinatario del codice a barre macro Pdf417.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Imposta il checksum del codice a barre macro Pdf417.

| Parametro | Descrizione |
| --- | --- |
| valore | Il campo checksum contiene il valore del checksum CRC a 16 bit (2 byte) usando il polinomio CCITT-16. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Identificatori di Interpretazione del Canale Esteso. Si applica ai campi di testo Macro PDF417.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Imposta l'ID file del codice a barre macro Pdf417. Utilizzato per MacroPdf417.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Imposta il nome file del codice a barre macro Pdf417.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Imposta la dimensione del file macro Pdf417.

| Parametro | Descrizione |
| --- | --- |
| valore | Il campo dimensione file contiene la dimensione in byte dell'intero file sorgente. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Imposta l'ID segmento del codice a barre macro Pdf417, che parte da 0 fino a MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Imposta il conteggio dei segmenti del codice a barre macro Pdf417.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

Imposta il nome del mittente del codice a barre macro Pdf417.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PDF417.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Imposta il timestamp del codice a barre macro Pdf417.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio).

### setReaderInitialization(value) {#setreaderinitialization}

Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore

| Parametro | Descrizione |
| --- | --- |
| valore |  |

### setRows() {#setrows}

Conteggio righe.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Identifica l'ID del codice a barre DotCode in modalità structured append. L'ID inizia da 1 e deve essere minore o uguale al numero di codici a barre. Il valore predefinito è -1.

### setTruncate() {#settruncate}

Indica se il tipo di simbologia Pdf417 del codice a barre è troncato (per ridurre lo spazio). Conosciuto anche come CompactPDF417. L'indicatore di riga destra e il pattern di stop destro sono rimossi in questa modalità.

### toString() {#tostring}

Restituisce una rappresentazione della stringa leggibile dall'uomo di questi Pdf417Parameters.

**Returns:** A string that represents this Pdf417Parameters.
