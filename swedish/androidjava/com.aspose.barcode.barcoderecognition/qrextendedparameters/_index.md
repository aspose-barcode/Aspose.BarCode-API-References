---
title: "QRExtendedParameters"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "Lagrar QR Structured Append-information för igenkänd streckkod"
type: docs
weight: 40
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Lagrar QR Structured Append-information för igenkänd streckkod

Detta exempel visar hur man får QR Structured Append‑data

```
{
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)‑värde. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Reed‑Solomon‑felkorrigeringsnivå för den igenkända streckkoden. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version av den igenkända MicroQR‑koden. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Version av den igenkända RectMicroQR‑koden. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Hämtar indexet för QR Structured Append‑lägesstreckkoden. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Hämtar antalet QR Structured Append‑lägesstreckkoder. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Hämtar paritetsdata för QR Structured Append‑läget. |
| [getVersion()](#getVersion--) | Version av den igenkända QR‑koden. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [isEmpty()](#isEmpty--) | Testar om alla parametrar endast har standardvärden. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)‑värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett System.Object‑värde att jämföra med detta objekt. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
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


Reed‑Solomon‑felkorrigeringsnivå för den igenkända streckkoden. Från låg till hög: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version av den igenkända MicroQR‑koden. Från M1 till M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Version av den igenkända RectMicroQR‑koden. Från R7x43 till R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Hämtar indexet för QR‑kodens strukturerade tilläggsläge. Indexet börjar på 0. Standardvärdet är -1.

Värde: Antalet QR‑kodens strukturerade tilläggsläge.

**Returns:**
int – indexet för QR‑kodens strukturerade tilläggsläge.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Hämtar antalet QR‑kodens strukturerade tilläggsläges‑streckkoder. Standardvärdet är -1.

Värde: Antalet QR‑kodens strukturerade tilläggsläge.

**Returns:**
int – antalet QR‑kodens strukturerade tilläggsläges‑streckkoder.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Hämtar paritetsdata för QR‑kodens strukturerade tilläggsläge. Standardvärdet är -1.

Värde: Indexet för QR‑kodens strukturerade tilläggsläge.

**Returns:**
int – paritetsdata för QR‑kodens strukturerade tilläggsläge.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version av igenkänd QR‑kod. Från Version1 till Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bit signerad heltals‑hashkod.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Testar om alla parametrar endast har standardvärden.

Värde: Returnerar  **true**  om alla parametrar endast har standardvärden; annars,  **false** .

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


Returnerar en människoläsbar strängrepresentation av detta [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String – En sträng som representerar detta [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

