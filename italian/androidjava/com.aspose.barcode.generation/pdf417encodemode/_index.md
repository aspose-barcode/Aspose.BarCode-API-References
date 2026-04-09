---
title: Pdf417EncodeMode
second_title: Aspose.BarCode per Android via Java API Reference
description: Modalità di codifica del codice a barre Pdf417
type: docs
weight: 99
url: /it/androidjava/com.aspose.barcode.generation/pdf417encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Pdf417EncodeMode extends Enum<Pdf417EncodeMode>
```

Modalità di codifica del codice a barre Pdf417
## Campi

| Campo | Descrizione |
| --- | --- |
| [AUTO](#AUTO) | In modalità Auto, il CodeText è codificato con la massima compattezza dei dati. |
| [BINARY](#BINARY) | In modalità Binaria, il CodeText è codificato con la massima compattezza dei dati. |
| [ECI](#ECI) | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. |
| [EXTENDED](#EXTENDED) |  |
## Methods

| Method | Descrizione |
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
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final Pdf417EncodeMode AUTO
```


In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. I caratteri Unicode vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione.

### BINARY {#BINARY}
```
public static final Pdf417EncodeMode BINARY
```


In modalità Binary, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene sollevata un'eccezione.

### ECI {#ECI}
```
public static final Pdf417EncodeMode ECI
```


In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. Si prega di notare che alcuni scanner vecchi (pre‑2006) potrebbero non supportare questa modalità.

### EXTENDED {#EXTENDED}
```
public static final Pdf417EncodeMode EXTENDED
```


Modalità estesa che supporta più modalità ECI.

È meglio utilizzare Pdf417ExtCodetextBuilder per la generazione di codetext esteso.

Utilizza la proprietà Display2DText per impostare il testo visibile rimuovendo i caratteri di gestione.

Gli identificatori ECI sono impostati come barra singola e identificatore a sei cifre "\\000026" - identificatore ECI UTF8

Tutti i caratteri Unicode dopo l'identificatore ECI vengono codificati automaticamente nel set di caratteri corretto.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static Pdf417EncodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
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
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Pdf417EncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### values() {#values--}
```
public static Pdf417EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Pdf417EncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

