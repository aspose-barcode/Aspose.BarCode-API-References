---
title: BaseDecodeType
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Clase base para MultiDecodeType y SingleDecodeType.
type: docs
weight: 23
url: /es/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Clase base para MultiDecodeType y SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | Descripción |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Determina si alguno de los tipos de decodificación proporcionados está incluido en |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [equals(Object other)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Convierte la representación en cadena de un BaseDecodeType a su instancia, habiendo determinado el tipo concreto. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Convierte la representación en cadena de un MultiDecodeType a su instancia. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Convierte la representación en cadena de un SingleDecodeType a su instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Determina si alguno de los tipos de decodificación proporcionados está incluido en

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipos a verificar. |

**Returns:**
boolean - El valor es verdadero si algún tipo está incluido en.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| otro | com.aspose.barcode.barcoderecognition.MultiDecodeType | Un valor java.lang.Object para comparar con esta instancia. |

**Returns:**
boolean - Verdadero si obj tiene el mismo valor que esta instancia; de lo contrario, falso.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un valor java.lang.Object para comparar con esta instancia. |

**Returns:**
boolean - Verdadero si obj tiene el mismo valor que esta instancia; de lo contrario, falso.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| otro | java.lang.Object | Un valor java.lang.Object para comparar con esta instancia. |

**Returns:**
boolean - Verdadero si obj tiene el mismo valor que esta instancia; de lo contrario, falso.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

