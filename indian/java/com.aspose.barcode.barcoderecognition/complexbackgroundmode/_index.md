---
title: "ComplexBackgroundMode"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: 
type: docs
weight: 50
url: /hi/java/com.aspose.barcode.barcoderecognition/complexbackgroundmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComplexBackgroundMode extends Enum<ComplexBackgroundMode>
```

वह मोड जो रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।

--------------------

> ```
> This sample shows how to use ComplexBackground mode
>   
>   BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AUTO](#AUTO) | वर्तमान में यह अक्षम के समान है। |
| [DISABLED](#DISABLED) | रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को अक्षम करता है। |
| [ENABLED](#ENABLED) | रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को सक्षम करता है। |
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
public static final ComplexBackgroundMode AUTO
```


वर्तमान में यह अक्षम के समान है। रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को अक्षम करता है।

### DISABLED {#DISABLED}
```
public static final ComplexBackgroundMode DISABLED
```


रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को अक्षम करता है।

### ENABLED {#ENABLED}
```
public static final ComplexBackgroundMode ENABLED
```


रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को सक्षम करता है।

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
public static ComplexBackgroundMode fromValue(int value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
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
public static ComplexBackgroundMode valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### values() {#values--}
```
public static ComplexBackgroundMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.ComplexBackgroundMode[]
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

