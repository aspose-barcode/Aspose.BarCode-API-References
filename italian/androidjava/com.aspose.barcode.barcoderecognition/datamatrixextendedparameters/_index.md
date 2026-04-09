---
title: DataMatrixExtendedParameters
second_title: Aspose.BarCode per Android via Java API Reference
description: Memorizza dati speciali del codice a barre DataMatrix riconosciuto
type: docs
weight: 31
url: /it/androidjava/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
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
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming)_);
>  }
> ```
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore DataMatrixExtendedParameters specificato. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Ottiene l'ID del codice a barre DataMatrix in modalità structured append. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Ottiene il conteggio dei codici a barre in modalità di aggiunta strutturata DataMatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Ottiene l'ID del codice a barre DataMatrix in modalità structured append. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isEmpty--) | Verifica se tutti i parametri hanno solo i valori predefiniti |
| [isReaderProgramming()](#isReaderProgramming--) | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | Restituisce un valore che indica se il primo valore DataMatrixExtendedParameters è uguale al secondo. |
| [op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | Restituisce un valore che indica se il primo valore DataMatrixExtendedParameters è diverso dal secondo. |
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


Verifica se tutti i parametri hanno solo i valori predefiniti

Valore: Restituisce  **true**  se tutti i parametri hanno solo valori predefiniti; altrimenti,  **false** .

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




### op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


Restituisce un valore che indica se il primo valore DataMatrixExtendedParameters è uguale al secondo.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Un primo valore confrontato |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Un secondo valore confrontato |

**Returns:**
boolean -  **true**  se il primo ha lo stesso valore del secondo; altrimenti,  **false** .
### op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


Restituisce un valore che indica se il primo valore DataMatrixExtendedParameters è diverso dal secondo.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Un primo valore confrontato |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Un secondo valore confrontato |

**Returns:**
boolean -  **true**  se il primo ha un valore diverso dal secondo; altrimenti,  **false** .
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

