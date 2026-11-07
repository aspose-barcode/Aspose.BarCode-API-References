---
title: "Classe Aspose::BarCode::Generation::Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Classe Aspose::BarCode::Generation::Pdf417Parameters. Parametri PDF417. Contiene i parametri PDF417, MacroPDF417, MicroPDF417 e GS1MicroPdf417. MacroPDF417 richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono opzionali. MicroPDF417 in modalità Structured Append (stessa della modalità MacroPDF417) richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono opzionali in C++."
type: docs
weight: 4000
url: /it/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


Parametri PDF417. Contiene i parametri PDF417, MacroPDF417, MicroPDF417 e GS1MicroPdf417. MacroPDF417 richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono opzionali. MicroPDF417 in modalità Structured Append (stessa della modalità MacroPDF417) richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono opzionali.

```cpp
class Pdf417Parameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Rapporto Altezza/Larghezza del modulo [BarCode](../../aspose.barcode/) 2D. |
| [get_Columns](./get_columns/)() const | Conteggio colonne. |
| [get_ECIEncoding](./get_eciencoding/)() const | Identificatori di Extended Channel Interpretation. Vengono usati per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per codificare i dati nel simbolo. Non si applicano ai campi di testo Macro PDF417. L'implementazione attuale comprende tutte le codifiche di set di caratteri conosciute. |
| [get_EncodeMode](./get_encodemode/)() const | Identifica la modalità di codifica Pdf417. Valore predefinito: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Ottiene il tipo di simbologia Pdf417 del livello di correzione errori di [BarCode](../../aspose.barcode/), che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, che comporta un'immagine più grande. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, e può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128. |
| [get_IsLinked](./get_islinked/)() const | Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica le modalità “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 verso il componente lineare associato, diverso da un EAN.UCC. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [get_MacroCharacters](./get_macrocharacters/)() const | I valori Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con MicroPdf417 e codificano le modalità MicroPdf417 916 e 917. Valore predefinito: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Checksum del codice a barre MacroPdf417 (campo opzionale). Checksum del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo checksum contiene il valore del checksum CRC a 16 bit (2 byte) usando il polinomio CCITT-16. x^16 + x^12 + x^5 + 1 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Identificatori di Extended Channel Interpretation. Si applicano ai campi di testo Macro PDF417. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | ID file del codice a barre MacroPdf417 (campo obbligatorio). ID file del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append). |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Nome file del codice a barre MacroPdf417 (campo opzionale). Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Dimensione file MacroPdf417 (campo opzionale). Dimensione file MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo dimensione file contiene la dimensione in byte dell'intero file sorgente. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1. ID segmento del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append). |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Conteggio segmenti del codice a barre MacroPdf417 (campo opzionale). Conteggio segmenti del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Nome del mittente del codice a barre MacroPdf417 (campo opzionale). Nome del mittente del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Usato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Marca temporale del codice a barre MacroPdf417 (campo opzionale). Marca temporale del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| [get_Rows](./get_rows/)() const | Conteggio righe. |
| [get_Truncate](./get_truncate/)() const | Indica se il tipo di simbologia Pdf417 di [BarCode](../../aspose.barcode/) è troncato (per ridurre lo spazio). Conosciuto anche come CompactPDF417. L'indicatore di riga destra e il pattern di stop destro sono rimossi in questa modalità. |
| [set_AspectRatio](./set_aspectratio/)(float) | Rapporto Altezza/Larghezza del modulo [BarCode](../../aspose.barcode/) 2D. |
| [set_Columns](./set_columns/)(int32_t) | Conteggio colonne. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identificatori di Extended Channel Interpretation. Vengono usati per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per codificare i dati nel simbolo. Non si applicano ai campi di testo Macro PDF417. L'implementazione attuale comprende tutte le codifiche di set di caratteri conosciute. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Identifica la modalità di codifica Pdf417. Valore predefinito: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | Imposta il tipo di simbologia Pdf417 del livello di correzione errori di [BarCode](../../aspose.barcode/), che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, il che comporta un'immagine più grande. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, e può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128. |
| [set_IsLinked](./set_islinked/)(bool) | Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica le modalità “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 verso il componente lineare associato, diverso da un EAN.UCC. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | I valori Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con MicroPdf417 e codificano le modalità MicroPdf417 916 e 917. Valore predefinito: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | Checksum del codice a barre MacroPdf417 (campo opzionale). Checksum del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo checksum contiene il valore del checksum CRC a 16 bit (2 byte) usando il polinomio CCITT-16. x^16 + x^12 + x^5 + 1 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Identificatori di Extended Channel Interpretation. Si applicano ai campi di testo Macro PDF417. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | ID file del codice a barre MacroPdf417 (campo obbligatorio). ID file del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append). |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | Nome file del codice a barre MacroPdf417 (campo opzionale). Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | Dimensione file MacroPdf417 (campo opzionale). Dimensione file MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo dimensione file contiene la dimensione in byte dell'intero file sorgente. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1. ID segmento del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append). |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | Conteggio segmenti del codice a barre MacroPdf417 (campo opzionale). Conteggio segmenti del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | Nome del mittente del codice a barre MacroPdf417 (campo opzionale). Nome del mittente del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | Usato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PDF417. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | Marca temporale del codice a barre MacroPdf417 (campo opzionale). Marca temporale del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). |
| [set_Rows](./set_rows/)(int32_t) | Conteggio righe. |
| [set_Truncate](./set_truncate/)(bool) | Indica se il tipo di simbologia Pdf417 di [BarCode](../../aspose.barcode/) è troncato (per ridurre lo spazio). Conosciuto anche come CompactPDF417. L'indicatore di riga destra e il pattern di stop destro sono rimossi in questa modalità. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [Pdf417Parameters](./). |
## Osservazioni


Questi esempi mostrano come codificare le modalità non collegate UCC/EAN-128 in GS1MicroPdf417.
```cpp
[C#]
//Codifica la modalità non collegata 905 di GS1 UCC/EAN-128 con AI 01 (GTIN).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Codifica le modalità non collegate 903, 904 di GS1 UCC/EAN-128 con qualsiasi AI.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
