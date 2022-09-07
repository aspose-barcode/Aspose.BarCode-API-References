---
title: Pdf417Parameters
second_title: Riferimento all'API Aspose.BarCode per .NET
description: parametri PDF417. Contiene i parametri PDF417 MacroPDF417 e MicroPDF417. MacroPDF417 richiede due campi Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono facoltativi. MicroPDF417 in modalità di aggiunta strutturata uguale alla modalità MacroPDF417 richiede due campi Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono facoltativi.
type: docs
weight: 860
url: /it/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

parametri PDF417. Contiene i parametri PDF417, MacroPDF417 e MicroPDF417. MacroPDF417 richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono facoltativi. MicroPDF417 in modalità di aggiunta strutturata (uguale alla modalità MacroPDF417) richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono facoltativi.

```csharp
public class Pdf417Parameters
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio) { get; set; } | Rapporto altezza/larghezza del modulo codice a barre 2D. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation) { get; set; } | Parola codice funzione per emulazione Code 128. Applicato solo per MicroPDF417. Ignorato per i codici a barre PDF417 e MacroPDF417. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding) { get; set; } | Ottiene o imposta la codifica del testo del codice. Valore predefinito: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns) { get; set; } | Conteggio colonne. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization) { get; set; } | Utilizzato per istruire il lettore ad interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode) { get; set; } | Pdf417 tipo di simbologia della modalità di compattazione di BarCode. Valore predefinito: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding) { get; set; } | Identificatori di interpretazione del canale estesi. Viene utilizzato per comunicare al lettore di codici a barre dettagli sui riferimenti utilizzati per codificare i dati nel simbolo. Non applicato per i campi di testo Macro PDF417. L'implementazione corrente consiste in tutte le codifiche di set di caratteri ben note. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel) { get; set; } | Ottiene o imposta il tipo di simbologia Pdf417 del livello di correzione degli errori di BarCode che va da level0 a level8, level0 significa nessuna informazione di correzione degli errori, level8 significa la migliore correzione degli errori che significa un'immagine più grande. |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee) { get; set; } | Nome destinatario codice a barre MacroPdf417 (campo opzionale). Nome destinatario codice a barre MicroPDF417 (campo opzionale per la modalità di aggiunta strutturata) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum) { get; set; } | Checksum codice a barre MacroPdf417 (campo opzionale). Checksum codice a barre MicroPDF417 (campo opzionale per la modalità di aggiunta strutturata) Il campo checksum contiene il valore del checksum CRC a 16 bit (2 byte) utilizzando il polinomio CCITT-16. x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding) { get; set; } | Identificatori di interpretazione del canale estesi. Si applica ai campi di testo Macro PDF417. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid) { get; set; } | ID file del codice a barre MacroPdf417 (campo obbligatorio). ID file del codice a barre MicroPDF417 (campo obbligatorio per la modalità di aggiunta strutturata) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename) { get; set; } | Nome file codice a barre MacroPdf417 (campo opzionale). Nome file codice a barre MicroPDF417 (campo opzionale per modalità di aggiunta strutturata) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize) { get; set; } | Dimensione file MacroPdf417 (campo facoltativo). Dimensione file MicroPDF417 (campo facoltativo per la modalità di aggiunta strutturata) Il campo dimensione file contiene la dimensione in byte dell'intero file sorgente. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid) { get; set; } | ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che inizia da 0, a MacroSegmentsCount - 1. ID segmento del codice a barre MicroPDF417 (campo obbligatorio per la modalità di aggiunta strutturata) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount) { get; set; } | Conteggio segmenti codice a barre MacroPdf417 (campo opzionale). Conteggio segmenti codice a barre MicroPDF417 (campo opzionale per modalità di aggiunta strutturata) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender) { get; set; } | Nome mittente codice a barre MacroPdf417 (campo opzionale). Nome mittente codice a barre MicroPDF417 (campo opzionale per la modalità di aggiunta strutturata) |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp) { get; set; } | Indicatore data e ora codice a barre MacroPdf417 (campo opzionale). Indicatore data e ora codice a barre MicroPDF417 (campo facoltativo per la modalità di aggiunta strutturata) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate) { get; set; } | Se il tipo di simbologia Pdf417 del codice a barre è troncato (per ridurre lo spazio). Conosciuto anche come CompactPDF417. L'indicatore della riga destra e lo schema di arresto destro vengono rimossi in questa modalità. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows) { get; set; } | Conteggio righe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring)() | Restituisce una rappresentazione di stringa leggibile dall'uomo di questo[`Pdf417Parameters`](../pdf417parameters) . |

### Guarda anche

* spazio dei nomi [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
