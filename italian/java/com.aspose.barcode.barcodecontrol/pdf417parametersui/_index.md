---
title: "Pdf417ParametersUI"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Wrapper UI per la classe com.aspose.barcode.generation.Pdf417Parameters."
type: docs
weight: 16
url: /it/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

Wrapper UI per la classe com.aspose.barcode.generation.Pdf417Parameters.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapporto altezza/larghezza del modulo 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Conteggio colonne. |
| [getECIEncoding()](#getECIEncoding--) | Identificatori di Interpretazione del Canale Esteso. |
| [getEncodeMode()](#getEncodeMode--) | Tipo di simbologia Pdf417 della modalità di codifica del BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Restituisce il tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, che comporta un'immagine più grande. |
| [getMacroCharacters()](#getMacroCharacters--) | I valori dei Macro Caratteri 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Checksum del codice a barre MacroPdf417 (campo opzionale). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Identificatori di Interpretazione del Canale Esteso. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Restituisce l'ID file del codice a barre macro Pdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nome file del codice a barre MacroPdf417 (campo opzionale). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Dimensione file MacroPdf417 (campo opzionale). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Restituisce l'ID segmento del codice a barre macro Pdf417, che parte da 0, fino a MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Restituisce il conteggio dei segmenti del codice a barre macro Pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nome del mittente del codice a barre MacroPdf417 (campo opzionale). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Usato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Marca temporale del codice a barre MacroPdf417 (campo opzionale). |
| [getRows()](#getRows--) | Conteggio righe. |
| [getTruncate()](#getTruncate--) | Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128. |
| [isLinked()](#isLinked--) | Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica i modi 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato, diverso da un EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapporto altezza/larghezza del modulo 2D BarCode. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128. |
| [setColumns(int value)](#setColumns-int-) | Conteggio colonne. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identificatori di Interpretazione del Canale Esteso. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Tipo di simbologia Pdf417 della modalità di codifica del BarCode. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Imposta il tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, che comporta un'immagine più grande. |
| [setLinked(boolean value)](#setLinked-boolean-) | Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica i modi 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato, diverso da un EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | I valori dei Macro Caratteri 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Checksum del codice a barre MacroPdf417 (campo opzionale). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Identificatori di Interpretazione del Canale Esteso. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Imposta l'ID file del codice a barre macro Pdf417. |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Nome file del codice a barre MacroPdf417 (campo opzionale). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Dimensione file MacroPdf417 (campo opzionale). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Imposta l'ID segmento del codice a barre macro Pdf417, che parte da 0, fino a MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Imposta il conteggio dei segmenti del codice a barre macro Pdf417. |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Nome del mittente del codice a barre MacroPdf417 (campo opzionale). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Usato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Marca temporale del codice a barre MacroPdf417 (campo opzionale). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [setRows(int value)](#setRows-int-) | Conteggio righe. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio). |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Rapporto altezza/larghezza del modulo 2D BarCode.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Conteggio colonne.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identificatori di Interpretazione del Canale Esteso. Vengono utilizzati per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. Non applicati ai campi di testo Macro PDF417. L'implementazione corrente comprende tutte le codifiche di set di caratteri conosciute.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Tipo di simbologia Pdf417 della modalità di codifica del BarCode. Valore predefinito: Pdf417EncodeMode.Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Restituisce il tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, che comporta un'immagine più grande.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con MicroPdf417 e codificano le modalità MicroPdf417 916 e 917. Valore predefinito: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


Checksum del codice a barre MacroPdf417 (campo opzionale). Checksum del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo checksum contiene il valore del checksum CRC a 16 bit (2 byte) usando il polinomio CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Identificatori di Interpretazione del Canale Esteso. Si applicano ai campi di testo Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


Ottiene l'ID file del codice a barre macro Pdf417. Usato per MacroPdf417.

**Returns:**
int - ID file del codice a barre macro Pdf417.
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Nome file del codice a barre MacroPdf417 (campo opzionale). Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


Dimensione file MacroPdf417 (campo opzionale). Dimensione file MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo dimensione file contiene la dimensione in byte dell'intero file sorgente.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


Restituisce l'ID segmento del codice a barre macro Pdf417, che parte da 0, fino a MacroSegmentsCount - 1.

**Returns:**
int - ID segmento del codice a barre macro Pdf417, che parte da 0 fino a MacroSegmentsCount - 1.
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Restituisce il conteggio dei segmenti del codice a barre macro Pdf417.

**Returns:**
int - conteggio dei segmenti del codice a barre macro Pdf417.
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Nome del mittente del codice a barre MacroPdf417 (campo opzionale). Nome del mittente del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Usato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Timestamp del codice a barre MacroPdf417 (campo opzionale). Timestamp del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


Conteggio righe.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio).

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128.

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica i modi 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato, diverso da un EAN.UCC.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Rapporto altezza/larghezza del modulo 2D BarCode.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Conteggio colonne.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identificatori di Interpretazione del Canale Esteso. Vengono utilizzati per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. Non applicati ai campi di testo Macro PDF417. L'implementazione corrente comprende tutte le codifiche di set di caratteri conosciute.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Tipo di simbologia Pdf417 della modalità di codifica del BarCode. Valore predefinito: Pdf417EncodeMode.Auto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Imposta il tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, che comporta un'immagine più grande.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8; level0 significa nessuna informazione di correzione errori, level8 indica la migliore correzione errori, che comporta un'immagine più grande. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica i modi 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato, diverso da un EAN.UCC.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con MicroPdf417 e codificano le modalità MicroPdf417 916 e 917. Valore predefinito: MacroCharacters.None.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Checksum del codice a barre MacroPdf417 (campo opzionale). Checksum del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo checksum contiene il valore del checksum CRC a 16 bit (2 byte) usando il polinomio CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Identificatori di Interpretazione del Canale Esteso. Si applicano ai campi di testo Macro PDF417.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


Imposta l'ID file del codice a barre macro Pdf417. Usato per MacroPdf417.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | ID file del codice a barre macro Pdf417. |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Nome file del codice a barre MacroPdf417 (campo opzionale). Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


Dimensione file MacroPdf417 (campo opzionale). Dimensione file MicroPDF417 (campo opzionale per la modalità Structured Append). Il campo dimensione file contiene la dimensione in byte dell'intero file sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


Imposta l'ID segmento del codice a barre macro Pdf417, che parte da 0, fino a MacroSegmentsCount - 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | ID segmento del codice a barre macro Pdf417, che parte da 0 fino a MacroSegmentsCount - 1. |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Imposta il conteggio dei segmenti del codice a barre macro Pdf417.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Conteggio dei segmenti del codice a barre macro Pdf417. |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Nome del mittente del codice a barre MacroPdf417 (campo opzionale). Nome del mittente del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Usato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PDF417.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Timestamp del codice a barre MacroPdf417 (campo opzionale). Timestamp del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Conteggio righe.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - Una stringa che rappresenta questo [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

