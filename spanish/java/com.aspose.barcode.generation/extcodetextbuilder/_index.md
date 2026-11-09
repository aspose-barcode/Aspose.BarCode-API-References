---
title: "ExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Clase auxiliar para la generación automática de codetext del Modo de Codetext Extendido"
type: docs
weight: 38
url: /es/java/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

Clase auxiliar para la generación automática de codetext del Modo de Codetext Extendido
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Añade codetext con Identificador de Canal Extendido |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Añade codetext simple a los elementos de codetext extendido |
| [clear()](#clear--) | Borra los elementos de codetext extendido |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genera texto de código extendido a partir de la lista de elementos de generación |
| [hashCode()](#hashCode--) |  |
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
public final void addECICodetext(int ECIEncoding, String codetext)
```


Añade codetext con Identificador de Canal Extendido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ECIEncoding | int | Identificador de Canal Extendido |
| codetext | java.lang.String | Codetext en unicode para añadir como elemento de codetext extendido con Identificador de Canal Extendido |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Añade codetext simple a los elementos de codetext extendido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codetext | java.lang.String | Codetext en unicode para agregar como elemento de texto de código extendido |

### clear() {#clear--}
```
public void clear()
```


Borra los elementos de codetext extendido

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

