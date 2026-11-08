---
title: "XDimensionMode"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: 
type: docs
weight: 54
url: /hi/java/com.aspose.barcode.barcoderecognition/xdimensionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum XDimensionMode extends Enum<XDimensionMode>
```

मान्यता मोड जो बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक) निर्धारित करता है: मैट्रिक्स सेल या बार।

--------------------

> ```
> This sample shows how to use XDimension mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AUTO](#AUTO) | XDimension का मान AI (SVM) द्वारा पता लगाया जाता है। |
| [LARGE](#LARGE) | उच्च-रिज़ॉल्यूशन कैमरों से कैप्चर की गई BarcodeQuality के साथ बड़ी XDimension वाले बारकोड का पता लगाता है। |
| [NORMAL](#NORMAL) | 2 पिक्सेल या अधिक की क्लासिक XDimension वाले बारकोड को BarcodeQuality या उच्च गुणवत्ता वाले बारकोड के साथ पहचानता है। |
| [SMALL](#SMALL) | 1 पिक्सेल या अधिक की छोटी XDimension वाले बारकोड को BarcodeQuality के साथ पहचानता है। |
| [USE_MINIMAL_X_DIMENSION](#USE-MINIMAL-X-DIMENSION) | MinimalXDimension में सेट आकार वाले बारकोड को BarcodeQuality के साथ पहचानता है। |
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
public static final XDimensionMode AUTO
```


XDimension का मान AI (SVM) द्वारा पता लगाया जाता है। वर्तमान में यह Normal के समान है।

### LARGE {#LARGE}
```
public static final XDimensionMode LARGE
```


उच्च-रिज़ॉल्यूशन कैमरों से कैप्चर की गई BarcodeQuality के साथ बड़ी XDimension वाले बारकोड का पता लगाता है।

### NORMAL {#NORMAL}
```
public static final XDimensionMode NORMAL
```


2 पिक्सेल या अधिक की क्लासिक XDimension वाले बारकोड को BarcodeQuality या उच्च गुणवत्ता वाले बारकोड के साथ पहचानता है।

### SMALL {#SMALL}
```
public static final XDimensionMode SMALL
```


1 पिक्सेल या अधिक की छोटी XDimension वाले बारकोड को BarcodeQuality के साथ पहचानता है।

### USE_MINIMAL_X_DIMENSION {#USE-MINIMAL-X-DIMENSION}
```
public static final XDimensionMode USE_MINIMAL_X_DIMENSION
```


MinimalXDimension में सेट आकार वाले बारकोड को BarcodeQuality के साथ पहचानता है।

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
public static XDimensionMode fromValue(int value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
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
public static XDimensionMode valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
### values() {#values--}
```
public static XDimensionMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.XDimensionMode[]
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

