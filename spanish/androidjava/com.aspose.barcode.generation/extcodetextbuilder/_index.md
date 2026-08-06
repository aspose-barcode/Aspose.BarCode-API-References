---
title: ExtCodetextBuilder
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Clase auxiliar para la generación automática de codetext del Modo de Codetext Extendido
type: docs
weight: 40
url: /es/androidjava/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

Clase auxiliar para la generación automática de codetext del Modo de Codetext Extendido
## Constructors

| Constructor | Descripción |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Methods

| Method | Descripción |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Adds codetext with Extended Channel Identifier |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Agrega texto de código simple a los elementos de texto de código extendido |
| [clear()](#clear--) | Elimina los elementos de texto de código extendido |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genera texto de código extendido a partir de la lista de elementos de generación |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Comprueba la necesidad de proteger el elemento anterior con "\\000000" |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtCodetextBuilder() {#ExtCodetextBuilder--}
```
public ExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


Adds codetext with Extended Channel Identifier

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| Codificación ECI | int | Identificador de Canal Extendido |
| texto de código | java.lang.String | Texto de código en Unicode para agregar como elemento de texto de código extendido con Identificador de Canal Extendido |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Agrega texto de código simple a los elementos de texto de código extendido

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| texto de código | java.lang.String | Texto de código en Unicode para agregar como elemento de texto de código extendido |

### clear() {#clear--}
```
public void clear()
```


Elimina los elementos de texto de código extendido

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendedCodetext() {#getExtendedCodetext--}
```
public abstract String getExtendedCodetext()
```


Genera texto de código extendido a partir de la lista de elementos de generación

**Returns:**
java.lang.String - Devuelve la cadena de texto de código extendido
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


Comprueba la necesidad de proteger el elemento anterior con "\\000000"

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| Índice | int | Índice en m\_List |

**Returns:**
boolean - Necesidad de proteger
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

