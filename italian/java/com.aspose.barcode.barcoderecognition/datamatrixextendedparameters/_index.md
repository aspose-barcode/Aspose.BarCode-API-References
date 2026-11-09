---
title: "DataMatrixExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Memorizza dati speciali del codice a barre DataMatrix riconosciuto"
type: docs
weight: 29
url: /it/java/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

Memorizza dati speciali del codice a barre DataMatrix riconosciuto

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming));
>  }
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore DataMatrixExtendedParameters specificato. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Ottiene l'ID del codice a barra DataMatrix in modalità structured append. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Ottiene il conteggio dei codici a barre in modalità di aggiunta strutturata DataMatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Ottiene l'ID del codice a barra DataMatrix in modalità structured append. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isEmpty--) | Verifica se tutti i parametri hanno solo valori predefiniti |
| [isReaderProgramming()](#isReaderProgramming--) | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo DataMatrixExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore DataMatrixExtendedParameters specificato.

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
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


Ottiene l'ID del codice a barre in modalità di aggiunta strutturata DataMatrix. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1.

Valore: L'ID del codice a barre in modalità di aggiunta strutturata DataMatrix.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Ottiene il conteggio dei codici a barre in modalità di aggiunta strutturata DataMatrix. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35.

Valore: Il conteggio del codice a barre in modalità di aggiunta strutturata DataMatrix.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


Ottiene l'ID del codice a barre in modalità di aggiunta strutturata DataMatrix. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1.

Valore: L'ID del codice a barre in modalità di aggiunta strutturata DataMatrix.

**Returns:**
int
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
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
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


Restituisce una rappresentazione stringa leggibile dall'uomo di questo DataMatrixExtendedParameters.

**Returns:**
java.lang.String - Una stringa che rappresenta questo DataMatrixExtendedParameters.
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

