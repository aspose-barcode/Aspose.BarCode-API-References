---
title: QRExtendedParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Lagrar QR Structured Append-information för en igenkänd streckkod
type: docs
weight: 42
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Lagrar QR Structured Append-information för en igenkänd streckkod

Detta exempel visar hur man får QR Structured Append-data

```
{
```
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett angivet [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) värde. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Reed-Solomon felkorrigeringsnivå för den igenkända streckkoden. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version av den igenkända MicroQR-koden. |
| [getQRErrorLevel()](#getQRErrorLevel--) | Reed-Solomon felkorrigeringsnivå för den igenkända streckkoden. |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | Hämtar indexet för QR structured append-lägesstreckkoden. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | Hämtar antalet QR structured append-lägesstreckkoder. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | Hämtar QR:s strukturerade tilläggslägesparitetsdata. |
| [getQRVersion()](#getQRVersion--) | Version av identifierad QR-kod. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Version av identifierad RectMicroQR-kod. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Hämtar indexet för QR structured append-lägesstreckkoden. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Hämtar antalet QR structured append-lägesstreckkoder. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Hämtar QR:s strukturerade tilläggslägesparitetsdata. |
| [getVersion()](#getVersion--) | Version av identifierad QR-kod. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [isEmpty()](#isEmpty--) | Testar om alla parametrar endast har standardvärden |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Returnerar ett värde som indikerar om det första [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-värdet är lika med det andra. |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Returnerar ett värde som indikerar om det första [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-värdet är skilt från det andra. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett angivet [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) värde.

**Parameters:**
| Parameter | Type | Beskrivning |
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


Reed-Solomon-felkorrigeringsnivå för identifierad streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version av identifierad MicroQR-kod. Från M1 till M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


Reed-Solomon-felkorrigeringsnivå för identifierad streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


Hämtar indexet för QR:s strukturerade tilläggslägesstreckkod. Indexet börjar på 0. Standardvärdet är -1.

Värde: Antalet QR:s strukturerade tilläggslägesstreckkod.

**Returns:**
int – indexet för QR:s strukturerade tilläggslägesstreckkod.
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


Hämtar antalet QR:s strukturerade tilläggslägesstreckkoder. Standardvärdet är -1.

Värde: Antalet QR:s strukturerade tilläggslägesstreckkod.

**Returns:**
int – antalet QR:s strukturerade tilläggslägesstreckkoder.
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


Hämtar QR:s strukturerade tilläggslägesparitetsdata. Standardvärdet är -1.

Värde: Indexet för QR:s strukturerade tilläggslägesstreckkod.

**Returns:**
int – QR:s strukturerade tilläggslägesparitetsdata.
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


Version av identifierad QR-kod. Från Version1 till Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Version av identifierad RectMicroQR-kod. Från R7x43 till R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Hämtar indexet för QR:s strukturerade tilläggslägesstreckkod. Indexet börjar på 0. Standardvärdet är -1.

Värde: Antalet QR:s strukturerade tilläggslägesstreckkod.

**Returns:**
int – indexet för QR:s strukturerade tilläggslägesstreckkod.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Hämtar antalet QR:s strukturerade tilläggslägesstreckkoder. Standardvärdet är -1.

Värde: Antalet QR:s strukturerade tilläggslägesstreckkod.

**Returns:**
int – antalet QR:s strukturerade tilläggslägesstreckkoder.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Hämtar QR:s strukturerade tilläggslägesparitetsdata. Standardvärdet är -1.

Värde: Indexet för QR:s strukturerade tilläggslägesstreckkod.

**Returns:**
int – QR:s strukturerade tilläggslägesparitetsdata.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version av identifierad QR-kod. Från Version1 till Version40.

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


Testar om alla parametrar endast har standardvärden

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




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


Returnerar ett värde som indikerar om det första [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-värdet är lika med det andra.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Ett första jämfört värde |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Ett andra jämfört värde |

**Returns:**
boolean -  **true**  om första har samma värde som andra; annars,  **false** .
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


Returnerar ett värde som indikerar om det första [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-värdet är skilt från det andra.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Ett första jämfört värde |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Ett andra jämfört värde |

**Returns:**
boolean -  **true**  om första har ett annat värde än andra; annars,  **false** .
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

