---
title: Code128EncodeMode
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Code128 बारकोड के लिए एन्कोडिंग मोड।
type: docs
weight: 80
url: /hi/androidjava/com.aspose.barcode.generation/code128encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Code128EncodeMode extends Enum<Code128EncodeMode>
```

Code128 बारकोड के लिए एन्कोडिंग मोड।  Code 128  विनिर्देश।

--------------------

> ```
> Following code demonstrates how to generate code 128 with different encodings
>  
> 
>  //Generate code 128 with ISO 15417 encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO);
>  generator.save(filePath, BarCodeImageFormat.PNG);
> 
>  //Generate code 128 only with Codeset A encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A);
>  generator.save(filePath, BarCodeImageFormat.PNG);
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AUTO](#AUTO) | क्लासिक ISO 15417 मोड में कोडटेक्स्ट एन्कोड करें। |
| [CODE_A](#CODE-A) | केवल 128A कोडसेट में कोडटेक्स्ट एन्कोड करें। |
| [CODE_AB](#CODE-AB) | केवल 128A और 128B कोडसेट्स में कोडटेक्स्ट एन्कोड करें। |
| [CODE_AC](#CODE-AC) | केवल 128A और 128C कोडसेट्स में कोडटेक्स्ट एन्कोड करें। |
| [CODE_B](#CODE-B) | केवल 128B कोडसेट में कोडटेक्स्ट एन्कोड करें। |
| [CODE_BC](#CODE-BC) | केवल 128B और 128C कोडसेट्स में कोडटेक्स्ट एन्कोड करें। |
| [CODE_C](#CODE-C) | केवल 128C कोडसेट में कोडटेक्स्ट एन्कोड करें। |
## Methods

| Method | विवरण |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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


क्लासिक ISO 15417 मोड में कोडटेक्स्ट एन्कोड करें। इस मोड का उपयोग सभी सामान्य मामलों में किया जाना चाहिए।

### CODE_A {#CODE-A}
```
public static final Code128EncodeMode CODE_A
```


केवल 128A कोडसेट में कोडटेक्स्ट एन्कोड करें।

### CODE_AB {#CODE-AB}
```
public static final Code128EncodeMode CODE_AB
```


केवल 128A और 128B कोडसेट्स में कोडटेक्स्ट एन्कोड करें।

### CODE_AC {#CODE-AC}
```
public static final Code128EncodeMode CODE_AC
```


केवल 128A और 128C कोडसेट्स में कोडटेक्स्ट एन्कोड करें।

### CODE_B {#CODE-B}
```
public static final Code128EncodeMode CODE_B
```


केवल 128B कोडसेट में कोडटेक्स्ट एन्कोड करें।

### CODE_BC {#CODE-BC}
```
public static final Code128EncodeMode CODE_BC
```


केवल 128B और 128C कोडसेट्स में कोडटेक्स्ट एन्कोड करें।

### CODE_C {#CODE-C}
```
public static final Code128EncodeMode CODE_C
```


केवल 128C कोडसेट में कोडटेक्स्ट एन्कोड करें।

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Code128EncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

