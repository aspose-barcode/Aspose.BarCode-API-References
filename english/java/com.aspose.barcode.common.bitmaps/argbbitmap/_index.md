---
title: ARGBBitmap
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.common.bitmaps/argbbitmap/
---
**Inheritance:**
java.lang.Object
```
public class ARGBBitmap
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ARGBBitmap(int aWidth, int aHeight)](#ARGBBitmap-int-int-) |  |
| [ARGBBitmap(int aWidth, int aHeight, ARGBColor aInit)](#ARGBBitmap-int-int-com.aspose.barcode.common.bitmaps.ARGBColor-) |  |
| [ARGBBitmap(ARGBBitmap aBitmap)](#ARGBBitmap-com.aspose.barcode.common.bitmaps.ARGBBitmap-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Data](#Data) |  |
| [Height](#Height) |  |
| [Width](#Width) |  |
## Methods

| Method | Description |
| --- | --- |
| [convertToByteBitmap(ARGBBitmap aBitmap)](#convertToByteBitmap-com.aspose.barcode.common.bitmaps.ARGBBitmap-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorPixel(System.Drawing.Point point)](#getColorPixel-com.aspose.ms.System.Drawing.Point-) |  |
| [getColorPixel(int x, int y)](#getColorPixel-int-int-) |  |
| [getColorPixelSafe(System.Drawing.Point point)](#getColorPixelSafe-com.aspose.ms.System.Drawing.Point-) |  |
| [getColorPixelSafe(System.Drawing.Point point, System.Drawing.Color aDef)](#getColorPixelSafe-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Color-) |  |
| [getColorPixelSafe(int x, int y)](#getColorPixelSafe-int-int-) |  |
| [getColorPixelSafe(int x, int y, System.Drawing.Color aDef)](#getColorPixelSafe-int-int-com.aspose.ms.System.Drawing.Color-) |  |
| [getPixelSafe(System.Drawing.Point point)](#getPixelSafe-com.aspose.ms.System.Drawing.Point-) |  |
| [getPixelSafe(System.Drawing.Point point, ARGBColor aDef)](#getPixelSafe-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ARGBColor-) |  |
| [getPixelSafe(int x, int y)](#getPixelSafe-int-int-) |  |
| [getPixelSafe(int x, int y, ARGBColor aDef)](#getPixelSafe-int-int-com.aspose.barcode.common.bitmaps.ARGBColor-) |  |
| [get_Item(int x, int y)](#get-Item-int-int-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorPixel(System.Drawing.Point point, System.Drawing.Color data)](#setColorPixel-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Color-) |  |
| [setColorPixel(int x, int y, System.Drawing.Color data)](#setColorPixel-int-int-com.aspose.ms.System.Drawing.Color-) |  |
| [setColorPixelSafe(System.Drawing.Point point, System.Drawing.Color data)](#setColorPixelSafe-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Color-) |  |
| [setColorPixelSafe(int x, int y, System.Drawing.Color data)](#setColorPixelSafe-int-int-com.aspose.ms.System.Drawing.Color-) |  |
| [setPixelSafe(System.Drawing.Point point, ARGBColor data)](#setPixelSafe-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ARGBColor-) |  |
| [setPixelSafe(int x, int y, ARGBColor data)](#setPixelSafe-int-int-com.aspose.barcode.common.bitmaps.ARGBColor-) |  |
| [set_Item(int x, int y, ARGBColor value)](#set-Item-int-int-com.aspose.barcode.common.bitmaps.ARGBColor-) |  |
| [set_Item(int x, int y, int ARGBColorValue)](#set-Item-int-int-int-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ARGBBitmap(int aWidth, int aHeight) {#ARGBBitmap-int-int-}
```
public ARGBBitmap(int aWidth, int aHeight)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aWidth | int |  |
| aHeight | int |  |

### ARGBBitmap(int aWidth, int aHeight, ARGBColor aInit) {#ARGBBitmap-int-int-com.aspose.barcode.common.bitmaps.ARGBColor-}
```
public ARGBBitmap(int aWidth, int aHeight, ARGBColor aInit)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aWidth | int |  |
| aHeight | int |  |
| aInit | [ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor) |  |

### ARGBBitmap(ARGBBitmap aBitmap) {#ARGBBitmap-com.aspose.barcode.common.bitmaps.ARGBBitmap-}
```
public ARGBBitmap(ARGBBitmap aBitmap)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ARGBBitmap](../../com.aspose.barcode.common.bitmaps/argbbitmap) |  |

### Data {#Data}
```
public int[] Data
```


### Height {#Height}
```
public int Height
```


### Width {#Width}
```
public int Width
```


