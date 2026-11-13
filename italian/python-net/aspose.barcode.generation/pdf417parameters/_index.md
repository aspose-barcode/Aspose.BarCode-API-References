---
title: "Pdf417Parameters"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

Parametri PDF417. Contiene i parametri PDF417, MacroPDF417, MicroPDF417 e GS1MicroPdf417.<br/>            MacroPDF417 richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono opzionali.<br/>            MicroPDF417 in modalità Structured Append (stessa della modalità MacroPDF417) richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono opzionali.

Il tipo Pdf417Parameters espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| encode_mode | Identifica la modalità di codifica Pdf417. <br/>            Valore predefinito: Auto. |
| error_level | Ottiene o imposta il tipo di simbologia Pdf417 del livello di correzione errori del BarCode<br/>            che varia da level0 a level8, level0 indica nessuna informazione di correzione errori,<br/>            level8 indica la migliore correzione errori, il che comporta un'immagine più grande. |
| truncate | Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio). <br/>            Conosciuto anche come CompactPDF417. L'indicatore di riga destra e il pattern di stop destro sono rimossi in questa modalità. |
| colonne | Conteggio colonne. |
| righe | Conteggio righe. |
| aspect_ratio | Rapporto altezza/larghezza del modulo 2D BarCode. |
| macro_pdf_417_file_id | ID file del codice a barre MacroPdf417 (campo obbligatorio).<br/>            ID file del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append). |
| macro_pdf_417_segment_id | ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1.<br/>            ID segmento del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append). |
| macro_pdf_417_segments_count | Conteggio segmenti del codice a barre MacroPdf417 (campo opzionale).<br/>            Conteggio segmenti del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| macro_pdf_417_file_name | Nome file del codice a barre MacroPdf417 (campo opzionale).<br/>            Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| macro_pdf_417_time_stamp | Timestamp del codice a barre MacroPdf417 (campo opzionale).<br/>            Timestamp del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| macro_pdf_417_sender | Nome del mittente del codice a barre MacroPdf417 (campo opzionale).<br/>            Nome del mittente del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| macro_pdf_417_addressee | Nome del destinatario del codice a barre MacroPdf417 (campo opzionale).<br/>            Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| macro_pdf_417_file_size | Dimensione del file MacroPdf417 (campo facoltativo).<br/>            Dimensione del file MicroPDF417 (campo facoltativo per la modalità Structured Append)<br/>            Il campo dimensione del file contiene la dimensione in byte dell'intero file sorgente. |
| macro_pdf_417_checksum | Checksum del codice a barre MacroPdf417 (campo facoltativo).<br/>            Checksum del codice a barre MicroPDF417 (campo facoltativo per la modalità Structured Append)<br/>            Il campo checksum contiene il valore del checksum CRC a 16 bit (2 byte) usando il polinomio CCITT-16. x^16 + x^12 + x^5 + 1 |
| eci_encoding | Identificatori di Interpretazione del Canale Esteso. Vengono usati per fornire al lettore di codici a barre dettagli<br/>            sui riferimenti utilizzati per codificare i dati nel simbolo. Non applicati ai campi di testo Macro PDF417.<br/>            L'implementazione attuale comprende tutte le codifiche di set di caratteri conosciute. |
| macro_pdf_417eci_encoding | Identificatori di Interpretazione del Canale Esteso. Si applicano ai campi di testo Macro PDF417. |
| macro_pdf_417_terminator | Usato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. <br/>            Applicato solo per Macro PDF417. |
| is_reader_initialization | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo<br/>            come programmazione per l'inizializzazione del lettore. |
| macro_characters | I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali.<br/>            Possono essere usati solo con MicroPdf417 e codificano le modalità MicroPdf417 916 e 917<br/>            Valore predefinito: MacroCharacters.None. |
| is_linked | Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417<br/>            Con la simbologia GS1MicroPdf417 codifica le modalità UCC/EAN-128 “Linked” 906, 907, 912, 913, 914, 915<br/>            Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato diverso da un EAN.UCC |
| is_code_128_emulation | Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128<br/>            Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, può anche codificare 910 e 911 che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128 |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

