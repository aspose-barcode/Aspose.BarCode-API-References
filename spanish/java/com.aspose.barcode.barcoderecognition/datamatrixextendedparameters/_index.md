---
title: "DataMatrixExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Almacena datos especiales del código de barras DataMatrix reconocido"
type: docs
weight: 29
url: /es/java/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

Almacena datos especiales del código de barras DataMatrix reconocido

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming));
>  }
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de  DataMatrixExtendedParameters . |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Obtiene el ID del código de barras en modo Structured Append de DataMatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Obtiene la cantidad de códigos de barras en modo de anexado estructurado de DataMatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Obtiene el ID del código de barras en modo Structured Append de DataMatrix. |
| [hashCode()](#hashCode--) | Devuelve el código hash de esta instancia. |
| [isEmpty()](#isEmpty--) | Comprueba si todos los parámetros tienen solo valores predeterminados. |
| [isReaderProgramming()](#isReaderProgramming--) | Indica si el código se utiliza para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este DataMatrixExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de  DataMatrixExtendedParameters .

**Parameters:**
| Parámetro | Tipo | Descripción |
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
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


Obtiene el ID del código de barras en modo de anexado estructurado de DataMatrix. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1.

Valor: El ID del código de barras en modo de anexado estructurado de DataMatrix.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Obtiene la cantidad de códigos de barras en modo de anexado estructurado de DataMatrix. El valor predeterminado es -1. La cantidad debe ser un valor entre 1 y 35.

Valor: La cantidad de códigos de barras en modo de anexado estructurado de DataMatrix.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


Obtiene el ID del código de barras en modo de anexado estructurado de DataMatrix. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1.

Valor: El ID del código de barras en modo de anexado estructurado de DataMatrix.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash de esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Comprueba si todos los parámetros tienen solo valores predeterminados.

Valor: Devuelve  **true**  si todos los parámetros tienen solo valores predeterminados; de lo contrario,  **false** .

**Returns:**
boolean
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


Indica si el código se utiliza para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false.

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




### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este DataMatrixExtendedParameters.

**Returns:**
java.lang.String - Una cadena que representa este DataMatrixExtendedParameters.
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

