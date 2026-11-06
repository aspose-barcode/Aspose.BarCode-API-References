---
title: "Pdf417Parameters"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "Parametri PDF417."
type: docs
weight: 58
url: /it/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

Parametri PDF417. Contiene i parametri PDF417, MacroPDF417, MicroPDF417 e GS1MicroPdf417. MacroPDF417 richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono opzionali. MicroPDF417 in modalità Structured Append (uguale alla modalità MacroPDF417) richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono opzionali.

Questi esempi mostrano come codificare le modalità non collegate UCC/EAN-128 in GS1MicroPdf417

```

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapporto Altezza/Larghezza del modulo di codice a barre 2D. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Numero di colonne. |
| [getECIEncoding()](#getECIEncoding--) | Identificatori di Interpretazione del Canale Esteso. |
| [getEncodeMode()](#getEncodeMode--) | Identifica la modalità di codifica Pdf417. |
| [getErrorLevel()](#getErrorLevel--) | Ottiene il tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, il che comporta un'immagine più grande. |
| [getMacroCharacters()](#getMacroCharacters--) | I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Checksum del codice a barre MacroPdf417 (campo opzionale). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Identificatori di Interpretazione del Canale Esteso. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | ID file del codice a barre MacroPdf417 (campo obbligatorio). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nome file del codice a barre MacroPdf417 (campo opzionale). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Dimensione file MacroPdf417 (campo opzionale). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Conteggio segmenti del codice a barre MacroPdf417 (campo opzionale). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nome del mittente del codice a barre MacroPdf417 (campo opzionale). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Usato per indicare all'encoder se aggiungere il Macro PDF417 Terminator (codeword 922) al segmento. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Timestamp del codice a barre MacroPdf417 (campo opzionale). |
| [getRows()](#getRows--) | Numero di righe. |
| [getTruncate()](#getTruncate--) | Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, e può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128. |
| [isLinked()](#isLinked--) | Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica le modalità UCC/EAN-128 \u201cLinked\u201d 906, 907, 912, 913, 914, 915. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato, diverso da un EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapporto Altezza/Larghezza del modulo di codice a barre 2D. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, e può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128. |
| [setColumns(int value)](#setColumns-int-) | Numero di colonne. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identificatori di Interpretazione del Canale Esteso. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifica la modalità di codifica Pdf417. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Imposta il tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, il che comporta un'immagine più grande. |
| [setLinked(boolean value)](#setLinked-boolean-) | Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica le modalità UCC/EAN-128 \u201cLinked\u201d 906, 907, 912, 913, 914, 915. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato, diverso da un EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Checksum del codice a barre MacroPdf417 (campo opzionale). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Identificatori di Interpretazione del Canale Esteso. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | ID file del codice a barre MacroPdf417 (campo obbligatorio). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Nome file del codice a barre MacroPdf417 (campo opzionale). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Dimensione file MacroPdf417 (campo opzionale). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Conteggio segmenti del codice a barre MacroPdf417 (campo opzionale). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Nome del mittente del codice a barre MacroPdf417 (campo opzionale). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Usato per indicare all'encoder se aggiungere il Macro PDF417 Terminator (codeword 922) al segmento. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Timestamp del codice a barre MacroPdf417 (campo opzionale). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [setRows(int value)](#setRows-int-) | Numero di righe. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Indica se il tipo di simbologia Pdf417 del BarCode è troncato (per ridurre lo spazio). |
| [toString()](#toString--) | Restituisce una rappresentazione della stringa leggibile dall'uomo di questo [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
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


Rapporto Altezza/Larghezza del modulo di codice a barre 2D.

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


Numero di colonne.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. Non viene applicato ai campi di testo Macro PDF417. L'implementazione attuale comprende tutte le codifiche di set di caratteri conosciute.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Identifica la modalità di codifica Pdf417. Valore predefinito: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Ottiene il tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, il che comporta un'immagine più grande.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con MicroPdf417 e codificano le modalità MicroPdf417 916 e 917. Valore predefinito: MacroCharacters.None.

Questi esempi mostrano come codificare i Macro Characters in MicroPdf417

```

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

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


Identificatori di Interpretazione del Canale Esteso. Si applica ai campi di testo Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


