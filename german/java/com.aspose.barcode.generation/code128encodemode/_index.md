---
title: "Code128EncodeMode"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Kodierungsmodus für Code128-Barcodes."
type: docs
weight: 78
url: /de/java/com.aspose.barcode.generation/code128encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Code128EncodeMode extends Enum<Code128EncodeMode>
```

Kodierungsmodus für Code128-Barcodes.  Code 128  Spezifikation.

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
## Felder

| Feld | Beschreibung |
| --- | --- |
| [AUTO](#AUTO) | Kodiert den Code-Text im klassischen ISO‑15417‑Modus. |
| [CODE_A](#CODE-A) | Kodiert den Code-Text nur im 128A‑Zeichensatz. |
| [CODE_AB](#CODE-AB) | Kodiert den Code-Text nur im 128A‑ und 128B‑Zeichensatz. |
| [CODE_AC](#CODE-AC) | Kodiert den Code-Text nur im 128A‑ und 128C‑Zeichensatz. |
| [CODE_B](#CODE-B) | Kodiert den Code-Text nur im 128B‑Zeichensatz. |
| [CODE_BC](#CODE-BC) | Kodiert den Code-Text nur im 128B‑ und 128C‑Zeichensatz. |
| [CODE_C](#CODE-C) | Codetext nur im 128C-Codeset codieren. |
## Methoden

| Methode | Beschreibung |
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


Codetext im klassischen ISO‑15417‑Modus codieren. Der Modus sollte in allen üblichen Fällen verwendet werden.

### CODE_A {#CODE-A}
```
public static final Code128EncodeMode CODE_A
```


Kodiert den Code-Text nur im 128A‑Zeichensatz.

### CODE_AB {#CODE-AB}
```
public static final Code128EncodeMode CODE_AB
```


Kodiert den Code-Text nur im 128A‑ und 128B‑Zeichensatz.

### CODE_AC {#CODE-AC}
```
public static final Code128EncodeMode CODE_AC
```


Kodiert den Code-Text nur im 128A‑ und 128C‑Zeichensatz.

### CODE_B {#CODE-B}
```
public static final Code128EncodeMode CODE_B
```


Kodiert den Code-Text nur im 128B‑Zeichensatz.

### CODE_BC {#CODE-BC}
```
public static final Code128EncodeMode CODE_BC
```


Kodiert den Code-Text nur im 128B‑ und 128C‑Zeichensatz.

### CODE_C {#CODE-C}
```
public static final Code128EncodeMode CODE_C
```


Codetext nur im 128C-Codeset codieren.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
### fromValue(int value) {#fromValue-int-}
```
public static Code128EncodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Code128EncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

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
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

