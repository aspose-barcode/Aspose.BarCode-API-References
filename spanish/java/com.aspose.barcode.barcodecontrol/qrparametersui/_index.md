---
title: "QrParametersUI"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Wrapper de UI para la clase com.aspose.barcode.generation.QrParameters."
type: docs
weight: 17
url: /es/java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

Wrapper de UI para la clase com.aspose.barcode.generation.QrParameters.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Relación altura/ancho del módulo de código de barras 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Identificadores de Interpretación de Canal Extendido. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) | Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para los códigos de barras QR y RectMicroQR. |
| [getEncodeMode()](#getEncodeMode--) | Tipo de simbología QR del modo de codificación de BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Nivel de corrección de errores Reed-Solomon para los códigos de barras QR, MicroQR y RectMicroQR. |
| [getMicroQrVersion()](#getMicroQrVersion--) | Versión del MicroQR Code. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Versión del RectMicroQR Code. |
| [getVersion()](#getVersion--) | Versión del QR Code. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Relación altura/ancho del módulo de código de barras 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identificadores de Interpretación de Canal Extendido. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) | Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para los códigos de barras QR y RectMicroQR. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Tipo de simbología QR del modo de codificación de BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Nivel de corrección de errores Reed-Solomon para los códigos de barras QR, MicroQR y RectMicroQR. |
| [setMicroQrVersion(MicroQRVersion value)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | Versión del MicroQR Code. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Versión del RectMicroQR Code. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Versión del QR Code. |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
public int getECIEncoding()
```


Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjuntos de caracteres conocidas. No compatible con MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public boolean getEncodeGS1SeparatorInByteMode()
```


Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para los códigos de barras QR y RectMicroQR.

Si es falso, los separadores GS1 pueden codificarse como '%' en modo Alfanumérico según la especificación QR.

Si es verdadero, los separadores de grupo GS1 se codifican en modo Byte como el carácter 0x1D, y los caracteres '%' también se codifican en modo Byte para preservarlos como datos.

Esta opción puede mejorar la compatibilidad con decodificadores que esperan separadores de grupo GS1 a nivel de byte y evita que los caracteres de datos '%' se interpreten como separadores GS1.

**Returns:**
boolean
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. ver QERrrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQrVersion() {#getMicroQrVersion--}
```
public final MicroQRVersion getMicroQrVersion()
```


Versión del código MicroQR. Desde la versión M1 hasta la versión M4. El valor predeterminado es MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Versión del código RectMicroQR. Desde la versión R7x59 hasta la versión R17x139. El valor predeterminado es RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versión del código QR. Desde Version1 hasta Version40 para códigos QR y desde M1 hasta M4 para MicroQr. El valor predeterminado es QRVersion.Auto.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjuntos de caracteres conocidas. No compatible con MicroQR.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public void setEncodeGS1SeparatorInByteMode(boolean value)
```


Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para los códigos de barras QR y RectMicroQR.

Si es falso, los separadores GS1 pueden codificarse como '%' en modo Alfanumérico según la especificación QR.

Si es verdadero, los separadores de grupo GS1 se codifican en modo Byte como el carácter 0x1D, y los caracteres '%' también se codifican en modo Byte para preservarlos como datos.

Esta opción puede mejorar la compatibilidad con decodificadores que esperan separadores de grupo GS1 a nivel de byte y evita que los caracteres de datos '%' se interpreten como separadores GS1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.Auto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. ver QERrrorLevel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQrVersion(MicroQRVersion value) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQrVersion(MicroQRVersion value)
```


Versión del código MicroQR. Desde la versión M1 hasta la versión M4. El valor predeterminado es MicroQRVersion.Auto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Versión del código RectMicroQR. Desde la versión R7x59 hasta la versión R17x139. El valor predeterminado es RectMicroQRVersion.Auto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Versión del código QR. Desde Version1 hasta Version40 para códigos QR y desde M1 hasta M4 para MicroQr. El valor predeterminado es QRVersion.Auto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - Una cadena que representa este [QrParameters](../../com.aspose.barcode.generation/qrparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

