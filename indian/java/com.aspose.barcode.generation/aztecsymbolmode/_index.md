---
title: "AztecSymbolMode"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "Aztec प्रतीक मोड निर्दिष्ट करता है।"
type: docs
weight: 72
url: /hi/java/com.aspose.barcode.generation/aztecsymbolmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AztecSymbolMode extends Enum<AztecSymbolMode>
```

Aztec प्रतीक मोड निर्दिष्ट करता है।

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC);
>       generator.setCodeText("125");
>       generator.getParameters().getBarcode().getAztec().setAztecSymbolMode(AztecSymbolMode.RUNE);
>       generator.save("test.png");
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AUTO](#AUTO) | Aztec के लिए सर्वोत्तम प्रतीक (COMPACT या FULL-range) को स्वचालित रूप से चुनने को निर्दिष्ट करता है। |
| [COMPACT](#COMPACT) | Aztec के लिए COMPACT प्रतीक को निर्दिष्ट करता है। |
| [FULL_RANGE](#FULL-RANGE) | Aztec के लिए FULL-range प्रतीक को निर्दिष्ट करता है। |
| [RUNE](#RUNE) | Aztec के लिए RUNE प्रतीक को निर्दिष्ट करता है। |
## मेथड्स

| मेथड | विवरण |
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


Aztec के लिए सर्वोत्तम प्रतीक (COMPACT या FULL-range) को स्वचालित रूप से चुनने को निर्दिष्ट करता है। यह डिफ़ॉल्ट मान है।

### COMPACT {#COMPACT}
```
public static final AztecSymbolMode COMPACT
```


Aztec के लिए COMPACT प्रतीक को निर्दिष्ट करता है। Aztec COMPACT प्रतीक केवल 1, 2, 3 या 4 लेयर की अनुमति देता है।

### FULL_RANGE {#FULL-RANGE}
```
public static final AztecSymbolMode FULL_RANGE
```


Aztec के लिए FULL-range प्रतीक को निर्दिष्ट करता है। Aztec FULL-range प्रतीक 1 से 32 लेयर तक की अनुमति देता है।

### RUNE {#RUNE}
```
public static final AztecSymbolMode RUNE
```


Aztec के लिए RUNE प्रतीक को निर्दिष्ट करता है। Aztec Runes छोटे लेकिन विशिष्ट मशीन-पढ़ने योग्य चिह्नों की श्रृंखला हैं। यह केवल 0 से 255 तक की संख्या मान की अनुमति देता है।

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static AztecSymbolMode fromValue(int value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

