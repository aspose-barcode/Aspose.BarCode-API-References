---
title: QRExtendedParameters
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Almacena información de QR Structured Append del código de barras reconocido
type: docs
weight: 42
url: /es/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Almacena información de QR Structured Append del código de barras reconocido

Este ejemplo muestra cómo obtener los datos QR Structured Append

```
{
```
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Nivel de corrección de errores Reed-Solomon del código de barras reconocido. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versión del MicroQR Code reconocido. |
| [getQRErrorLevel()](#getQRErrorLevel--) | Nivel de corrección de errores Reed-Solomon del código de barras reconocido. |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | Obtiene el índice del código de barras en modo QR structured append. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | Obtiene la cantidad de códigos de barras en modo QR structured append. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | Obtiene los datos de paridad del modo de anexado estructurado QR. |
| [getQRVersion()](#getQRVersion--) | Versión del código QR reconocido. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Versión del código RectMicroQR reconocido. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Obtiene el índice del código de barras en modo QR structured append. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Obtiene la cantidad de códigos de barras en modo QR structured append. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Obtiene los datos de paridad del modo de anexado estructurado QR. |
| [getVersion()](#getVersion--) | Versión del código QR reconocido. |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [isEmpty()](#isEmpty--) | Comprueba si todos los parámetros tienen solo valores predeterminados |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Devuelve un valor que indica si el primer valor de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) es igual al segundo. |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Devuelve un valor que indica si el primer valor de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) es diferente del segundo. |
| [toString()](#toString--) | Devuelve una representación en cadena legible por humanos de este [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor System.Object para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
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


Nivel de corrección de errores Reed-Solomon del código de barras reconocido. De bajo a alto: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Versión del código MicroQR reconocido. De M1 a M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


Nivel de corrección de errores Reed-Solomon del código de barras reconocido. De bajo a alto: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


Obtiene el índice del código de barras en modo de anexado estructurado QR. El índice comienza en 0. El valor predeterminado es -1.

Valor: La cantidad del código de barras en modo de anexado estructurado QR.

**Returns:**
int - el índice del código de barras en modo de anexado estructurado QR.
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


Obtiene la cantidad de códigos de barras en modo de anexado estructurado QR. El valor predeterminado es -1.

Valor: La cantidad del código de barras en modo de anexado estructurado QR.

**Returns:**
int - la cantidad de códigos de barras en modo de anexado estructurado QR.
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


Obtiene los datos de paridad del modo de anexado estructurado QR. El valor predeterminado es -1.

Valor: El índice del código de barras en modo de anexado estructurado QR.

**Returns:**
int - los datos de paridad del modo de anexado estructurado QR.
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


Versión del código QR reconocido. De Version1 a Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Versión del código RectMicroQR reconocido. De R7x43 a R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Obtiene el índice del código de barras en modo de anexado estructurado QR. El índice comienza en 0. El valor predeterminado es -1.

Valor: La cantidad del código de barras en modo de anexado estructurado QR.

**Returns:**
int - el índice del código de barras en modo de anexado estructurado QR.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Obtiene la cantidad de códigos de barras en modo de anexado estructurado QR. El valor predeterminado es -1.

Valor: La cantidad del código de barras en modo de anexado estructurado QR.

**Returns:**
int - la cantidad de códigos de barras en modo de anexado estructurado QR.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Obtiene los datos de paridad del modo de anexado estructurado QR. El valor predeterminado es -1.

Valor: El índice del código de barras en modo de anexado estructurado QR.

**Returns:**
int - los datos de paridad del modo de anexado estructurado QR.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versión del código QR reconocido. De Version1 a Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Comprueba si todos los parámetros tienen solo valores predeterminados

Valor: Devuelve  **true**  si todos los parámetros tienen solo valores predeterminados; de lo contrario,  **false** .

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


Devuelve un valor que indica si el primer valor de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) es igual al segundo.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Un primer valor comparado |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Un segundo valor comparado |

**Returns:**
boolean -  **true**  si el primero tiene el mismo valor que el segundo; de lo contrario,  **false** .
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


Devuelve un valor que indica si el primer valor de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) es diferente del segundo.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Un primer valor comparado |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Un segundo valor comparado |

**Returns:**
boolean -  **true**  si el primero tiene un valor diferente al segundo; de lo contrario,  **false** .
### toString() {#toString--}
```
public String toString()
```


Devuelve una representación en cadena legible por humanos de este [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String - Una cadena que representa este [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
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

