---
title: "AztecParametersUI"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Envoltorio UI para la clase AztecParameters"
type: docs
weight: 10
url: /es/java/com.aspose.barcode.barcodecontrol/aztecparametersui/
---
**Inheritance:**
java.lang.Object
```
public class AztecParametersUI
```

Envoltorio UI para la clase AztecParameters
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Relación altura/ancho del módulo de código de barras 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Obtiene la codificación ECI. |
| [getEncodeMode()](#getEncodeMode--) | Obtiene un modo de codificación Aztec. |
| [getErrorLevel()](#getErrorLevel--) | Nivel de corrección de errores de los tipos de código de barras Aztec. |
| [getLayersCount()](#getLayersCount--) | Obtiene el recuento de capas del símbolo Aztec. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | ID del código de barras para el modo Structured Append del código de barras Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Recuento de códigos de barras para el modo Structured Append del código de barras Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | ID de archivo para el modo Structured Append del código de barras Aztec (campo opcional). |
| [getSymbolMode()](#getSymbolMode--) | Obtiene un modo de símbolo Aztec. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Relación altura/ancho del módulo de código de barras 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Establece la codificación ECI. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Establece un modo de codificación Aztec. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Nivel de corrección de errores de los tipos de código de barras Aztec. |
| [setLayersCount(int value)](#setLayersCount-int-) | Establece el recuento de capas del símbolo Aztec. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | ID del código de barras para el modo Structured Append del código de barras Aztec. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Recuento de códigos de barras para el modo Structured Append del código de barras Aztec. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | ID de archivo para el modo Structured Append del código de barras Aztec (campo opcional). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Establece un modo de símbolo Aztec. |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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
public float getAspectRatio()
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


Obtiene la codificación ECI. Se usa cuando AztecEncodeMode es Auto. Valor predeterminado: ISO-8859-1.

**Returns:**
int - codificación ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Obtiene un modo de codificación Aztec. Valor predeterminado: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - un modo de codificación Aztec.
### getErrorLevel() {#getErrorLevel--}
```
public int getErrorLevel()
```


Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 10 y 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Obtiene la cantidad de capas del símbolo Aztec. La cantidad de capas debe estar en el rango de 1 a 3 para el modo Compacto y en el rango de 1 a 32 para el modo de Rango Completo. Valor predeterminado: 0 (auto).

**Returns:**
int - cantidad de capas del símbolo Aztec.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


ID de código de barras para el modo Structured Append del código de barras Aztec. El ID de código de barras debe estar en el rango de 1 al número de códigos de barras. Valor predeterminado: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Cantidad de códigos de barras para el modo Structured Append del código de barras Aztec. La cantidad de códigos de barras debe estar en el rango de 1 a 26. Valor predeterminado: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


ID de archivo para el modo Structured Append del código de barras Aztec (campo opcional). El ID de archivo no debe contener espacios. Valor predeterminado: cadena vacía

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public AztecSymbolMode getSymbolMode()
```


Obtiene un modo de símbolo Aztec.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector.

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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public void setAspectRatio(float value)
```


Relación altura/ancho del módulo de código de barras 2D.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Establece la codificación ECI. Se usa cuando AztecEncodeMode es Auto. Valor predeterminado: ISO-8859-1

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Codificación ECI. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Establece un modo de codificación Aztec. Valor predeterminado: Auto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.barcode.generation.AztecEncodeMode | un modo de codificación Aztec. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public void setErrorLevel(int value)
```


Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 10 y 95.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Establece la cantidad de capas del símbolo Aztec. La cantidad de capas debe estar en el rango de 1 a 3 para el modo Compacto y en el rango de 1 a 32 para el modo de Rango Completo. Valor predeterminado: 0 (auto).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | cantidad de capas del símbolo Aztec. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


ID de código de barras para el modo Structured Append del código de barras Aztec. El ID de código de barras debe estar en el rango de 1 al número de códigos de barras. Valor predeterminado: 0

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Cantidad de códigos de barras para el modo Structured Append del código de barras Aztec. La cantidad de códigos de barras debe estar en el rango de 1 a 26. Valor predeterminado: 0

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


ID de archivo para el modo Structured Append del código de barras Aztec (campo opcional). El ID de archivo no debe contener espacios. Valor predeterminado: cadena vacía

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public void setSymbolMode(AztecSymbolMode value)
```


Establece un modo de símbolo Aztec.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - Una cadena que representa este [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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

