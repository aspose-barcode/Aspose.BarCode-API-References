---
title: QrParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: QR‑parametrar.
type: docs
weight: 64
url: /sv/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR‑parametrar.
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getEncodeMode()](#getEncodeMode--) | QR-symbologi-typ för BarCode:s kodningsläge. |
| [getErrorLevel()](#getErrorLevel--) | Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version av MicroQR Code. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getQrEncodeMode()](#getQrEncodeMode--) | QR-symbologi-typ för BarCode:s kodningsläge. |
| [getQrEncodeType()](#getQrEncodeType--) | QR / MicroQR-väljarläge. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. |
| [getQrVersion()](#getQrVersion--) | Version av QR-kod. Från Version1 till Version40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Version av RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | QR‑strukturerade tilläggs‑parametrar. |
| [getVersion()](#getVersion--) | Version av QR-kod. Från Version1 till Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifierare för utökad kanalinterpretation. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR-symbologi-typ för BarCode:s kodningsläge. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Version av MicroQR Code. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | QR / MicroQR-väljarläge. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Version av RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR‑strukturerade tilläggs‑parametrar. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Version av QR-kod. Från Version1 till Version40. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höjd/bredd-förhållande för 2D BarCode-modulen.

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


Extended Channel Interpretation Identifiers. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Den nuvarande implementeringen består av alla välkända teckenuppsättningskodningar. Stöds inte av MicroQR.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. Se QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version av MicroQR-kod. Från version M1 till version M4. Standardvärdet är MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Extended Channel Interpretation Identifiers. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Den nuvarande implementeringen består av alla välkända teckenuppsättningskodningar. Stöds inte av MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


QR / MicroQR-väljarläge. Välj ForceQR för standard QR-symboler, Auto för MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. Se QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


Version av QR-kod. Från Version1 till Version40. Standardvärdet är QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Version av RectMicroQR-kod. Från version R7x59 till version R17x139. Standardvärdet är RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


QR strukturerade tilläggsparametrar. Strukturerat tilläggsläge stöds inte av MicroQR- och RectMicroQR-streckkoder.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version av QR-kod. Från Version1 till Version40. Standardvärdet är QRVersion.Auto.

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


Höjd/bredd-förhållande för 2D BarCode-modulen.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Den nuvarande implementeringen består av alla välkända teckenuppsättningskodningar. Stöds inte av MicroQR.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. Se QRErrorLevel.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Version av MicroQR-kod. Från version M1 till version M4. Standardvärdet är MicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


QR / MicroQR-väljarläge. Välj ForceQR för standard QR-symboler, Auto för MicroQR.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Version av RectMicroQR-kod. Från version R7x59 till version R17x139. Standardvärdet är RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR strukturerade tilläggsparametrar. Strukturerat tilläggsläge stöds inte av MicroQR- och RectMicroQR-streckkoder.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Version av QR-kod. Från Version1 till Version40. Standardvärdet är QRVersion.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - En sträng som representerar detta [QrParameters](../../com.aspose.barcode.generation/qrparameters).
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

