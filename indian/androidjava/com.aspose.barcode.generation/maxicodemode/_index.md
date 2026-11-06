---
title: "MaxiCodeMode"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "MaxiCode एन्कोडिंग मोड शामिल हैं।"
type: docs
weight: 95
url: /hi/androidjava/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

MaxiCode एन्कोडिंग मोड शामिल हैं।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [MODE_2](#MODE-2) | Mode 2 पहली संदेश में डाक जानकारी और दूसरे संदेश में डेटा एन्कोड करता है। |
| [MODE_3](#MODE-3) | Mode 3 पहली संदेश में डाक जानकारी और दूसरे संदेश में डेटा एन्कोड करता है। |
| [MODE_4](#MODE-4) | Mode 4 पहली और दूसरी संदेशों में डेटा को छोटे ECC सुधार के साथ एन्कोड करता है। |
| [MODE_5](#MODE-5) | Mode 5 पहली और दूसरी संदेशों में डेटा को लंबे ECC सुधार के साथ एन्कोड करता है। |
| [MODE_6](#MODE-6) | Mode 6 पहली और दूसरी संदेशों में डेटा को छोटे ECC सुधार के साथ एन्कोड करता है। |
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
### MODE_2 {#MODE-2}
```
public static final MaxiCodeMode MODE_2
```


Mode 2 पहले संदेश में डाक जानकारी और दूसरे संदेश में डेटा एन्कोड करता है। इसमें 9-अंकीय पोस्टल कोड है और यह केवल USA में उपयोग किया जाता है।

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


Mode 3 पहले संदेश में डाक जानकारी और दूसरे संदेश में डेटा एन्कोड करता है। इसमें 6-अक्षर अल्फ़ान्यूमेरिक पोस्टल कोड है और यह विश्वभर में उपयोग किया जाता है।

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


Mode 4 पहली और दूसरी संदेशों में डेटा को छोटे ECC सुधार के साथ एन्कोड करता है।

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


Mode 5 पहली और दूसरी संदेशों में डेटा को लंबे ECC सुधार के साथ एन्कोड करता है।

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


Mode 6 पहले और दूसरे संदेशों में डेटा को छोटे ECC सुधार के साथ एन्कोड करता है। यह उपकरणों को एन्कोड करने के लिए उपयोग किया जाता है।

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
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
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
public static MaxiCodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
### values() {#values--}
```
public static MaxiCodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.MaxiCodeMode[]
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
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

