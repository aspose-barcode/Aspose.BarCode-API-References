---
title: QrParameters
second_title: Aspose.BarCode per Android via Java API Reference
description: Parametri QR.
type: docs
weight: 64
url: /it/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

Parametri QR.
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Identificatori di Interpretazione del Canale Esteso. |
| [getEncodeMode()](#getEncodeMode--) | Tipo di simbologia QR della modalità di codifica del codice a barre. |
| [getErrorLevel()](#getErrorLevel--) | Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versione di MicroQR Code. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Identificatori di Interpretazione del Canale Esteso. |
| [getQrEncodeMode()](#getQrEncodeMode--) | Tipo di simbologia QR della modalità di codifica del codice a barre. |
| [getQrEncodeType()](#getQrEncodeType--) | Modalità selettore QR / MicroQR. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. |
| [getQrVersion()](#getQrVersion--) | Versione del codice QR. Da Versione1 a Versione40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Versione di RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | Parametri di aggiunta strutturata QR. |
| [getVersion()](#getVersion--) | Versione del codice QR. Da Versione1 a Versione40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identificatori di Interpretazione del Canale Esteso. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Tipo di simbologia QR della modalità di codifica del codice a barre. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Versione di MicroQR Code. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | Modalità selettore QR / MicroQR. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Versione di RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | Parametri di aggiunta strutturata QR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Versione del codice QR. Da Versione1 a Versione40. |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
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


Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione corrente comprende tutte le codifiche di set di caratteri conosciute. Non supportato da MicroQR.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Tipo di simbologia QR della modalità di codifica del codice a barre. Valore predefinito: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. Da basso a alto: LevelL, LevelM, LevelQ, LevelH. Vedi QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Versione del codice MicroQR. Dalla versione M1 alla versione M4. Il valore predefinito è MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione corrente comprende tutte le codifiche di set di caratteri conosciute. Non supportato da MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


Tipo di simbologia QR della modalità di codifica del codice a barre. Valore predefinito: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


Modalità di selezione QR / MicroQR. Seleziona ForceQR per i simboli QR standard, Auto per MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. Da basso a alto: LevelL, LevelM, LevelQ, LevelH. Vedi QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


Versione del codice QR. Dalla Versione1 alla Versione40. Il valore predefinito è QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Versione del codice RectMicroQR. Dalla versione R7x59 alla versione R17x139. Il valore predefinito è RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


Parametri di aggiunta strutturata QR. La modalità di aggiunta strutturata non è supportata dai codici a barre MicroQR e RectMicroQR.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versione del codice QR. Dalla Versione1 alla Versione40. Il valore predefinito è QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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


Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione corrente comprende tutte le codifiche di set di caratteri conosciute. Non supportato da MicroQR.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Tipo di simbologia QR della modalità di codifica del codice a barre. Valore predefinito: QREncodeMode.Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. Da basso a alto: LevelL, LevelM, LevelQ, LevelH. Vedi QRErrorLevel.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Versione del codice MicroQR. Dalla versione M1 alla versione M4. Il valore predefinito è MicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


Modalità di selezione QR / MicroQR. Seleziona ForceQR per i simboli QR standard, Auto per MicroQR.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Versione del codice RectMicroQR. Dalla versione R7x59 alla versione R17x139. Il valore predefinito è RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


Parametri di aggiunta strutturata QR. La modalità di aggiunta strutturata non è supportata dai codici a barre MicroQR e RectMicroQR.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Versione del codice QR. Dalla Versione1 alla Versione40. Il valore predefinito è QRVersion.Auto.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - Una stringa che rappresenta questo [QrParameters](../../com.aspose.barcode.generation/qrparameters).
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

