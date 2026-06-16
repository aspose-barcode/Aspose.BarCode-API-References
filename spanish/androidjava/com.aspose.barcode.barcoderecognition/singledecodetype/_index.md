---
title: SingleDecodeType
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Tipo de decodificación única.
type: docs
weight: 48
url: /es/androidjava/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

Tipo de decodificación único. Consulte el tipo de decodificación para obtener una instancia.

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## Methods

| Method | Descripción |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Devuelve un valor que indica si esta instancia está incluida en la lista especificada. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype). |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | Convierte la instancia de SingleDecodeType a su representación de cadena equivalente, usando el siguiente formato: \"Index:-1; Name:None\". |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Convierte la instancia de SingleDecodeType a su representación de cadena equivalente, usando el siguiente formato: \"Index:-1; Name:None\". |
| [getTypeIndex()](#getTypeIndex--) | Obtiene un índice del tipo de decodificación |
| [getTypeName()](#getTypeName--) | Obtiene un nombre del tipo de decodificación |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | Convierte la representación en cadena del nombre de un SingleDecodeType a su instancia. |
| [toString()](#toString--) | Método sobrescrito que representa SingleDecodeType como la cadena Name. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Convierte la representación en cadena de un BaseDecodeType a su instancia, habiendo determinado el tipo concreto. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Convierte la representación en cadena de un MultiDecodeType a su instancia. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Convierte la representación en cadena de un SingleDecodeType a su instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


Devuelve un valor que indica si esta instancia está incluida en la lista especificada.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Arreglo de tipos de decodificación únicos y múltiples |

**Returns:**
boolean - El valor es verdadero si se incluyen alguno(s) tipos en
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| otro | com.aspose.barcode.barcoderecognition.MultiDecodeType |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor System.Object para comparar con esta instancia. |

**Returns:**
boolean - Verdadero si obj tiene el mismo valor que esta instancia; de lo contrario, falso.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getString() {#getString--}
```
public String getString()
```


Convierte la instancia de SingleDecodeType a su representación de cadena equivalente, usando el siguiente formato: \"Index:-1; Name:None\".

**Returns:**
java.lang.String - Una cadena que representa el valor completo del tipo de decodificación único
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


Convierte la instancia de SingleDecodeType a su representación de cadena equivalente, usando el siguiente formato: \"Index:-1; Name:None\".

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | La instancia SingleDecodeType a convertir |

**Returns:**
java.lang.String - Una cadena que representa el valor completo del tipo de decodificación único dado
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Obtiene un índice del tipo de decodificación

**Returns:**
short - El índice del tipo de decodificación
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Obtiene un nombre del tipo de decodificación

**Returns:**
java.lang.String - El nombre del tipo de decodificación
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseSingleDecodeType(String stringDecodeType) {#parseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType parseSingleDecodeType(String stringDecodeType)
```


Convierte la representación en cadena del nombre de un SingleDecodeType a su instancia.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| stringDecodeType | java.lang.String | Una cadena que contiene el nombre de un SingleDecodeType para convertir. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


Método sobrescrito que representa SingleDecodeType como la cadena Name.

**Returns:**
java.lang.String - Una cadena que representa el nombre del tipo de decodificación único
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Convierte la representación en cadena de un BaseDecodeType a su instancia, habiendo determinado el tipo concreto. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena que contiene una representación de MultiDecodeType para convertir. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

de lo contrario devuelve un tipo indefinido. o MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Convierte la representación en cadena de un MultiDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena que contiene una representación de MultiDecodeType para convertir. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Se devuelve un MultiDecodeType real cuando la conversión se ha completado con éxito;

de lo contrario devuelve un tipo indefinido. o MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena que contiene un SingleDecodeType en el formato "EAN8" o "EAN13" o "CodaBar"... para convertir. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

de lo contrario devuelve un tipo indefinido. o SingleDecodeType (-1, "None").
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

