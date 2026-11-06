---
title: "QrParameters"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
description: "QR-parameters."
type: docs
weight: 62
url: /nl/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR-parameters.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation-identifiers. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) |  |
| [getEncodeMode()](#getEncodeMode--) | QR-symbologie type van de coderingsmodus van BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Niveau van Reed-Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versie van MicroQR Code. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Versie van RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | QR gestructureerde toevoegingsparameters. |
| [getVersion()](#getVersion--) | Versie van QR-code. Van Version1 tot Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation-identifiers. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) |  |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR-symbologie type van de coderingsmodus van BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Niveau van Reed-Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Versie van MicroQR Code. |
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


Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bestaat uit alle bekende charset-coderingen. Niet ondersteund door MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public final boolean getEncodeGS1SeparatorInByteMode()
```


Haalt een waarde op of stelt deze in die aangeeft of GS1-specialtekens gecodeerd moeten worden in byte-modus voor QR- en RectMicroQR-barcodes.

Als false, kunnen GS1-scheidingstekens worden gecodeerd als '%' in alfanumerieke modus volgens de QR-specificatie.

Als true, worden GS1-groepscheidingstekens gecodeerd in byte-modus als het 0x1D-teken, en worden '%' tekens ook gecodeerd in byte-modus om ze als data te behouden.

Deze optie kan de compatibiliteit verbeteren met decoders die byte-niveau GS1-groepscheidingstekens verwachten en voorkomt dat '%' datatekens worden geïnterpreteerd als GS1-scheidingstekens.

**Returns:**
boolean - een waarde die aangeeft of GS1-specialtekens gecodeerd moeten worden in byte-modus voor QR- en RectMicroQR-barcodes.
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


QR-symbologie type van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.Auto.

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


QR gestructureerde toevoegingsparameters. Gestructureerde toevoegingsmodus wordt niet ondersteund door MicroQR- en RectMicroQR-barcodes.

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


Hoogte/breedteverhouding van 2D BarCode-module.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bestaat uit alle bekende charset-coderingen. Niet ondersteund door MicroQR.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public final void setEncodeGS1SeparatorInByteMode(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of GS1-specialtekens gecodeerd moeten worden in byte-modus voor QR- en RectMicroQR-barcodes.

Als false, kunnen GS1-scheidingstekens worden gecodeerd als '%' in alfanumerieke modus volgens de QR-specificatie.

Als true, worden GS1-groepscheidingstekens gecodeerd in byte-modus als het 0x1D-teken, en worden '%' tekens ook gecodeerd in byte-modus om ze als data te behouden.

Deze optie kan de compatibiliteit verbeteren met decoders die byte-niveau GS1-groepscheidingstekens verwachten en voorkomt dat '%' datatekens worden geïnterpreteerd als GS1-scheidingstekens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of GS1-specialtekens gecodeerd moeten worden in byte-modus voor QR- en RectMicroQR-barcodes. |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


QR-symbologie type van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.Auto.

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


QR gestructureerde toevoegingsparameters. Gestructureerde toevoegingsmodus wordt niet ondersteund door MicroQR- en RectMicroQR-barcodes.

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
java.lang.String - Een tekenreeks die deze [QrParameters](../../com.aspose.barcode.generation/qrparameters) vertegenwoordigt.
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

