---
title: "DataMatrixParametersUI"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Wrapper de UI para la clase com.aspose.barcode.generation.DataMatrixParameters."
type: docs
weight: 14
url: /es/java/com.aspose.barcode.barcodecontrol/datamatrixparametersui/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParametersUI
```

Wrapper de UI para la clase com.aspose.barcode.generation.DataMatrixParameters.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Relación altura/ancho del módulo de código de barras 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Obtiene la codificación ECI. |
| [getEccType()](#getEccType--) | Obtiene un tipo ECC de Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | Modo de codificación del código de barras Datamatrix. |
| [getMacroCharacters()](#getMacroCharacters--) | Protocolo para caracteres Macro en la primera posición (solo ECC 200). |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | ID de código de barras para el modo Structured Append. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Recuento de códigos de barras para el modo Structured Append. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | ID de archivo para el modo Structured Append. |
| [getVersion()](#getVersion--) | Tamaño del símbolo DataMatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Relación altura/ancho del módulo de código de barras 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Establece la codificación ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Establece un tipo ECC de Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Modo de codificación del código de barras Datamatrix. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Protocolo para caracteres Macro en la primera posición (solo ECC 200). |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | ID de código de barras para el modo Structured Append. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Recuento de códigos de barras para el modo Structured Append. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | ID de archivo para el modo Structured Append. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Tamaño del símbolo DataMatrix. |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
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


Obtiene la codificación ECI. Se usa cuando EncodeMode es Auto.

**Returns:**
int - codificación ECI.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Obtiene un tipo ECC de Datamatrix. Valor predeterminado: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Modo de codificación del código de barras Datamatrix. Valor predeterminado: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Protocolo para caracteres Macro en la primera posición (solo ECC 200).

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


ID de código de barras para el modo Structured Append.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Recuento de códigos de barras para el modo Structured Append.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


ID de archivo para el modo Structured Append.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Tamaño del símbolo DataMatrix.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
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


Establece la codificación ECI. Se usa cuando EncodeMode es Auto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Codificación ECI. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Establece un tipo ECC de Datamatrix. Valor predeterminado: DataMatrixEccType.Ecc200.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | un tipo ECC de Datamatrix. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Modo de codificación del código de barras Datamatrix. Valor predeterminado: EncodeMode.Auto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Protocolo para caracteres Macro en la primera posición (solo ECC 200).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
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


ID de código de barras para el modo Structured Append.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Recuento de códigos de barras para el modo Structured Append.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


ID de archivo para el modo Structured Append.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Tamaño del símbolo DataMatrix.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - Una cadena que representa este [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).
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

