---
title: InverseImageMode
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 54
url: /java/com.aspose.barcode.barcoderecognition/inverseimagemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InverseImageMode extends Enum<InverseImageMode>
```

Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance).

--------------------

> ```
> This sample shows how to use InverseImage mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## Fields

| Field | Description |
| --- | --- |
| [AUTO](#AUTO) | Disables additional recognition of barcodes on inverse images for all barcode types except QR Code |
| [DISABLED](#DISABLED) | Disables additional recognition of barcodes on inverse images. |
| [ENABLED](#ENABLED) | Enables additional recognition of barcodes on inverse images |
## Methods

| Method | Description |
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
public static final InverseImageMode AUTO
```


Disables additional recognition of barcodes on inverse images for all barcode types except QR Code

### DISABLED {#DISABLED}
```
public static final InverseImageMode DISABLED
```


Disables additional recognition of barcodes on inverse images.

### ENABLED {#ENABLED}
```
public static final InverseImageMode ENABLED
```


Enables additional recognition of barcodes on inverse images

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static InverseImageMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

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
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

