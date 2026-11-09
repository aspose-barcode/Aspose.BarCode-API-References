---
title: "FontUnit"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Definisce un formato particolare per il testo includendo la dimensione del carattere e gli attributi di stile, dove la dimensione è nella proprietà Unit value."
type: docs
weight: 42
url: /it/java/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

Definisce un formato specifico per il testo, includendo il tipo di carattere, la dimensione e gli attributi di stile, dove la dimensione è nella proprietà valore Unità.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | Ottiene il nome del carattere di questo Font. |
| [getSize()](#getSize--) | Ottiene la dimensione di questo FontUnit in Unit value. |
| [getStyle()](#getStyle--) | Ottiene le informazioni di stile per questo FontUnit. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Imposta il nome del carattere di questo Font. |
| [setStyle(int value)](#setStyle-int-) | Imposta le informazioni di stile per questo FontUnit. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Ottiene il nome del carattere di questo Font.

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public Unit getSize()
```


Ottiene la dimensione di questo FontUnit in Unit value.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStyle() {#getStyle--}
```
public int getStyle()
```


Ottiene le informazioni di stile per questo FontUnit.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Imposta il nome del carattere di questo Font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Imposta le informazioni di stile per questo FontUnit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

