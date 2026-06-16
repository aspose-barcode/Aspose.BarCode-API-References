---
title: MaxiCodeParameters
second_title: Aspose.BarCode per Android via Java API Reference
description: Parametri MaxiCode.
type: docs
weight: 57
url: /it/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

Parametri MaxiCode.
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Ottiene la codifica ECI. |
| [getEncodeMode()](#getEncodeMode--) | Ottiene una modalità di codifica MaxiCode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Ottiene una modalità di codifica MaxiCode. |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | Ottiene una modalità di codifica MaxiCode. |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | Ottiene un ID di codice a barre MaxiCode in modalità di aggiunta strutturata. |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | Ottiene il conteggio dei codici a barre MaxiCode in modalità di aggiunta strutturata. |
| [getMode()](#getMode--) | Ottiene una modalità di codifica MaxiCode. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Ottiene un ID di codice a barre MaxiCode in modalità di aggiunta strutturata. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Ottiene il conteggio dei codici a barre MaxiCode in modalità di aggiunta strutturata. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Imposta la codifica ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Imposta una modalità di codifica MaxiCode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Imposta una modalità di codifica MaxiCode. |
| [setMaxiCodeMode(int value)](#setMaxiCodeMode-int-) | Imposta una modalità di codifica MaxiCode. |
| [setMaxiCodeStructuredAppendModeBarcodeId(int value)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | Imposta un ID di codice a barre MaxiCode in modalità di aggiunta strutturata. |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int value)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | Imposta il conteggio dei codici a barre MaxiCode in modalità di aggiunta strutturata. |
| [setMode(int value)](#setMode-int-) | Imposta una modalità di codifica MaxiCode. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Imposta un ID di codice a barre MaxiCode in modalità di aggiunta strutturata. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Imposta il conteggio dei codici a barre MaxiCode in modalità di aggiunta strutturata. |
| [toString()](#toString--) | Restituisce una rappresentazione della stringa leggibile dall'uomo di questo [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Ottiene la codifica ECI. Usato quando MaxiCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1

**Returns:**
int - codifica ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Ottiene una modalità di codifica MaxiCode. Valore predefinito: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Ottiene una modalità di codifica MaxiCode. Valore predefinito: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public final int getMaxiCodeMode()
```


Ottiene una modalità di codifica MaxiCode.

**Returns:**
int - una modalità di codifica MaxiCode.
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public final int getMaxiCodeStructuredAppendModeBarcodeId()
```


Ottiene un ID di codice a barre MaxiCode in modalità di aggiunta strutturata. L'ID deve essere un valore compreso tra 1 e 8. Valore predefinito: 0

**Returns:**
int - un ID di codice a barre MaxiCode in modalità di aggiunta strutturata.
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public final int getMaxiCodeStructuredAppendModeBarcodesCount()
```


Ottiene il conteggio dei codici a barre MaxiCode in modalità di aggiunta strutturata. Il numero di conteggio deve essere un valore compreso tra 2 e 8 (conteggio massimo dei codici a barre). Valore predefinito: -1

**Returns:**
int - un conteggio dei codici a barre MaxiCode in modalità di aggiunta strutturata.
### getMode() {#getMode--}
```
public final int getMode()
```


Ottiene una modalità di codifica MaxiCode.

**Returns:**
int - una modalità di codifica MaxiCode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Ottiene un ID di codice a barre MaxiCode in modalità di aggiunta strutturata. L'ID deve essere un valore compreso tra 1 e 8. Valore predefinito: 0

**Returns:**
int - un ID di codice a barre MaxiCode in modalità di aggiunta strutturata.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Ottiene il conteggio dei codici a barre MaxiCode in modalità di aggiunta strutturata. Il numero di conteggio deve essere un valore compreso tra 2 e 8 (conteggio massimo dei codici a barre). Valore predefinito: -1

**Returns:**
int - un conteggio dei codici a barre MaxiCode in modalità di aggiunta strutturata.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Imposta la codifica ECI. Usata quando MaxiCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int | Codifica ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Imposta una modalità di codifica MaxiCode. Valore predefinito: Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | una modalità di codifica MaxiCode. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Imposta una modalità di codifica MaxiCode. Valore predefinito: Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | una modalità di codifica MaxiCode. |

### setMaxiCodeMode(int value) {#setMaxiCodeMode-int-}
```
public final void setMaxiCodeMode(int value)
```


Imposta una modalità di codifica MaxiCode.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int | una modalità di codifica MaxiCode. |

### setMaxiCodeStructuredAppendModeBarcodeId(int value) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodeId(int value)
```


Imposta un ID di codice a barre MaxiCode in modalità di aggiunta strutturata. L'ID deve essere un valore compreso tra 1 e 8. Valore predefinito: 0

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int | un ID di codice a barre MaxiCode in modalità di aggiunta strutturata. |

### setMaxiCodeStructuredAppendModeBarcodesCount(int value) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodesCount(int value)
```


Imposta il conteggio dei codici a barre MaxiCode in modalità di aggiunta strutturata. Il numero di conteggio deve essere un valore compreso tra 2 e 8 (conteggio massimo dei codici a barre). Valore predefinito: -1

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int | un conteggio di codici a barre MaxiCode in modalità di aggiunta strutturata. |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Imposta una modalità di codifica MaxiCode.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int | una modalità di codifica MaxiCode. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Imposta un ID di codice a barre MaxiCode in modalità di aggiunta strutturata. L'ID deve essere un valore compreso tra 1 e 8. Valore predefinito: 0

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int | un ID di codice a barre MaxiCode in modalità di aggiunta strutturata. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Imposta il conteggio dei codici a barre MaxiCode in modalità di aggiunta strutturata. Il numero di conteggio deve essere un valore compreso tra 2 e 8 (conteggio massimo dei codici a barre). Valore predefinito: -1

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int | un conteggio di codici a barre MaxiCode in modalità di aggiunta strutturata. |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione della stringa leggibile dall'uomo di questo [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String - Una stringa che rappresenta questo [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).
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

