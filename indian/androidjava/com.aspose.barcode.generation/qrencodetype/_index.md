---
title: QREncodeType
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: QR / MicroQR चयनकर्ता मोड।
type: docs
weight: 103
url: /hi/androidjava/com.aspose.barcode.generation/qrencodetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeType extends Enum<QREncodeType>
```

QR / MicroQR चयन मोड। मानक QR प्रतीकों के लिए FORCE\_QR चुनें, MicroQR के लिए AUTO। यदि संभव हो तो मजबूत MicroQR प्रतीक निर्माण के लिए FORCE\_MICRO\_QR उपयोग किया जाता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AUTO](#AUTO) | मोड MicroQR V1 से बारकोड संस्करण वार्ता शुरू करता है |
| [FORCE_MICRO_QR](#FORCE-MICRO-QR) | मोड MicroQR V1 से V4 तक बारकोड संस्करण वार्ता शुरू करता है। |
| [FORCE_QR](#FORCE-QR) | मोड QR V1 से बारकोड संस्करण वार्ता शुरू करता है। |
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
### AUTO {#AUTO}
```
public static final QREncodeType AUTO
```


मोड MicroQR V1 से बारकोड संस्करण वार्ता शुरू करता है

### FORCE_MICRO_QR {#FORCE-MICRO-QR}
```
public static final QREncodeType FORCE_MICRO_QR
```


मोड MicroQR V1 से V4 तक बारकोड संस्करण वार्ता शुरू करता है। यदि डेटा को MicroQR में एन्कोड नहीं किया जा सकता, तो अपवाद फेंका जाता है।

### FORCE_QR {#FORCE-QR}
```
public static final QREncodeType FORCE_QR
```


मोड QR V1 से बारकोड संस्करण वार्ता शुरू करता है।

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
public static QREncodeType valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### values() {#values--}
```
public static QREncodeType[] values()
```




**Returns:**
com.aspose.barcode.generation.QREncodeType[]
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