ID file del codice a barre MacroPdf417 (campo obbligatorio). ID file del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append)

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Nome file del codice a barre MacroPdf417 (campo opzionale). Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

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


ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1. ID segmento del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append)

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Conteggio segmenti del codice a barre MacroPdf417 (campo opzionale). Conteggio segmenti del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Nome del mittente del codice a barre MacroPdf417 (campo opzionale). Nome del mittente del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Timestamp del codice a barre MacroPdf417 (campo opzionale). Timestamp del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


Numero di righe.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Indica se il tipo di simbologia Pdf417 del codice a barre è troncato (per ridurre lo spazio). Conosciuto anche come CompactPDF417. L'indicatore di riga destro e il pattern di stop destro sono rimossi in questa modalità.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, e può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128.

Questi esempi mostrano come codificare le modalità di emulazione Code 128 con FNC1 in seconda posizione e senza. In questo modo MicroPdf417 può essere decodificato come codice a barre Code 128

```

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica le modalità UCC/EAN-128 \u201cLinked\u201d 906, 907, 912, 913, 914, 915. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato, diverso da un EAN.UCC.

Questi esempi mostrano come codificare le modalità "Linked" UCC/EAN-128 in GS1MicroPdf417 e il Flag di collegamento (918) nei codici a barre MicroPdf417 e Pdf417

```

```

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


Rapporto Altezza/Larghezza del modulo di codice a barre 2D.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, e può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128.

Questi esempi mostrano come codificare le modalità di emulazione Code 128 con FNC1 in seconda posizione e senza. In questo modo MicroPdf417 può essere decodificato come codice a barre Code 128

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Numero di colonne.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. Non viene applicato ai campi di testo Macro PDF417. L'implementazione attuale comprende tutte le codifiche di set di caratteri conosciute.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Identifica la modalità di codifica Pdf417. Valore predefinito: Auto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Imposta il tipo di simbologia Pdf417 del livello di correzione errori del BarCode, che varia da level0 a level8; level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, il che comporta un'immagine più grande.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Il livello di correzione errori della simbologia Pdf417 del codice a barre varia da level0 a level8, level0 indica nessuna informazione di correzione errori, level8 indica la migliore correzione errori, che comporta un'immagine più grande. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Definisce le modalità collegate con i codici a barre GS1MicroPdf417, MicroPdf417 e Pdf417. Con la simbologia GS1MicroPdf417 codifica le modalità UCC/EAN-128 \u201cLinked\u201d 906, 907, 912, 913, 914, 915. Con le simbologie MicroPdf417 e Pdf417 codifica il flag di collegamento 918 al componente lineare associato, diverso da un EAN.UCC.

Questi esempi mostrano come codificare le modalità "Linked" UCC/EAN-128 in GS1MicroPdf417 e il Flag di collegamento (918) nei codici a barre MicroPdf417 e Pdf417

```

 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked modes 906, 907 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());
 
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con MicroPdf417 e codificano le modalità MicroPdf417 916 e 917. Valore predefinito: MacroCharacters.None.

Questi esempi mostrano come codificare i Macro Characters in MicroPdf417

```

```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Nome del destinatario del codice a barre MacroPdf417 (campo opzionale). Nome del destinatario del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

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


Identificatori di Interpretazione del Canale Esteso. Si applica ai campi di testo Macro PDF417.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


ID file del codice a barre MacroPdf417 (campo obbligatorio). ID file del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Nome file del codice a barre MacroPdf417 (campo opzionale). Nome file del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

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


ID segmento del codice a barre MacroPdf417 (campo obbligatorio), che parte da 0 fino a MacroSegmentsCount - 1. ID segmento del codice a barre MicroPDF417 (campo obbligatorio per la modalità Structured Append)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Conteggio segmenti del codice a barre MacroPdf417 (campo opzionale). Conteggio segmenti del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Nome del mittente del codice a barre MacroPdf417 (campo opzionale). Nome del mittente del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PDF417.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Timestamp del codice a barre MacroPdf417 (campo opzionale). Timestamp del codice a barre MicroPDF417 (campo opzionale per la modalità Structured Append)

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


Numero di righe.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Indica se il tipo di simbologia Pdf417 del codice a barre è troncato (per ridurre lo spazio). Conosciuto anche come CompactPDF417. L'indicatore di riga destro e il pattern di stop destro sono rimossi in questa modalità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione della stringa leggibile dall'uomo di questo [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - Una stringa che rappresenta questo [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

