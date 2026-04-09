---
title: EnableChecksum
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: 1D बारकोड के जनरेशन के दौरान चेकसम सक्षम करें।
type: docs
weight: 86
url: /hi/androidjava/com.aspose.barcode.generation/enablechecksum/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EnableChecksum extends Enum<EnableChecksum>
```

1D बारकोड के जनरेशन के दौरान चेकसम सक्षम करें।

डिफ़ॉल्ट रूप से उन सिम्बोलॉजीज़ के लिए Yes माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ No माना जाता है।

Checksum कभी उपयोग नहीं किया गया: Codabar

Checksum संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

चेकसम हमेशा उपयोग किया जाता है: शेष सिम्बोलॉजीज़
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DEFAULT](#DEFAULT) | यदि विनिर्देश द्वारा checksum आवश्यक है - इसे संलग्न किया जाएगा। |
| [NO](#NO) | checksum का उपयोग न करें। |
| [YES](#YES) | यदि संभव हो तो हमेशा चेकसम का उपयोग करें। |
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
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DEFAULT {#DEFAULT}
```
public static final EnableChecksum DEFAULT
```


यदि विनिर्देश द्वारा checksum आवश्यक है - इसे संलग्न किया जाएगा।

### NO {#NO}
```
public static final EnableChecksum NO
```


checksum का उपयोग न करें।

### YES {#YES}
```
public static final EnableChecksum YES
```


यदि संभव हो तो हमेशा चेकसम का उपयोग करें।

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
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static EnableChecksum valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### values() {#values--}
```
public static EnableChecksum[] values()
```




**Returns:**
com.aspose.barcode.generation.EnableChecksum[]
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