### convertToByteBitmap(ARGBBitmap aBitmap) {#convertToByteBitmap-com.aspose.barcode.common.bitmaps.ARGBBitmap-}
```
public static ByteBitmap convertToByteBitmap(ARGBBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ARGBBitmap](../../com.aspose.barcode.common.bitmaps/argbbitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPixel(System.Drawing.Point point) {#getColorPixel-com.aspose.ms.System.Drawing.Point-}
```
public System.Drawing.Color getColorPixel(System.Drawing.Point point)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
com.aspose.ms.System.Drawing.Color
### getColorPixel(int x, int y) {#getColorPixel-int-int-}
```
public System.Drawing.Color getColorPixel(int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |

**Returns:**
com.aspose.ms.System.Drawing.Color
### getColorPixelSafe(System.Drawing.Point point) {#getColorPixelSafe-com.aspose.ms.System.Drawing.Point-}
```
public System.Drawing.Color getColorPixelSafe(System.Drawing.Point point)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
com.aspose.ms.System.Drawing.Color
### getColorPixelSafe(System.Drawing.Point point, System.Drawing.Color aDef) {#getColorPixelSafe-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Color-}
```
public System.Drawing.Color getColorPixelSafe(System.Drawing.Point point, System.Drawing.Color aDef)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |
| aDef | com.aspose.ms.System.Drawing.Color |  |

**Returns:**
com.aspose.ms.System.Drawing.Color
### getColorPixelSafe(int x, int y) {#getColorPixelSafe-int-int-}
```
public System.Drawing.Color getColorPixelSafe(int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |

**Returns:**
com.aspose.ms.System.Drawing.Color
### getColorPixelSafe(int x, int y, System.Drawing.Color aDef) {#getColorPixelSafe-int-int-com.aspose.ms.System.Drawing.Color-}
```
public System.Drawing.Color getColorPixelSafe(int x, int y, System.Drawing.Color aDef)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| aDef | com.aspose.ms.System.Drawing.Color |  |

**Returns:**
com.aspose.ms.System.Drawing.Color
### getPixelSafe(System.Drawing.Point point) {#getPixelSafe-com.aspose.ms.System.Drawing.Point-}
```
public ARGBColor getPixelSafe(System.Drawing.Point point)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
[ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor)
### getPixelSafe(System.Drawing.Point point, ARGBColor aDef) {#getPixelSafe-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ARGBColor-}
```
public ARGBColor getPixelSafe(System.Drawing.Point point, ARGBColor aDef)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |
| aDef | [ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor) |  |

**Returns:**
[ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor)
### getPixelSafe(int x, int y) {#getPixelSafe-int-int-}
```
public ARGBColor getPixelSafe(int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |

**Returns:**
[ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor)
### getPixelSafe(int x, int y, ARGBColor aDef) {#getPixelSafe-int-int-com.aspose.barcode.common.bitmaps.ARGBColor-}
```
public ARGBColor getPixelSafe(int x, int y, ARGBColor aDef)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| aDef | [ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor) |  |

**Returns:**
[ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor)
### get_Item(int x, int y) {#get-Item-int-int-}
```
public final ARGBColor get_Item(int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |

**Returns:**
[ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor)
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




### setColorPixel(System.Drawing.Point point, System.Drawing.Color data) {#setColorPixel-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Color-}
```
public void setColorPixel(System.Drawing.Point point, System.Drawing.Color data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |
| data | com.aspose.ms.System.Drawing.Color |  |

### setColorPixel(int x, int y, System.Drawing.Color data) {#setColorPixel-int-int-com.aspose.ms.System.Drawing.Color-}
```
public void setColorPixel(int x, int y, System.Drawing.Color data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| data | com.aspose.ms.System.Drawing.Color |  |

### setColorPixelSafe(System.Drawing.Point point, System.Drawing.Color data) {#setColorPixelSafe-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Color-}
```
public void setColorPixelSafe(System.Drawing.Point point, System.Drawing.Color data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |
| data | com.aspose.ms.System.Drawing.Color |  |

### setColorPixelSafe(int x, int y, System.Drawing.Color data) {#setColorPixelSafe-int-int-com.aspose.ms.System.Drawing.Color-}
```
public void setColorPixelSafe(int x, int y, System.Drawing.Color data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| data | com.aspose.ms.System.Drawing.Color |  |

### setPixelSafe(System.Drawing.Point point, ARGBColor data) {#setPixelSafe-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ARGBColor-}
```
public void setPixelSafe(System.Drawing.Point point, ARGBColor data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |
| data | [ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor) |  |

### setPixelSafe(int x, int y, ARGBColor data) {#setPixelSafe-int-int-com.aspose.barcode.common.bitmaps.ARGBColor-}
```
public void setPixelSafe(int x, int y, ARGBColor data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| data | [ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor) |  |

### set_Item(int x, int y, ARGBColor value) {#set-Item-int-int-com.aspose.barcode.common.bitmaps.ARGBColor-}
```
public final void set_Item(int x, int y, ARGBColor value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| value | [ARGBColor](../../com.aspose.barcode.common.bitmaps/argbcolor) |  |

### set_Item(int x, int y, int ARGBColorValue) {#set-Item-int-int-int-}
```
public final void set_Item(int x, int y, int ARGBColorValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| ARGBColorValue | int |  |

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

