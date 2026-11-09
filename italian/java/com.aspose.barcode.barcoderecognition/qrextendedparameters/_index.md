---
title: "QRExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Memorizza informazioni di QR Structured Append del codice a barre riconosciuto"
type: docs
weight: 38
url: /it/java/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Memorizza informazioni di QR Structured Append del codice a barre riconosciuto

Questo esempio mostra come ottenere i dati QR Structured Append

```
{
```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Livello di correzione errori Reed-Solomon del codice a barre riconosciuto. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versione del MicroQR Code riconosciuto. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Versione del RectMicroQR Code riconosciuto. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Ottiene l'indice del codice a barre QR in modalità append strutturata. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Ottiene la quantità di codici a barre QR in modalità append strutturata. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Ottiene i dati di parità della modalità append strutturata QR. |
| [getVersion()](#getVersion--) | Versione del QR Code riconosciuto. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isEmpty--) | Verifica se tutti i parametri hanno solo valori predefiniti |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore specificato [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene l'indice del codice a barre QR in modalità append strutturata. L'indice inizia da 0. Il valore predefinito è -1.

Valore: La quantità di codici a barre QR in modalità append strutturata.

**Returns:**
int - l'indice del codice a barre QR in modalità append strutturata.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Ottiene la quantità di codici a barre QR in modalità append strutturata. Il valore predefinito è -1.

Valore: La quantità di codici a barre QR in modalità append strutturata.

**Returns:**
int - la quantità di codici a barre QR in modalità append strutturata.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Ottiene i dati di parità della modalità append strutturata QR. Il valore predefinito è -1.

Valore: L'indice del codice a barre QR in modalità append strutturata.

**Returns:**
int - i dati di parità della modalità append strutturata QR.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versione del QR Code riconosciuto. Da Versione1 a Versione40.

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


Verifica se tutti i parametri hanno solo valori predefiniti

Valore: Restituisce **true** se tutti i parametri hanno solo valori predefiniti; altrimenti, **false**.

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

