---
title: "DotCodeParameters"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Parametri DotCode."
type: docs
weight: 34
url: /it/java/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

Parametri DotCode.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapporto altezza/larghezza del modulo 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identifica il numero di colonne. |
| [getECIEncoding()](#getECIEncoding--) | Identifica la codifica ECI. |
| [getEncodeMode()](#getEncodeMode--) | Identifica la modalità di codifica DotCode. |
| [getRows()](#getRows--) | Identifica il numero di righe. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identifica l'ID del codice a barre in modalità di aggiunta strutturata DotCode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identifica il conteggio dei codici a barre in modalità di aggiunta strutturata DotCode. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapporto altezza/larghezza del modulo 2D BarCode. |
| [setColumns(int value)](#setColumns-int-) | Identifica il numero di colonne. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifica la codifica ECI. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifica la modalità di codifica DotCode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. |
| [setRows(int value)](#setRows-int-) | Identifica il numero di righe. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Identifica l'ID del codice a barre in modalità di aggiunta strutturata DotCode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Identifica il conteggio dei codici a barre in modalità di aggiunta strutturata DotCode. |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
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


Identifica il numero di colonne. La somma del numero di righe più il numero di colonne di un simbolo DotCode deve essere dispari. Il numero di colonne deve essere almeno 5. Valore predefinito: -1

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifica la codifica ECI. Utilizzata quando DotCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


Identifica la modalità di codifica DotCode. Valore predefinito: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Identifica il numero di righe. La somma del numero di righe più il numero di colonne di un simbolo DotCode deve essere dispari. Il numero di righe deve essere almeno 5. Valore predefinito: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Identifica l'ID del codice a barre in modalità di aggiunta strutturata DotCode. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Identifica il conteggio dei codici a barre in modalità di aggiunta strutturata DotCode. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35.

**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Rapporto altezza/larghezza del modulo 2D BarCode.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Identifica il numero di colonne. La somma del numero di righe più il numero di colonne di un simbolo DotCode deve essere dispari. Il numero di colonne deve essere almeno 5. Valore predefinito: -1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifica la codifica ECI. Utilizzata quando DotCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Identifica la modalità di codifica DotCode. Valore predefinito: Auto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Identifica il numero di righe. La somma del numero di righe più il numero di colonne di un simbolo DotCode deve essere dispari. Il numero di righe deve essere almeno 5. Valore predefinito: -1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Identifica l'ID del codice a barre in modalità di aggiunta strutturata DotCode. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Identifica il conteggio dei codici a barre in modalità di aggiunta strutturata DotCode. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

**Returns:**
java.lang.String - Una stringa che rappresenta questo [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).
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

