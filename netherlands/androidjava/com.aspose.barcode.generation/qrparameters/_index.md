---
title: QrParameters
second_title: Aspose.BarCode for Android via Java API-referentie
description: QR parameters.
type: docs
weight: 64
url: /nl/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR parameters.
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation-identifiers. |
| [getEncodeMode()](#getEncodeMode--) | QR-symbooltype van de coderingsmodus van BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Niveau van Reed-Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versie van MicroQR Code. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Extended Channel Interpretation-identifiers. |
| [getQrEncodeMode()](#getQrEncodeMode--) | QR-symbooltype van de coderingsmodus van BarCode. |
| [getQrEncodeType()](#getQrEncodeType--) | QR / MicroQR-selectormodus. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Niveau van Reed-Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. |
| [getQrVersion()](#getQrVersion--) | Versie van QR-code. Van Version1 tot Version40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Versie van RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | QR gestructureerde toevoegingsparameters. |
| [getVersion()](#getVersion--) | Versie van QR-code. Van Version1 tot Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation-identifiers. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR-symbooltype van de coderingsmodus van BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Niveau van Reed-Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Versie van MicroQR Code. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | QR / MicroQR-selectormodus. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Versie van RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR gestructureerde toevoegingsparameters. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Versie van QR-code. Van Version1 tot Version40. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Hoogte/breedteverhouding van 2D BarCode-module.

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


Extended Channel Interpretation-identifiers. Wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bevat alle bekende charset‑coderingen. Niet ondersteund door MicroQR.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


QR-symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Niveau van Reed-Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. Zie QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Versie van MicroQR-code. Van versie M1 tot versie M4. Standaardwaarde is MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Extended Channel Interpretation-identifiers. Wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bevat alle bekende charset‑coderingen. Niet ondersteund door MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


QR-symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


QR-/MicroQR-selectiemodus. Selecteer ForceQR voor standaard QR-symbolen, Auto voor MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


Niveau van Reed-Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. Zie QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


Versie van QR-code. Van Version1 tot Version40. Standaardwaarde is QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Versie van RectMicroQR-code. Van versie R7x59 tot versie R17x139. Standaardwaarde is RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


QR-gestructureerde toevoegingsparameters. Gestructureerde toevoegingsmodus wordt niet ondersteund door MicroQR- en RectMicroQR-barcodes.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versie van QR-code. Van Version1 tot Version40. Standaardwaarde is QRVersion.Auto.

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


Hoogte/breedteverhouding van 2D BarCode-module.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation-identifiers. Wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bevat alle bekende charset‑coderingen. Niet ondersteund door MicroQR.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


QR-symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Niveau van Reed-Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. Zie QRErrorLevel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Versie van MicroQR-code. Van versie M1 tot versie M4. Standaardwaarde is MicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


QR-/MicroQR-selectiemodus. Selecteer ForceQR voor standaard QR-symbolen, Auto voor MicroQR.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Versie van RectMicroQR-code. Van versie R7x59 tot versie R17x139. Standaardwaarde is RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR-gestructureerde toevoegingsparameters. Gestructureerde toevoegingsmodus wordt niet ondersteund door MicroQR- en RectMicroQR-barcodes.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Versie van QR-code. Van Version1 tot Version40. Standaardwaarde is QRVersion.Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - Een string die deze [QrParameters](../../com.aspose.barcode.generation/qrparameters) vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

