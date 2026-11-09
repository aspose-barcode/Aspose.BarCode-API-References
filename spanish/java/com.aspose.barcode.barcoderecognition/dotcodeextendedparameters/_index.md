---
title: "DotCodeExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Almacena datos especiales del código de barras DotCode reconocido"
type: docs
weight: 31
url: /es/java/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

Almacena datos especiales del código de barras DotCode reconocido

Este ejemplo muestra cómo obtener los valores sin procesar de DotCode

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");
 
 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [getClass()](#getClass--) |  |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Obtiene el ID del código de barras de modo de anexado estructurado DotCode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Obtiene la cantidad de códigos de barras de modo de anexado estructurado DotCode. |
| [hashCode()](#hashCode--) | Devuelve el código hash de esta instancia. |
| [isEmpty()](#isEmpty--) | Comprueba si todos los parámetros tienen solo valores predeterminados. |
| [isReaderInitialization()](#isReaderInitialization--) | Indica si el código se utiliza para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

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
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Obtiene el ID del código de barras de modo de anexado estructurado DotCode. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1.

Valor: El ID del código de barras de modo de anexado estructurado DotCode.

**Returns:**
int - el ID del código de barras de modo de anexado estructurado DotCode.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Obtiene la cantidad de códigos de barras de modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor entre 1 y 35.

Valor: El recuento del código de barras de modo de anexado estructurado DotCode.

**Returns:**
int - el recuento de códigos de barras de modo de anexado estructurado DotCode.
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
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
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


Devuelve una representación de cadena legible por humanos de este [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - Una cadena que representa este [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).
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

