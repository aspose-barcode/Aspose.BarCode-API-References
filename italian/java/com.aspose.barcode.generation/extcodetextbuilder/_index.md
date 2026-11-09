---
title: "ExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Classe di supporto per la generazione automatica di codetext nella Modalità Codetext Esteso"
type: docs
weight: 38
url: /it/java/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

Classe di supporto per la generazione automatica di codetext nella Modalità Codetext Esteso
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Aggiunge codetext con Identificatore di Canale Esteso |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Aggiunge codetext semplice agli elementi di codetext esteso |
| [clear()](#clear--) | Cancella gli elementi di codetext esteso |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genera il codetext esteso dall'elenco degli elementi di generazione |
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


Aggiunge codetext con Identificatore di Canale Esteso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ECIEncoding | int | Identificatore di Canale Esteso |
| codetext | java.lang.String | Codetext in Unicode da aggiungere come elemento di codetext esteso con Identificatore di Canale Esteso |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Aggiunge codetext semplice agli elementi di codetext esteso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in unicode da aggiungere come elemento di Codetext esteso |

### clear() {#clear--}
```
public void clear()
```


Cancella gli elementi di codetext esteso

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Genera il codetext esteso dall'elenco degli elementi di generazione

**Returns:**
java.lang.String - Restituisce la stringa del codetext esteso
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

