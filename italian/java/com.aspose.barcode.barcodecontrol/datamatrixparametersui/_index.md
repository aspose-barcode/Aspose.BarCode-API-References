---
title: "DataMatrixParametersUI"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Wrapper UI per la classe com.aspose.barcode.generation.DataMatrixParameters."
type: docs
weight: 14
url: /it/java/com.aspose.barcode.barcodecontrol/datamatrixparametersui/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParametersUI
```

Wrapper UI per la classe com.aspose.barcode.generation.DataMatrixParameters.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapporto altezza/larghezza del modulo 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Ottiene la codifica ECI. |
| [getEccType()](#getEccType--) | Ottiene un tipo ECC Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | Modalità di codifica del codice a barre Datamatrix. |
| [getMacroCharacters()](#getMacroCharacters--) | Protocollo per i caratteri Macro nella prima posizione (solo ECC 200). |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | ID del codice a barre per la modalità Structured Append. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Conteggio dei codici a barre per la modalità Structured Append. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | ID file per la modalità Structured Append. |
| [getVersion()](#getVersion--) | Dimensione del simbolo DataMatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapporto altezza/larghezza del modulo 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Imposta la codifica ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Imposta un tipo ECC Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Modalità di codifica del codice a barre Datamatrix. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Protocollo per i caratteri Macro nella prima posizione (solo ECC 200). |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | ID del codice a barre per la modalità Structured Append. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Conteggio dei codici a barre per la modalità Structured Append. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | ID file per la modalità Structured Append. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Dimensione del simbolo DataMatrix. |
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


Ottiene la codifica ECI. Utilizzato quando EncodeMode è Auto.

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


Protocollo per i caratteri Macro nella prima posizione (solo ECC 200).

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


ID del codice a barre per la modalità Structured Append.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Conteggio dei codici a barre per la modalità Structured Append.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


ID file per la modalità Structured Append.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Dimensione del simbolo DataMatrix.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion)
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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Imposta la codifica ECI. Utilizzato quando EncodeMode è Auto.

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


Protocollo per i caratteri Macro nella prima posizione (solo ECC 200).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


ID del codice a barre per la modalità Structured Append.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Conteggio dei codici a barre per la modalità Structured Append.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


ID file per la modalità Structured Append.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Dimensione del simbolo DataMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) |  |

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

