---
title: QRErrorLevel
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: रीड-सोमन त्रुटि सुधार का स्तर।
type: docs
weight: 104
url: /hi/androidjava/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च तक: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H.
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | त्रुटि सुधार स्तर H को QR और RectMicroQR बारकोड पर लागू किया जा सकता है। |
| [LEVEL_L](#LEVEL-L) | त्रुटि सुधार स्तर L को QR और MicroQR बारकोड पर लागू किया जा सकता है। |
| [LEVEL_M](#LEVEL-M) | त्रुटि सुधार स्तर M को QR बारकोड, RectMicroQR बारकोड और M2 से M4 संस्करणों वाले MicroQR बारकोड पर लागू किया जा सकता है। |
| [LEVEL_Q](#LEVEL-Q) | त्रुटि सुधार स्तर Q को QR बारकोड और संस्करण M4 वाले MicroQR बारकोड पर लागू किया जा सकता है। |
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
### LEVEL_H {#LEVEL-H}
```
public static final QRErrorLevel LEVEL_H
```


त्रुटि सुधार स्तर H को QR और RectMicroQR बारकोड पर लागू किया जा सकता है। कोड टेक्स्ट का 30% पुनर्प्राप्ति की अनुमति देता है।

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


त्रुटि सुधार स्तर L को QR और MicroQR बारकोड पर लागू किया जा सकता है। कोड टेक्स्ट का 7% पुनर्प्राप्ति की अनुमति देता है।

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


त्रुटि सुधार स्तर M को QR बारकोड, RectMicroQR बारकोड और M2 से M4 संस्करणों वाले MicroQR बारकोड पर लागू किया जा सकता है। कोड टेक्स्ट का 15% पुनर्प्राप्ति की अनुमति देता है।

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


त्रुटि सुधार स्तर Q को QR बारकोड और संस्करण M4 वाले MicroQR बारकोड पर लागू किया जा सकता है। कोड टेक्स्ट का 25% पुनर्प्राप्ति की अनुमति देता है।

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
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
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
public static QRErrorLevel valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### values() {#values--}
```
public static QRErrorLevel[] values()
```




**Returns:**
com.aspose.barcode.generation.QRErrorLevel[]
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

