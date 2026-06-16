---
title: SymbologyEncodeType
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Tipo de codificación de simbología.
type: docs
weight: 67
url: /es/androidjava/com.aspose.barcode.generation/symbologyencodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
```
public class SymbologyEncodeType extends BaseEncodeType
```

Tipo de codificación de simbología. Consulte EncodeTypes para obtener una instancia.

--------------------

> ```
> Create symbology encode type
>  
>  SymbologyEncodeType symbologyType = EncodeTypes.GS_1_CODE_128
> ```
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de BaseEncodeType. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Obtiene una clasificación de esta simbología. |
| [getString()](#getString--) | Convierte la instancia de BaseEncodeType a su representación de cadena equivalente. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Convierte la instancia de BaseEncodeType a su representación de cadena equivalente. |
| [getTypeIndex()](#getTypeIndex--) | Obtiene un índice del tipo de codificación |
| [getTypeName()](#getTypeName--) | Obtiene un nombre del tipo de codificación |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Convierte la representación de cadena del nombre de un BaseEncodeType a su instancia. |
| [toString()](#toString--) | Devuelve el nombre del BaseEncodeType dado como una cadena. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Convierte la representación de cadena de un BaseEncodeType a su instancia. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Convierte la representación de cadena de un BaseEncodeType a su instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de BaseEncodeType.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| otro | java.lang.Object | Un valor de BaseEncodeType para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


Obtiene una clasificación de esta simbología.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Convierte la instancia de BaseEncodeType a su representación de cadena equivalente. El formato de cadena es: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - Una cadena que representa el valor completo del tipo de codificación
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Convierte la instancia de BaseEncodeType a su representación de cadena equivalente. El formato de cadena es: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | La instancia de BaseEncodeType a convertir |

**Returns:**
java.lang.String - Una cadena que representa el valor completo del tipo de codificación dado
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Obtiene un índice del tipo de codificación

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Obtiene un nombre del tipo de codificación

**Returns:**
java.lang.String
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




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


Convierte la representación de cadena del nombre de un BaseEncodeType a su instancia.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| stringEncodeType | java.lang.String | Una cadena que contiene el nombre de un BaseEncodeType para convertir. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Devuelve el nombre del BaseEncodeType dado como una cadena.

**Returns:**
java.lang.String - Una cadena que representa el nombre del tipo de codificación
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Convierte la representación de cadena de un BaseEncodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena con el formato "Index:-1; Name:None" para convertir. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | Un SingleEncodeType real se devuelve cuando la conversión se ha completado con éxito; |

de lo contrario devuelve null. |

**Returns:**
boolean -  **true**  si s se convirtió correctamente; de lo contrario,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Convierte la representación de cadena de un BaseEncodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena con el formato "Index:-1; Name:None" para convertir. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | Un SingleEncodeType real se devuelve cuando la conversión se ha completado con éxito; |

de lo contrario devuelve null. |

**Returns:**
boolean -  **true**  si s se convirtió correctamente; de lo contrario,  **false** .
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

