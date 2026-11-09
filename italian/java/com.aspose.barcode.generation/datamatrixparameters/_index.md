---
title: "DataMatrixParameters"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Parametri DataMatrix."
type: docs
weight: 32
url: /it/java/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

Parametri DataMatrix.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapporto altezza/larghezza del modulo 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Ottiene la codifica ECI. |
| [getEccType()](#getEccType--) | Ottiene un tipo ECC Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | Modalità di codifica del codice a barre Datamatrix. |
| [getMacroCharacters()](#getMacroCharacters--) | I valori dei Macro Caratteri 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | ID file per la modalità Structured Append del codice a barre Datamatrix. |
| [getVersion()](#getVersion--) | Ottiene una dimensione del simbolo Datamatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapporto altezza/larghezza del modulo 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Imposta la codifica ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Imposta un tipo ECC Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Modalità di codifica del codice a barre Datamatrix. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | I valori dei Macro Caratteri 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | ID file per la modalità Structured Append del codice a barre Datamatrix. |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Ottiene la codifica ECI. Utilizzata quando EncodeMode è Auto. Valore predefinito: ISO-8859-1

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
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


ID file per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0

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
public final int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. Valore predefinito: false

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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Imposta la codifica ECI. Utilizzata quando EncodeMode è Auto. Valore predefinito: ISO-8859-1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Codifica ECI. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Imposta un tipo ECC Datamatrix. Valore predefinito: DataMatrixEccType.Ecc200.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | un tipo ECC Datamatrix. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Modalità di codifica del codice a barre Datamatrix. Valore predefinito: EncodeMode.Auto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con DataMatrixEccType.Ecc200 o DataMatrixEccType.EccAuto. Non possono essere usati con EncodeTypes.GS1DataMatrix Valore predefinito: MacroCharacters.None.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. Valore predefinito: false

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


ID file per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Imposta una dimensione del simbolo Datamatrix. Valore predefinito: Version.Auto.

**Parameters:**
| Parametro | Tipo | Descrizione |
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

