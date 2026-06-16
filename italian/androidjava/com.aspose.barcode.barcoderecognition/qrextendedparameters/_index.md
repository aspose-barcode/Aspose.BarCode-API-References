---
title: QRExtendedParameters
second_title: Aspose.BarCode per Android via Java API Reference
description: Memorizza informazioni QR Structured Append del codice a barre riconosciuto
type: docs
weight: 42
url: /it/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Memorizza informazioni QR Structured Append del codice a barre riconosciuto

Questo esempio mostra come ottenere i dati QR Structured Append

```
{
```
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Livello di correzione errori Reed-Solomon del codice a barre riconosciuto. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versione del MicroQR Code riconosciuto. |
| [getQRErrorLevel()](#getQRErrorLevel--) | Livello di correzione errori Reed-Solomon del codice a barre riconosciuto. |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | Ottiene l'indice del codice a barre in modalità QR structured append. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | Ottiene la quantità di codici a barre in modalità QR structured append. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | Ottiene i dati di parità della modalità di aggiunta strutturata QR. |
| [getQRVersion()](#getQRVersion--) | Versione del QR Code riconosciuto. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Versione del RectMicroQR Code riconosciuto. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Ottiene l'indice del codice a barre in modalità QR structured append. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Ottiene la quantità di codici a barre in modalità QR structured append. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Ottiene i dati di parità della modalità di aggiunta strutturata QR. |
| [getVersion()](#getVersion--) | Versione del QR Code riconosciuto. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isEmpty--) | Verifica se tutti i parametri hanno solo i valori predefiniti |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Restituisce un valore che indica se il valore del primo [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) è uguale al secondo. |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Restituisce un valore che indica se il valore del primo [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) è diverso dal secondo. |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore specificato di [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

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
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Livello di correzione errori Reed-Solomon del codice a barre riconosciuto. Da basso a alto: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Versione del MicroQR Code riconosciuto. Da M1 a M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


Livello di correzione errori Reed-Solomon del codice a barre riconosciuto. Da basso a alto: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


Ottiene l'indice del codice a barre in modalità di aggiunta strutturata QR. L'indice parte da 0. Il valore predefinito è -1.

Valore: La quantità del codice a barre in modalità di aggiunta strutturata QR.

**Returns:**
int - l'indice del codice a barre in modalità di aggiunta strutturata QR.
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


Ottiene la quantità di codici a barre in modalità di aggiunta strutturata QR. Il valore predefinito è -1.

Valore: La quantità del codice a barre in modalità di aggiunta strutturata QR.

**Returns:**
int - la quantità di codici a barre in modalità di aggiunta strutturata QR.
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


Ottiene i dati di parità della modalità di aggiunta strutturata QR. Il valore predefinito è -1.

Valore: L'indice del codice a barre in modalità di aggiunta strutturata QR.

**Returns:**
int - i dati di parità della modalità di aggiunta strutturata QR.
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


Versione del QR Code riconosciuto. Da Version1 a Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Versione del RectMicroQR Code riconosciuto. Da R7x43 a R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Ottiene l'indice del codice a barre in modalità di aggiunta strutturata QR. L'indice parte da 0. Il valore predefinito è -1.

Valore: La quantità del codice a barre in modalità di aggiunta strutturata QR.

**Returns:**
int - l'indice del codice a barre in modalità di aggiunta strutturata QR.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Ottiene la quantità di codici a barre in modalità di aggiunta strutturata QR. Il valore predefinito è -1.

Valore: La quantità del codice a barre in modalità di aggiunta strutturata QR.

**Returns:**
int - la quantità di codici a barre in modalità di aggiunta strutturata QR.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Ottiene i dati di parità della modalità di aggiunta strutturata QR. Il valore predefinito è -1.

Valore: L'indice del codice a barre in modalità di aggiunta strutturata QR.

**Returns:**
int - i dati di parità della modalità di aggiunta strutturata QR.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versione del QR Code riconosciuto. Da Version1 a Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


Restituisce un valore che indica se il valore del primo [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) è uguale al secondo.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Un primo valore confrontato |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Un secondo valore confrontato |

**Returns:**
boolean -  **true**  se il primo ha lo stesso valore del secondo; altrimenti,  **false** .
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


Restituisce un valore che indica se il valore del primo [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) è diverso dal secondo.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Un primo valore confrontato |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Un secondo valore confrontato |

**Returns:**
boolean -  **true**  se il primo ha un valore diverso dal secondo; altrimenti,  **false** .
### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String - Una stringa che rappresenta questo [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
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

