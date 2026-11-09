---
title: "DotCodeExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Memorizza dati speciali del codice a barre DotCode riconosciuto"
type: docs
weight: 31
url: /it/java/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

Memorizza dati speciali del codice a barre DotCode riconosciuto

Questo esempio mostra come ottenere i valori grezzi di DotCode

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");
 
 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) specificato. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Ottiene l'ID del codice a barre DotCode in modalità di aggiunta strutturata. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Ottiene il conteggio dei codici a barre DotCode in modalità di aggiunta strutturata. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isEmpty--) | Verifica se tutti i parametri hanno solo valori predefiniti |
| [isReaderInitialization()](#isReaderInitialization--) | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
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
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Ottiene l'ID del codice a barre DotCode in modalità di aggiunta strutturata. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1.

Valore: L'ID del codice a barre DotCode in modalità di aggiunta strutturata.

**Returns:**
int - l'ID del codice a barre DotCode in modalità di aggiunta strutturata.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Ottiene il conteggio dei codici a barre DotCode in modalità di aggiunta strutturata. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35.

Valore: il conteggio del codice a barre in modalità di aggiunta strutturata DotCode.

**Returns:**
int - il conteggio dei codici a barre in modalità di aggiunta strutturata DotCode.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

**Returns:**
int - Un codice hash intero con segno a 32 bit.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Verifica se tutti i parametri hanno solo valori predefiniti

Valore: Restituisce **true** se tutti i parametri hanno solo valori predefiniti; altrimenti, **false**.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false.

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


Restituisce una rappresentazione stringa leggibile dall'uomo di questo [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - Una stringa che rappresenta questo [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).
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

