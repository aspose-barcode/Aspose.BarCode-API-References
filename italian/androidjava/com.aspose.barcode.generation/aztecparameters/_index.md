---
title: AztecParameters
second_title: Aspose.BarCode per Android via Java API Reference
description: Parametri Aztec.
type: docs
weight: 12
url: /it/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Parametri Aztec.
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | Ottiene una modalità di codifica Aztec. |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | Livello di correzione degli errori dei tipi di codice a barre Aztec. |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | Ottiene una modalità di simbolo Aztec. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Ottiene la codifica ECI. |
| [getEncodeMode()](#getEncodeMode--) | Ottiene una modalità di codifica Aztec. |
| [getErrorLevel()](#getErrorLevel--) | Livello di correzione degli errori dei tipi di codice a barre Aztec. |
| [getLayersCount()](#getLayersCount--) | Ottiene il conteggio dei livelli del simbolo Aztec. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | ID del codice a barre per la modalità Structured Append del codice a barre Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Conteggio dei codici a barre per la modalità Structured Append del codice a barre Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | ID del file per la modalità Structured Append del codice a barre Aztec (campo opzionale). |
| [getSymbolMode()](#getSymbolMode--) | Ottiene una modalità di simbolo Aztec. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Imposta una modalità di codifica Aztec. |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | Livello di correzione degli errori dei tipi di codice a barre Aztec. |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Imposta una modalità di simbolo Aztec. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Imposta la codifica ECI. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Imposta una modalità di codifica Aztec. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Livello di correzione degli errori dei tipi di codice a barre Aztec. |
| [setLayersCount(int value)](#setLayersCount-int-) | Imposta il conteggio dei livelli del simbolo Aztec. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | ID del codice a barre per la modalità Structured Append del codice a barre Aztec. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Conteggio dei codici a barre per la modalità Structured Append del codice a barre Aztec. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | ID del file per la modalità Structured Append del codice a barre Aztec (campo opzionale). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Imposta una modalità di simbolo Aztec. |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public final AztecEncodeMode getAztecEncodeMode()
```


Ottiene una modalità di codifica Aztec. Valore predefinito: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - una modalità di codifica Aztec.
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public final int getAztecErrorLevel()
```


Livello di correzione degli errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere compreso tra 5 e 95.

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public final AztecSymbolMode getAztecSymbolMode()
```


Ottiene una modalità di simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
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


Ottiene la codifica ECI. Utilizzata quando AztecEncodeMode è Auto. Valore predefinito: ISO-8859-1

**Returns:**
int - codifica ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Ottiene una modalità di codifica Aztec. Valore predefinito: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - una modalità di codifica Aztec.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Livello di correzione degli errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere compreso tra 5 e 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Ottiene il conteggio dei livelli del simbolo Aztec. Il conteggio dei livelli dovrebbe essere nell'intervallo da 1 a 3 per la modalità Compact e da 1 a 32 per la modalità Full Range. Valore predefinito: 0 (auto).

**Returns:**
int - conteggio dei livelli del simbolo Aztec.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


ID del codice a barre per la modalità Structured Append del codice a barre Aztec. L'ID del codice a barre dovrebbe essere nell'intervallo da 1 al conteggio dei codici a barre. Valore predefinito: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Conteggio dei codici a barre per la modalità Structured Append del codice a barre Aztec. Il conteggio dei codici a barre dovrebbe essere nell'intervallo da 1 a 26. Valore predefinito: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


ID del file per la modalità Structured Append del codice a barre Aztec (campo opzionale). L'ID del file non dovrebbe contenere spazi. Valore predefinito: stringa vuota

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Ottiene una modalità di simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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


Rapporto Altezza/Larghezza del modulo BarCode 2D.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setAztecEncodeMode(AztecEncodeMode value)
```


Imposta una modalità di codifica Aztec. Valore predefinito: Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | com.aspose.barcode.generation.AztecEncodeMode | una modalità di codifica Aztec. |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public final void setAztecErrorLevel(int value)
```


Livello di correzione degli errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere compreso tra 5 e 95.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setAztecSymbolMode(AztecSymbolMode value)
```


Imposta una modalità di simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | una modalità di simbolo Aztec. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Imposta la codifica ECI. Utilizzata quando AztecEncodeMode è Auto. Valore predefinito: ISO-8859-1

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int | Codifica ECI. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Imposta una modalità di codifica Aztec. Valore predefinito: Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | com.aspose.barcode.generation.AztecEncodeMode | una modalità di codifica Aztec. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Livello di correzione degli errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere compreso tra 5 e 95.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Imposta il conteggio dei livelli del simbolo Aztec. Il conteggio dei livelli dovrebbe essere nell'intervallo da 1 a 3 per la modalità Compact e da 1 a 32 per la modalità Full Range. Valore predefinito: 0 (auto).

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int | conteggio dei livelli del simbolo Aztec. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


ID del codice a barre per la modalità Structured Append del codice a barre Aztec. L'ID del codice a barre dovrebbe essere nell'intervallo da 1 al conteggio dei codici a barre. Valore predefinito: 0

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Conteggio dei codici a barre per la modalità Structured Append del codice a barre Aztec. Il conteggio dei codici a barre dovrebbe essere nell'intervallo da 1 a 26. Valore predefinito: 0

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


ID del file per la modalità Structured Append del codice a barre Aztec (campo opzionale). L'ID del file non dovrebbe contenere spazi. Valore predefinito: stringa vuota

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Imposta una modalità di simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | una modalità di simbolo Aztec. |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - Una stringa che rappresenta questo [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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

