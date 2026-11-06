---
title: "QrParameters"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "Parametri QR."
type: docs
weight: 62
url: /it/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

Parametri QR.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapporto Altezza/Larghezza del modulo di codice a barre 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Identificatori di Interpretazione del Canale Esteso. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) |  |
| [getEncodeMode()](#getEncodeMode--) | Tipo di simbologia QR della modalità di codifica del BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versione di MicroQR Code. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Versione di RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | Parametri di aggiunta strutturata QR. |
| [getVersion()](#getVersion--) | Versione del QR Code. Da Version1 a Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapporto Altezza/Larghezza del modulo di codice a barre 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identificatori di Interpretazione del Canale Esteso. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) |  |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Tipo di simbologia QR della modalità di codifica del BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Versione di MicroQR Code. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Versione di RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | Parametri di aggiunta strutturata QR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Versione del QR Code. Da Version1 a Version40. |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
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


Rapporto Altezza/Larghezza del modulo di codice a barre 2D.

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


Identificatori di Interpretazione del Canale Esteso. Vengono usati per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per codificare i dati nel simbolo. L'implementazione corrente comprende tutte le codifiche di set di caratteri conosciute. Non supportato da MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public final boolean getEncodeGS1SeparatorInByteMode()
```


Ottiene o imposta un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici a barre QR e RectMicroQR.

Se false, i separatori GS1 possono essere codificati come '%' in modalità Alfanumerica secondo la specifica QR.

Se true, i separatori di gruppo GS1 sono codificati in modalità Byte come carattere 0x1D, e i caratteri '%' sono anch'essi codificati in modalità Byte per preservarli come dati.

Questa opzione può migliorare la compatibilità con i decoder che si aspettano separatori di gruppo GS1 a livello byte e impedisce che i caratteri dati '%' vengano interpretati come separatori GS1.

**Returns:**
boolean - un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici a barre QR e RectMicroQR.
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Tipo di simbologia QR della modalità di codifica del BarCode. Valore predefinito: QREncodeMode.Auto.

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


Versione del MicroQR Code. Da versione M1 a versione M4. Il valore predefinito è MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Versione del RectMicroQR Code. Da versione R7x59 a versione R17x139. Il valore predefinito è RectMicroQRVersion.Auto.

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


Versione del QR Code. Da Version1 a Version40. Il valore predefinito è QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public final int hashCode()
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


Rapporto Altezza/Larghezza del modulo di codice a barre 2D.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identificatori di Interpretazione del Canale Esteso. Vengono usati per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per codificare i dati nel simbolo. L'implementazione corrente comprende tutte le codifiche di set di caratteri conosciute. Non supportato da MicroQR.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public final void setEncodeGS1SeparatorInByteMode(boolean value)
```


Ottiene o imposta un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici a barre QR e RectMicroQR.

Se false, i separatori GS1 possono essere codificati come '%' in modalità Alfanumerica secondo la specifica QR.

Se true, i separatori di gruppo GS1 sono codificati in modalità Byte come carattere 0x1D, e i caratteri '%' sono anch'essi codificati in modalità Byte per preservarli come dati.

Questa opzione può migliorare la compatibilità con i decoder che si aspettano separatori di gruppo GS1 a livello byte e impedisce che i caratteri dati '%' vengano interpretati come separatori GS1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici a barre QR e RectMicroQR. |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Tipo di simbologia QR della modalità di codifica del BarCode. Valore predefinito: QREncodeMode.Auto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. Da basso a alto: LevelL, LevelM, LevelQ, LevelH. Vedi QRErrorLevel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Versione del MicroQR Code. Da versione M1 a versione M4. Il valore predefinito è MicroQRVersion.Auto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Versione del RectMicroQR Code. Da versione R7x59 a versione R17x139. Il valore predefinito è RectMicroQRVersion.Auto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


Parametri di aggiunta strutturata QR. La modalità di aggiunta strutturata non è supportata dai codici a barre MicroQR e RectMicroQR.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Versione del QR Code. Da Version1 a Version40. Il valore predefinito è QRVersion.Auto.

**Parameters:**
| Parametro | Tipo | Descrizione |
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

