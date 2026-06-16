---
title: GraphicsUnit
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: दिए गए डेटा के लिए माप इकाई निर्दिष्ट करता है।
type: docs
weight: 88
url: /hi/androidjava/com.aspose.barcode.generation/graphicsunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum GraphicsUnit extends Enum<GraphicsUnit>
```

दिए गए डेटा के लिए माप इकाई निर्दिष्ट करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DISPLAY](#DISPLAY) | डिस्प्ले डिवाइस की माप इकाई को निर्दिष्ट करता है। |
| [DOCUMENT](#DOCUMENT) | दस्तावेज़ इकाई (1/300 इंच) को माप इकाई के रूप में निर्दिष्ट करता है। |
| [INCH](#INCH) | इंच को माप इकाई के रूप में निर्दिष्ट करता है। |
| [MILLIMETER](#MILLIMETER) | मिलीमीटर को माप इकाई के रूप में निर्दिष्ट करता है। |
| [PIXEL](#PIXEL) | डिवाइस पिक्सेल को माप इकाई के रूप में निर्दिष्ट करता है। |
| [POINT](#POINT) | प्रिंटर के पॉइंट (1/72 इंच) को माप इकाई के रूप में निर्दिष्ट करता है। |
| [WORLD](#WORLD) | वर्ल्ड कोऑर्डिनेट सिस्टम इकाई को माप इकाई के रूप में निर्दिष्ट करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getGraphicsUnitName(int graphicsUnit)](#getGraphicsUnitName-int-) |  |
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
### DISPLAY {#DISPLAY}
```
public static final GraphicsUnit DISPLAY
```


डिस्प्ले डिवाइस की माप इकाई को निर्दिष्ट करता है। आमतौर पर वीडियो डिस्प्ले के लिए पिक्सेल और प्रिंटर के लिए 1/100 इंच।

### DOCUMENT {#DOCUMENT}
```
public static final GraphicsUnit DOCUMENT
```


दस्तावेज़ इकाई (1/300 इंच) को माप इकाई के रूप में निर्दिष्ट करता है।

### INCH {#INCH}
```
public static final GraphicsUnit INCH
```


इंच को माप इकाई के रूप में निर्दिष्ट करता है।

### MILLIMETER {#MILLIMETER}
```
public static final GraphicsUnit MILLIMETER
```


मिलीमीटर को माप इकाई के रूप में निर्दिष्ट करता है।

### PIXEL {#PIXEL}
```
public static final GraphicsUnit PIXEL
```


डिवाइस पिक्सेल को माप इकाई के रूप में निर्दिष्ट करता है।

### POINT {#POINT}
```
public static final GraphicsUnit POINT
```


प्रिंटर के पॉइंट (1/72 इंच) को माप इकाई के रूप में निर्दिष्ट करता है।

### WORLD {#WORLD}
```
public static final GraphicsUnit WORLD
```


वर्ल्ड कोऑर्डिनेट सिस्टम इकाई को माप इकाई के रूप में निर्दिष्ट करता है।

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
### getGraphicsUnitName(int graphicsUnit) {#getGraphicsUnitName-int-}
```
public static String getGraphicsUnitName(int graphicsUnit)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| graphicsUnit | int |  |

**Returns:**
java.lang.String
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
public static GraphicsUnit valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit)
### values() {#values--}
```
public static GraphicsUnit[] values()
```




**Returns:**
com.aspose.barcode.generation.GraphicsUnit[]
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

