---
title: "MaxiCodeMode"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "MaxiCode एन्कोडिंग मोड्स शामिल हैं।"
type: docs
weight: 94
url: /hi/java/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

MaxiCode एन्कोडिंग मोड्स शामिल हैं।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [MODE_2](#MODE-2) | मोड 2 पहले संदेश में डाक सूचना और दूसरे संदेश में डेटा एन्कोड करता है। |
| [MODE_3](#MODE-3) | मोड 3 पहले संदेश में डाक सूचना और दूसरे संदेश में डेटा एन्कोड करता है। |
| [MODE_4](#MODE-4) | मोड 4 पहले और दूसरे संदेशों में डेटा को छोटे ECC सुधार के साथ एन्कोड करता है। |
| [MODE_5](#MODE-5) | मोड 5 पहले और दूसरे संदेशों में डेटा को लंबे ECC सुधार के साथ एन्कोड करता है। |
| [MODE_6](#MODE-6) | मोड 6 पहले और दूसरे संदेशों में डेटा को छोटे ECC सुधार के साथ एन्कोड करता है। |
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
### MODE_2 {#MODE-2}
```
public static final MaxiCodeMode MODE_2
```


मोड 2 पहले संदेश में डाक सूचना और दूसरे संदेश में डेटा एन्कोड करता है। इसमें 9-अंकीय डाक कोड होता है और यह केवल USA में उपयोग होता है।

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


मोड 3 पहले संदेश में डाक सूचना और दूसरे संदेश में डेटा एन्कोड करता है। इसमें 6-अंकीय अल्फ़ान्यूमेरिक डाक कोड होता है और यह विश्वभर में उपयोग होता है।

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


मोड 4 पहले और दूसरे संदेशों में डेटा को छोटे ECC सुधार के साथ एन्कोड करता है।

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


मोड 5 पहले और दूसरे संदेशों में डेटा को लंबे ECC सुधार के साथ एन्कोड करता है।

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


मोड 6 पहले और दूसरे संदेशों में डेटा को छोटे ECC सुधार के साथ एन्कोड करता है। उपकरणों को एन्कोड करने के लिए उपयोग किया जाता है।

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
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
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

