---
title: "MaxiCodeParameters"
second_title: "Referencia de API de Aspose.BarCode para Android mediante Java"
description: "Parámetros de MaxiCode."
type: docs
weight: 55
url: /es/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

Parámetros de MaxiCode.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Relación altura/ancho del módulo de código de barras 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Obtiene la codificación ECI. |
| [getEncodeMode()](#getEncodeMode--) | Obtiene un modo de codificación MaxiCode. |
| [getMode()](#getMode--) | Obtiene un modo de codificación MaxiCode. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Obtiene un id de código de barras MaxiCode en modo de anexado estructurado. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Obtiene el recuento de códigos de barras MaxiCode en modo de anexado estructurado. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Relación altura/ancho del módulo de código de barras 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Establece la codificación ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Establece un modo de codificación MaxiCode. |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | Establece un modo de codificación MaxiCode. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Establece un identificador de código de barras MaxiCode en modo de anexado estructurado. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Establece la cantidad de códigos de barras MaxiCode en modo de anexado estructurado. |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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
public final int getECIEncoding()
```


Obtiene la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1

**Returns:**
int - codificación ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Obtiene un modo de codificación MaxiCode. Valor predeterminado: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public final MaxiCodeMode getMode()
```


Obtiene un modo de codificación MaxiCode.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Obtiene un identificador de código de barras MaxiCode en modo de anexado estructurado. El ID debe ser un valor entre 1 y 8. Valor predeterminado: 0

**Returns:**
int - un id de código de barras MaxiCode en modo de anexado estructurado.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Obtiene la cantidad de códigos de barras MaxiCode en modo de anexado estructurado. El número de cantidad debe ser un valor entre 2 y 8 (cantidad máxima de códigos de barras). Valor predeterminado: -1

**Returns:**
int - un recuento de códigos de barras MaxiCode en modo de anexado estructurado.
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


Relación altura/ancho del módulo de código de barras 2D.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Codificación ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Establece un modo de codificación MaxiCode. Valor predeterminado: Auto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | un modo de codificación MaxiCode. |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


Establece un modo de codificación MaxiCode.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | un modo de codificación MaxiCode. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Establece un identificador de código de barras MaxiCode en modo de anexado estructurado. El ID debe ser un valor entre 1 y 8. Valor predeterminado: 0

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | un identificador de código de barras MaxiCode en modo de anexado estructurado. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Establece la cantidad de códigos de barras MaxiCode en modo de anexado estructurado. El número de cantidad debe ser un valor entre 2 y 8 (cantidad máxima de códigos de barras). Valor predeterminado: -1

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | un recuento de códigos de barras MaxiCode en modo de anexado estructurado. |

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String - Una cadena que representa este [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

