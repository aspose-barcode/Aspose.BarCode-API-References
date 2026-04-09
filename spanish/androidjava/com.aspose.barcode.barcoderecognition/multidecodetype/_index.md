---
title: MultiDecodeType
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Tipo de decodificación compuesta.
type: docs
weight: 37
url: /es/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

Tipo de decodificación compuesta.

Este ejemplo muestra cómo crear tipos MultiDecode compuestos que combinan SingleDecodeType y tipos MultiDecode.

```

```
## Constructors

| Constructor | Descripción |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Inicializa una nueva instancia de la clase MultiDecodeType. |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Inicializa una nueva instancia de la clase MultiDecodeType. |
## Methods

| Method | Descripción |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Agrega un [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) más al MultiDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Comprueba si esto contiene todos los tipos de códigos de barras. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Contiene alguno de los tipos. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de MultiDecodeType. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Devuelve un valor que indica si esta colección de tipos de decodificación contiene solo el valor especificado de [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype). |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de MultiDecodeType. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Excluye [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) del MultiDecodeType y devuelve una nueva instancia de MultiDecodeType. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Representa una lista de tipos simples. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Devuelve un número de tipos simples. |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Método sobrescrito que representa MultiDecodeType como una cadena. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Convierte la representación en cadena de un BaseDecodeType a su instancia, habiendo determinado el tipo concreto. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Convierte la representación en cadena de un MultiDecodeType a su instancia. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Convierte la representación en cadena de un SingleDecodeType a su instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


Inicializa una nueva instancia de la clase MultiDecodeType.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Arreglo de tipos de decodificación simples. |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


Inicializa una nueva instancia de la clase MultiDecodeType.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Arreglo de tipos de decodificación múltiples y simples. |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


Agrega un [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) más al MultiDecodeType.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un Single DecodeType para agregar a la lista. |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Comprueba si esto contiene todos los tipos de códigos de barras.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipos de códigos de barras simples o múltiples de entrada. |

**Returns:**
boolean - El valor es verdadero si todos los tipos están incluidos en
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Contiene alguno de los tipos.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipos de decodificación. |

**Returns:**
boolean - El valor es verdadero si se incluyen alguno(s) tipos en
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de MultiDecodeType.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| otro | com.aspose.barcode.barcoderecognition.MultiDecodeType | Un valor MultiDecodeType para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Devuelve un valor que indica si esta colección de tipos de decodificación contiene solo el valor especificado de [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un valor [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) para comparar con esta colección de tipos de decodificación. |

**Returns:**
boolean -  **true**  si esta colección contiene solo el tipo de decodificación especificado; de lo contrario,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de MultiDecodeType.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor System.Object para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


Excluye [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) del MultiDecodeType y devuelve una nueva instancia de MultiDecodeType.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un Single DecodeType que será excluido. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Nueva instancia de MultiDecodeType con SingleDecodeType excluido.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


Representa una lista de tipos simples.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - Lista de tipos simples
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


Devuelve un número de tipos simples.

**Returns:**
int
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




### toString() {#toString--}
```
public String toString()
```


Método sobrescrito que representa MultiDecodeType como una cadena.

**Returns:**
java.lang.String - Una cadena que representa una instancia de MultiDecodeType como "singleDecodeType1, singleDecodeType2, ..."

 **"AllSupportedTypes"**  returns when all types are included.
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

