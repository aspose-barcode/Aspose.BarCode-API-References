---
title: QrParameters
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Parámetros de QR.
type: docs
weight: 64
url: /es/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

Parámetros de QR.
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Relación altura/ancho del módulo de código de barras 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Identificadores de Interpretación de Canal Extendido. |
| [getEncodeMode()](#getEncodeMode--) | Tipo de simbología QR del modo de codificación del código de barras. |
| [getErrorLevel()](#getErrorLevel--) | Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versión de MicroQR Code. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Identificadores de Interpretación de Canal Extendido. |
| [getQrEncodeMode()](#getQrEncodeMode--) | Tipo de simbología QR del modo de codificación del código de barras. |
| [getQrEncodeType()](#getQrEncodeType--) | Modo selector QR / MicroQR. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. |
| [getQrVersion()](#getQrVersion--) | Versión del código QR. Desde Version1 hasta Version40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Versión de RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | Parámetros de anexado estructurado QR. |
| [getVersion()](#getVersion--) | Versión del código QR. Desde Version1 hasta Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Relación altura/ancho del módulo de código de barras 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identificadores de Interpretación de Canal Extendido. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Tipo de simbología QR del modo de codificación del código de barras. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Versión de MicroQR Code. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | Modo selector QR / MicroQR. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Versión de RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | Parámetros de anexado estructurado QR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Versión del código QR. Desde Version1 hasta Version40. |
| [toString()](#toString--) | Devuelve una representación en cadena legible por humanos de este [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Relación altura/ancho del módulo de código de barras 2D.

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


Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas. No es compatible con MicroQR.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Tipo de simbología QR del modo de codificación del código de barras. Valor predeterminado: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. Ver QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Versión del código MicroQR. De la versión M1 a la versión M4. El valor predeterminado es MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas. No es compatible con MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


Tipo de simbología QR del modo de codificación del código de barras. Valor predeterminado: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


Modo selector QR / MicroQR. Seleccione ForceQR para símbolos QR estándar, Auto para MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. Ver QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


Versión del código QR. De Version1 a Version40. El valor predeterminado es QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Versión del código RectMicroQR. De la versión R7x59 a la versión R17x139. El valor predeterminado es RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


Parámetros de anexado estructurado QR. El modo de anexado estructurado no es compatible con los códigos de barras MicroQR y RectMicroQR.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versión del código QR. De Version1 a Version40. El valor predeterminado es QRVersion.Auto.

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


Relación altura/ancho del módulo de código de barras 2D.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas. No es compatible con MicroQR.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Tipo de simbología QR del modo de codificación del código de barras. Valor predeterminado: QREncodeMode.Auto.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. Ver QRErrorLevel.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Versión del código MicroQR. De la versión M1 a la versión M4. El valor predeterminado es MicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


Modo selector QR / MicroQR. Seleccione ForceQR para símbolos QR estándar, Auto para MicroQR.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Versión del código RectMicroQR. De la versión R7x59 a la versión R17x139. El valor predeterminado es RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


Parámetros de anexado estructurado QR. El modo de anexado estructurado no es compatible con los códigos de barras MicroQR y RectMicroQR.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Versión del código QR. De Version1 a Version40. El valor predeterminado es QRVersion.Auto.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación en cadena legible por humanos de este [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - Una cadena que representa este [QrParameters](../../com.aspose.barcode.generation/qrparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

