---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode per Android via Java API Reference
description: Memorizza informazioni di metadati MacroPdf417 del codice a barre riconosciuto
type: docs
weight: 40
url: /it/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Memorizza informazioni di metadati MacroPdf417 del codice a barre riconosciuto

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di Pdf417ExtendedParameters. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nome del destinatario Macro PDF417 (opzionale). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Checksum Macro PDF417 (opzionale). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Ottiene l'ID file del codice a barre, disponibile solo con MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nome file Macro PDF417 (opzionale). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Dimensione file Macro PDF417 (opzionale). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Ottiene l'ID segmento del codice a barre, disponibile solo con MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Ottiene il conteggio dei segmenti del codice a barre macro pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nome del mittente Macro PDF417 (opzionale). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Indica se il segmento è l'ultimo segmento di un file Macro PDF417. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Marca temporale Macro PDF417 (opzionale). |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [isCode128Emulation()](#isCode128Emulation--) | Flag che indica che il codice a barre MicroPdf417 è codificato con parole codice di emulazione Code 128 908, 909, 910 o 911. |
| [isEmpty()](#isEmpty--) | Verifica se tutti i parametri hanno solo i valori predefiniti |
| [isLinked()](#isLinked--) | Flag che indica che il codice a barre deve essere collegato a un codice a barre 1D. |
| [isReaderInitialization()](#isReaderInitialization--) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo Pdf417ExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore specificato di Pdf417ExtendedParameters.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore System.Object da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Nome del destinatario Macro PDF417 (opzionale).

**Returns:**
java.lang.String - Nome del destinatario.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Checksum Macro PDF417 (opzionale).

**Returns:**
int - Checksum.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Ottiene l'ID file del codice a barre, disponibile solo con MacroPdf417.

Valore: L'ID file per MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Nome file Macro PDF417 (opzionale).

**Returns:**
java.lang.String - Nome file.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Dimensione file Macro PDF417 (opzionale).

**Returns:**
int - Dimensione file.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Ottiene l'ID segmento del codice a barre, disponibile solo con MacroPdf417.

Valore: L'ID segmento del codice a barre.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Ottiene il conteggio dei segmenti del codice a barre macro pdf417. Il valore predefinito è -1.

Valore: Conteggio segmenti.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Nome del mittente Macro PDF417 (opzionale).

**Returns:**
java.lang.String - Nome mittente
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Indica se il segmento è l'ultimo segmento di un file Macro PDF417.

**Returns:**
boolean - Terminatore.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Marca temporale Macro PDF417 (opzionale).

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

**Returns:**
int - Un codice hash intero con segno a 32 bit.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Flag che indica che il codice a barre MicroPdf417 è codificato con parole codice di emulazione Code 128 908, 909, 910 o 911.

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Verifica se tutti i parametri hanno solo i valori predefiniti

Valore: Restituisce  **true**  se tutti i parametri hanno solo valori predefiniti; altrimenti,  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Flag che indica che il codice a barre deve essere collegato a un codice a barre 1D.

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore.

Value: Reader initialization flag

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




### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo Pdf417ExtendedParameters.

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

