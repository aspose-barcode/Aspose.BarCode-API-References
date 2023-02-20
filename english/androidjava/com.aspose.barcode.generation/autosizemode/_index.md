---
title: AutoSizeMode
second_title: Aspose.BarCode for Java API Reference
description: Specifies the different types of automatic sizing modes.
type: docs
weight: 57
url: /java/com.aspose.barcode.generation/autosizemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AutoSizeMode extends Enum<AutoSizeMode>
```

Specifies the different types of automatic sizing modes. Default value is AutoSizeMode.NONE.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>          generator.setAutoSizeMode(AutoSizeMode.NEAREST);
>          generator.getBarCodeWidth().setMillimeters(50);
>          generator.getBarCodeHeight().setInches(1.3f);
>          generator.save("test.png");
> ```
## Fields

| Field | Description |
| --- | --- |
| [INTERPOLATION](#INTERPOLATION) | Resizes barcode to specified size with little scaling but it can be little damaged in some cases because using interpolation for scaling. |
| [NEAREST](#NEAREST) | Barcode resizes to nearest lowest possible size which are specified by BarCodeWidth and BarCodeHeight properties. |
| [NONE](#NONE) | Automatic resizing is disabled. |
## Methods

| Method | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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
### INTERPOLATION {#INTERPOLATION}
```
public static final AutoSizeMode INTERPOLATION
```


Resizes barcode to specified size with little scaling but it can be little damaged in some cases because using interpolation for scaling. Size can be specified by  BarcodeGenerator.BarCodeWidth  and  BarcodeGenerator.BarCodeHeight  properties.

--------------------

> ```
> This sample shows how to create and save a BarCode image in Scale mode.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>          generator.setAutoSizeMode(AutoSizeMode.INTERPOLATION);
>          generator.getBarCodeWidth().setMillimeters(50);
>          generator.getBarCodeHeight().setInches(1.3f);
>          generator.save("test.png");
> ```

### NEAREST {#NEAREST}
```
public static final AutoSizeMode NEAREST
```


Barcode resizes to nearest lowest possible size which are specified by BarCodeWidth and BarCodeHeight properties.

### NONE {#NONE}
```
public static final AutoSizeMode NONE
```


Automatic resizing is disabled. Default value.

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
public static AutoSizeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### values() {#values--}
```
public static AutoSizeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.AutoSizeMode[]
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

