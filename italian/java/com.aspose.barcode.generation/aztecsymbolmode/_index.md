---
title: "AztecSymbolMode"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Specifica la modalità del simbolo Aztec."
type: docs
weight: 72
url: /it/java/com.aspose.barcode.generation/aztecsymbolmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AztecSymbolMode extends Enum<AztecSymbolMode>
```

Specifica la modalità del simbolo Aztec.

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC);
>       generator.setCodeText("125");
>       generator.getParameters().getBarcode().getAztec().setAztecSymbolMode(AztecSymbolMode.RUNE);
>       generator.save("test.png");
> ```
## Campi

| Campo | Descrizione |
| --- | --- |
| [AUTO](#AUTO) | Specifica di selezionare automaticamente il miglior simbolo (COMPACT o FULL-range) per Aztec. |
| [COMPACT](#COMPACT) | Specifica il simbolo COMPACT per Aztec. |
| [FULL_RANGE](#FULL-RANGE) | Specifica il simbolo FULL-range per Aztec. |
| [RUNE](#RUNE) | Specifica il simbolo RUNE per Aztec. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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
public static final AztecSymbolMode AUTO
```


Specifica di selezionare automaticamente il miglior simbolo (COMPACT o FULL-range) per Aztec. Questo è il valore predefinito.

### COMPACT {#COMPACT}
```
public static final AztecSymbolMode COMPACT
```


Specifica il simbolo COMPACT per Aztec. Il simbolo COMPACT di Aztec consente solo 1, 2, 3 o 4 livelli.

### FULL_RANGE {#FULL-RANGE}
```
public static final AztecSymbolMode FULL_RANGE
```


Specifica il simbolo FULL-range per Aztec. Il simbolo FULL-range di Aztec consente da 1 a 32 livelli.

### RUNE {#RUNE}
```
public static final AztecSymbolMode RUNE
```


Specifica il simbolo RUNE per Aztec. Le rune di Aztec sono una serie di piccoli ma distinti segni leggibili dalla macchina. Consente solo valori numerici da 0 a 255.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static AztecSymbolMode fromValue(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode)
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
public static AztecSymbolMode valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode)
### values() {#values--}
```
public static AztecSymbolMode[] values()
```




**Returns:**
com.aspose.barcode.generation.AztecSymbolMode[]
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

