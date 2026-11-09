---
title: "QRExtendedParameters"
second_title: "Aspose.BarCode för Java API-referens"
description: "Lagrar en QR Structured Append‑information för igenkänd streckkod"
type: docs
weight: 38
url: /sv/java/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Lagrar en QR Structured Append‑information för igenkänd streckkod

Detta exempel visar hur man hämtar QR Structured Append-data

```
{
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-värde. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Reed-Solomon-felkorrigeringsnivå för igenkänd streckkod. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version av igenkänd MicroQR Code. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Version av igenkänd RectMicroQR Code. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Hämtar indexet för QR structured append-lägesstreckkoden. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Hämtar antalet QR structured append-lägesstreckkoder. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Hämtar paritydata för QR structured append-läget. |
| [getVersion()](#getVersion--) | Version av igenkänd QR Code. |
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


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett System.Object‑värde att jämföra med detta objekt. |

**Returns:**
boolesk -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
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


Reed-Solomon-felkorrigeringsnivå för igenkänd streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version av igenkänd MicroQR Code. Från M1 till M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Version av igenkänd RectMicroQR Code. Från R7x43 till R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Hämtar indexet för QR structured append-lägesstreckkoden. Index börjar på 0. Standardvärdet är -1.

Värde: Antalet QR structured append-lägesstreckkoder.

**Returns:**
int - indexet för QR structured append-lägesstreckkoden.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Hämtar antalet QR structured append-lägesstreckkoder. Standardvärdet är -1.

Värde: Antalet QR structured append-lägesstreckkoder.

**Returns:**
int - antalet QR structured append-lägesstreckkoder.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Hämtar paritydata för QR structured append-läget. Standardvärdet är -1.

Värde: Indexet för QR structured append-lägesstreckkoden.

**Returns:**
int - paritydata för QR structured append-läget.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version av igenkänd QR Code. Från Version1 till Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
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
java.lang.String - En sträng som representerar detta [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

