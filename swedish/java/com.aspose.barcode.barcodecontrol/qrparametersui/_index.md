---
title: "QrParametersUI"
second_title: "Aspose.BarCode för Java API-referens"
description: "UI-omslag för klassen com.aspose.barcode.generation.QrParameters."
type: docs
weight: 17
url: /sv/java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

UI-omslag för klassen com.aspose.barcode.generation.QrParameters.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höjd/bredd-förhållande för 2D BarCode-modul. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) | Hämtar eller anger ett värde som indikerar om GS1-specialtecken ska kodas i Byte-läge för QR- och RectMicroQR-streckkoder. |
| [getEncodeMode()](#getEncodeMode--) | QR-symbologi typ för BarCode:s kodningsläge. |
| [getErrorLevel()](#getErrorLevel--) | Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkoder. |
| [getMicroQrVersion()](#getMicroQrVersion--) | Version av MicroQR-kod. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Version av RectMicroQR-kod. |
| [getVersion()](#getVersion--) | Version av QR-kod. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höjd/bredd-förhållande för 2D BarCode-modul. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifierare för utökad kanalinterpretation. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) | Hämtar eller anger ett värde som indikerar om GS1-specialtecken ska kodas i Byte-läge för QR- och RectMicroQR-streckkoder. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR-symbologi typ för BarCode:s kodningsläge. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkoder. |
| [setMicroQrVersion(MicroQRVersion value)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | Version av MicroQR-kod. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Version av RectMicroQR-kod. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Version av QR-kod. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höjd/bredd-förhållande för 2D BarCode-modul.

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
public int getECIEncoding()
```


Utökade kanalinterpretationsidentifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Aktuell implementation består av alla välkända teckenkodningar. Stöds inte av MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public boolean getEncodeGS1SeparatorInByteMode()
```


Hämtar eller anger ett värde som indikerar om GS1-specialtecken ska kodas i Byte-läge för QR- och RectMicroQR-streckkoder.

Om falskt kan GS1-separatorer kodas som '%' i alfanumeriskt läge enligt QR-specifikationen.

Om sant kodas GS1-gruppseparatorer i Byte-läge som tecknet 0x1D, och '%'‑tecken kodas också i Byte-läge för att bevara dem som data.

Detta alternativ kan förbättra kompatibiliteten med avkodare som förväntar sig byte‑nivå GS1‑gruppseparatorer och förhindrar att '%'‑datatecken tolkas som GS1‑separatorer.

**Returns:**
boolean
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


QR-symbologi typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkoder. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. se QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQrVersion() {#getMicroQrVersion--}
```
public final MicroQRVersion getMicroQrVersion()
```


Version av MicroQR-kod. Från version M1 till version M4. Standardvärde är MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Version av RectMicroQR-kod. Från version R7x59 till version R17x139. Standardvärde är RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version av QR-kod. Från Version1 till Version40 för QR-kod och från M1 till M4 för MicroQr. Standardvärde är QRVersion.Auto.

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


Höjd/bredd-förhållande för 2D BarCode-modul.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Utökade kanalinterpretationsidentifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Aktuell implementation består av alla välkända teckenkodningar. Stöds inte av MicroQR.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public void setEncodeGS1SeparatorInByteMode(boolean value)
```


Hämtar eller anger ett värde som indikerar om GS1-specialtecken ska kodas i Byte-läge för QR- och RectMicroQR-streckkoder.

Om falskt kan GS1-separatorer kodas som '%' i alfanumeriskt läge enligt QR-specifikationen.

Om sant kodas GS1-gruppseparatorer i Byte-läge som tecknet 0x1D, och '%'‑tecken kodas också i Byte-läge för att bevara dem som data.

Detta alternativ kan förbättra kompatibiliteten med avkodare som förväntar sig byte‑nivå GS1‑gruppseparatorer och förhindrar att '%'‑datatecken tolkas som GS1‑separatorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


QR-symbologi typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.Auto.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkoder. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. se QRErrorLevel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQrVersion(MicroQRVersion value) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQrVersion(MicroQRVersion value)
```


Version av MicroQR-kod. Från version M1 till version M4. Standardvärde är MicroQRVersion.Auto.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Version av RectMicroQR-kod. Från version R7x59 till version R17x139. Standardvärde är RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Version av QR-kod. Från Version1 till Version40 för QR-kod och från M1 till M4 för MicroQr. Standardvärde är QRVersion.Auto.

**Parameters:**
| Parameter | Typ | Beskrivning |
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

