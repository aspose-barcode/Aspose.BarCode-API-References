---
title: AztecHelper
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.recognition.aztec/aztechelper/
---
**Inheritance:**
java.lang.Object
```
public class AztecHelper
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AztecHelper()](#AztecHelper--) |  |
## Fields

| Field | Description |
| --- | --- |
| [BORDERSCNTCOMPACT](#BORDERSCNTCOMPACT) | Number of elements in Zebra from center to border of target for Compact. |
| [BORDERSCNTREGULAR](#BORDERSCNTREGULAR) | Number of elements in Zebra from center to border of target for Regular. |
| [SQUAREMWIDTHCOMPACT](#SQUAREMWIDTHCOMPACT) | Number of elements in Zebra in target for Compact. |
| [SQUAREMWIDTHREGULAR](#SQUAREMWIDTHREGULAR) | Number of elements in Zebra in target for Regular. |
## Methods

| Method | Description |
| --- | --- |
| [createZebra(System.Drawing.Point start, System.Drawing.Point end, int separatrix, ByteBitmap ByteBitmap)](#createZebra-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-int-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCenterBorder(System.Drawing.Point centerModulePoint, int direction, ByteBitmap byteBitmap, int separatix)](#getCenterBorder-com.aspose.ms.System.Drawing.Point-int-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [getClass()](#getClass--) |  |
| [getModuleSizePx(System.Drawing.Point centerModulePoint, ByteBitmap byteBitmap, int separatix)](#getModuleSizePx-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AztecHelper() {#AztecHelper--}
```
public AztecHelper()
```


### BORDERSCNTCOMPACT {#BORDERSCNTCOMPACT}
```
public static final int BORDERSCNTCOMPACT
```


Number of elements in Zebra from center to border of target for Compact.

### BORDERSCNTREGULAR {#BORDERSCNTREGULAR}
```
public static final int BORDERSCNTREGULAR
```


Number of elements in Zebra from center to border of target for Regular.

### SQUAREMWIDTHCOMPACT {#SQUAREMWIDTHCOMPACT}
```
public static final int SQUAREMWIDTHCOMPACT
```


Number of elements in Zebra in target for Compact.

### SQUAREMWIDTHREGULAR {#SQUAREMWIDTHREGULAR}
```
public static final int SQUAREMWIDTHREGULAR
```


Number of elements in Zebra in target for Regular.

### createZebra(System.Drawing.Point start, System.Drawing.Point end, int separatrix, ByteBitmap ByteBitmap) {#createZebra-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-int-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static Int32List createZebra(System.Drawing.Point start, System.Drawing.Point end, int separatrix, ByteBitmap ByteBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| start | com.aspose.ms.System.Drawing.Point |  |
| end | com.aspose.ms.System.Drawing.Point |  |
| separatrix | int |  |
| ByteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCenterBorder(System.Drawing.Point centerModulePoint, int direction, ByteBitmap byteBitmap, int separatix) {#getCenterBorder-com.aspose.ms.System.Drawing.Point-int-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static System.Drawing.Point getCenterBorder(System.Drawing.Point centerModulePoint, int direction, ByteBitmap byteBitmap, int separatix)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| centerModulePoint | com.aspose.ms.System.Drawing.Point |  |
| direction | int |  |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| separatix | int |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getModuleSizePx(System.Drawing.Point centerModulePoint, ByteBitmap byteBitmap, int separatix) {#getModuleSizePx-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static float getModuleSizePx(System.Drawing.Point centerModulePoint, ByteBitmap byteBitmap, int separatix)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| centerModulePoint | com.aspose.ms.System.Drawing.Point |  |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| separatix | int |  |

**Returns:**
float
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

