---
title: InverseImageMode
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: 
type: docs
weight: 57
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/inverseimagemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InverseImageMode extends Enum<InverseImageMode>
```

वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।

--------------------

> ```
> This sample shows how to use InverseImage mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AUTO](#AUTO) | QR कोड को छोड़कर सभी बारकोड प्रकारों के लिए इनवर्स इमेज पर अतिरिक्त बारकोड पहचान को अक्षम करता है। |
| [DISABLED](#DISABLED) | इनवर्स इमेज पर अतिरिक्त बारकोड पहचान को अक्षम करता है। |
| [ENABLED](#ENABLED) | इनवर्स इमेज पर अतिरिक्त बारकोड पहचान को सक्षम करता है |
## Methods

| Method | विवरण |
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
public static final InverseImageMode AUTO
```


QR कोड को छोड़कर सभी बारकोड प्रकारों के लिए इनवर्स इमेज पर अतिरिक्त बारकोड पहचान को अक्षम करता है।

### DISABLED {#DISABLED}
```
public static final InverseImageMode DISABLED
```


इनवर्स इमेज पर अतिरिक्त बारकोड पहचान को अक्षम करता है।

### ENABLED {#ENABLED}
```
public static final InverseImageMode ENABLED
```


इनवर्स इमेज पर अतिरिक्त बारकोड पहचान को सक्षम करता है

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
### fromValue(int value) {#fromValue-int-}
```
public static InverseImageMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
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
public static InverseImageMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### values() {#values--}
```
public static InverseImageMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.InverseImageMode[]
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

