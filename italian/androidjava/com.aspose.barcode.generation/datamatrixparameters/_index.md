---
title: DataMatrixParameters
second_title: Aspose.BarCode per Android via Java API Reference
description: Parametri DataMatrix.
type: docs
weight: 34
url: /it/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

Parametri DataMatrix.
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Conteggio colonne. |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | Ottiene un tipo ECC Datamatrix. |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | Ottiene una dimensione del simbolo Datamatrix. |
| [getECIEncoding()](#getECIEncoding--) | Ottiene la codifica ECI. |
| [getEccType()](#getEccType--) | Ottiene un tipo ECC Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | I valori dei Macro Caratteri 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. |
| [getRows()](#getRows--) | Conteggio delle righe. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | ID del file per la modalità Structured Append del codice a barre Datamatrix. |
| [getVersion()](#getVersion--) | Ottiene una dimensione del simbolo Datamatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [setColumns(int value)](#setColumns-int-) | Conteggio colonne. |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Imposta un tipo ECC Datamatrix. |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Imposta una dimensione del simbolo Datamatrix. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Imposta la codifica ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Imposta un tipo ECC Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | I valori dei Macro Caratteri 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [setRows(int value)](#setRows-int-) | Conteggio delle righe. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | ID del file per la modalità Structured Append del codice a barre Datamatrix. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Imposta una dimensione del simbolo Datamatrix. |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Rapporto Altezza/Larghezza del modulo BarCode 2D.

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
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


Ottiene un tipo ECC Datamatrix. Valore predefinito: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Modalità di codifica del codice a barre Datamatrix. Valore predefinito: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


Ottiene una dimensione del simbolo Datamatrix. Valore predefinito: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Ottiene la codifica ECI. Usata quando EncodeMode è Auto. Valore predefinito: ISO-8859-1.

**Returns:**
int - codifica ECI.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Ottiene un tipo ECC Datamatrix. Valore predefinito: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Modalità di codifica del codice a barre Datamatrix. Valore predefinito: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con DataMatrixEccType.Ecc200 o DataMatrixEccType.EccAuto. Non possono essere usati con EncodeTypes.GS1DataMatrix Valore predefinito: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getRows() {#getRows--}
```
public final int getRows()
```


Conteggio delle righe.

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


ID del file per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Ottiene una dimensione del simbolo Datamatrix. Valore predefinito: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


Usato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. Valore predefinito: false.

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


Rapporto Altezza/Larghezza del modulo BarCode 2D.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Conteggio colonne.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


Imposta un tipo ECC Datamatrix. Valore predefinito: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | un tipo ECC Datamatrix. |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Modalità di codifica del codice a barre Datamatrix. Valore predefinito: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


Imposta una dimensione del simbolo Datamatrix. Valore predefinito: Version.Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | una dimensione del simbolo Datamatrix. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Imposta la codifica ECI. Usata quando EncodeMode è Auto. Valore predefinito: ISO-8859-1.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int | Codifica ECI. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Imposta un tipo ECC Datamatrix. Valore predefinito: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | un tipo ECC Datamatrix. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Modalità di codifica del codice a barre Datamatrix. Valore predefinito: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con DataMatrixEccType.Ecc200 o DataMatrixEccType.EccAuto. Non possono essere usati con EncodeTypes.GS1DataMatrix Valore predefinito: MacroCharacters.None.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Usato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. Valore predefinito: false.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Conteggio delle righe.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


ID del file per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Imposta una dimensione del simbolo Datamatrix. Valore predefinito: Version.Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | una dimensione del simbolo Datamatrix. |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - Una stringa che rappresenta questo [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).
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

