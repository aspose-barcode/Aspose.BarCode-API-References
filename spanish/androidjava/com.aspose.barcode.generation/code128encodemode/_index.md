---
title: "Code128EncodeMode"
second_title: "Referencia de API de Aspose.BarCode para Android mediante Java"
description: "Modo de codificación para códigos de barras Code128."
type: docs
weight: 79
url: /es/androidjava/com.aspose.barcode.generation/code128encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Code128EncodeMode extends Enum<Code128EncodeMode>
```

Modo de codificación para códigos de barras Code128.  Especificación Code 128.

--------------------

> ```
> Thos code demonstrates how to generate code 128 with different encodings
>  
> 
>  //Generate code 128 with ISO 15417 encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO);
>  generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG);
> 
>  //Generate code 128 only with Codeset A encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A);
>  generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);
> ```
## Campos

| Campo | Descripción |
| --- | --- |
| [AUTO](#AUTO) | Codifica el texto del código en modo clásico ISO 15417. |
| [CODE_A](#CODE-A) | Codifica el texto del código solo en el conjunto de códigos 128A. |
| [CODE_AB](#CODE-AB) | Codifique el texto de código solo en los conjuntos de códigos 128A y 128B. |
| [CODE_AC](#CODE-AC) | Codifique el texto de código solo en los conjuntos de códigos 128A y 128C. |
| [CODE_B](#CODE-B) | Codifique el texto de código solo en el conjunto de códigos 128B. |
| [CODE_BC](#CODE-BC) | Codifique el texto de código solo en los conjuntos de códigos 128B y 128C. |
| [CODE_C](#CODE-C) | Codifique el texto de código solo en el conjunto de códigos 128C. |
## Métodos

| Método | Descripción |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(int value)](#valueOf-int-) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final Code128EncodeMode AUTO
```


Codifique el texto de código en el modo clásico ISO 15417. El modo debe usarse en todos los casos ordinarios.

### CODE_A {#CODE-A}
```
public static final Code128EncodeMode CODE_A
```


Codifica el texto del código solo en el conjunto de códigos 128A.

### CODE_AB {#CODE-AB}
```
public static final Code128EncodeMode CODE_AB
```


Codifique el texto de código solo en los conjuntos de códigos 128A y 128B.

### CODE_AC {#CODE-AC}
```
public static final Code128EncodeMode CODE_AC
```


Codifique el texto de código solo en los conjuntos de códigos 128A y 128C.

### CODE_B {#CODE-B}
```
public static final Code128EncodeMode CODE_B
```


Codifique el texto de código solo en el conjunto de códigos 128B.

### CODE_BC {#CODE-BC}
```
public static final Code128EncodeMode CODE_BC
```


Codifique el texto de código solo en los conjuntos de códigos 128B y 128C.

### CODE_C {#CODE-C}
```
public static final Code128EncodeMode CODE_C
```


Codifique el texto de código solo en el conjunto de códigos 128C.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static Code128EncodeMode fromValue(int value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(int value) {#valueOf-int-}
```
public static Code128EncodeMode valueOf(int value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Code128EncodeMode valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### values() {#values--}
```
public static Code128EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Code128EncodeMode[]
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

