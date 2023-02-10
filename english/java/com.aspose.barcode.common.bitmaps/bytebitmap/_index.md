---
title: ByteBitmap
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.aspose.barcode.common.bitmaps/bytebitmap/
---
**Inheritance:**
java.lang.Object
```
public class ByteBitmap
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ByteBitmap(int width, int height)](#ByteBitmap-int-int-) |  |
| [ByteBitmap(int width, int height, byte defaultValue)](#ByteBitmap-int-int-byte-) |  |
| [ByteBitmap(int width, int height, byte[] data)](#ByteBitmap-int-int-byte---) |  |
| [ByteBitmap(ByteBitmap bitmap)](#ByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [ByteBitmap(byte[][] byteArray)](#ByteBitmap-byte-----) |  |
## Fields

| Field | Description |
| --- | --- |
| [BlackColor](#BlackColor) |  |
| [Data](#Data) |  |
| [Height](#Height) |  |
| [MaxColor](#MaxColor) |  |
| [WhiteColor](#WhiteColor) |  |
| [Width](#Width) |  |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPixelFast(ShortPoint point)](#getPixelFast-com.aspose.barcode.common.types.ShortPoint-) | Return color (skip validation) |
| [getPixelFast(System.Drawing.Point point)](#getPixelFast-com.aspose.ms.System.Drawing.Point-) | Return color (skip validation) |
| [getPixelFast(int x, int y)](#getPixelFast-int-int-) | Return color (skip validation) |
| [getPixelSafe(System.Drawing.Point point)](#getPixelSafe-com.aspose.ms.System.Drawing.Point-) |  |
| [getPixelSafe(int x, int y)](#getPixelSafe-int-int-) |  |
| [getPixelSafe(int x, int y, byte aDef)](#getPixelSafe-int-int-byte-) |  |
| [get_Item(ShortPoint point)](#get-Item-com.aspose.barcode.common.types.ShortPoint-) |  |
| [get_Item(System.Drawing.Point point)](#get-Item-com.aspose.ms.System.Drawing.Point-) |  |
| [get_Item(int x, int y)](#get-Item-int-int-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(String path)](#save-java.lang.String-) |  |
| [saveBinarized(String path)](#saveBinarized-java.lang.String-) |  |
| [setPixelFast(ShortPoint point, byte data)](#setPixelFast-com.aspose.barcode.common.types.ShortPoint-byte-) | Set color (skip validation) |
| [setPixelFast(System.Drawing.Point point, byte data)](#setPixelFast-com.aspose.ms.System.Drawing.Point-byte-) | Set color (skip validation) |
| [setPixelFast(int x, int y, byte data)](#setPixelFast-int-int-byte-) | Set color (skip validation) |
| [setPixelSafe(int x, int y, byte data)](#setPixelSafe-int-int-byte-) |  |
| [set_Item(ShortPoint point, byte value)](#set-Item-com.aspose.barcode.common.types.ShortPoint-byte-) |  |
| [set_Item(System.Drawing.Point point, byte value)](#set-Item-com.aspose.ms.System.Drawing.Point-byte-) |  |
| [set_Item(int x, int y, byte value)](#set-Item-int-int-byte-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ByteBitmap(int width, int height) {#ByteBitmap-int-int-}
```
public ByteBitmap(int width, int height)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int |  |
| height | int |  |

### ByteBitmap(int width, int height, byte defaultValue) {#ByteBitmap-int-int-byte-}
```
public ByteBitmap(int width, int height, byte defaultValue)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int |  |
| height | int |  |
| defaultValue | byte |  |

### ByteBitmap(int width, int height, byte[] data) {#ByteBitmap-int-int-byte---}
```
public ByteBitmap(int width, int height, byte[] data)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int |  |
| height | int |  |
| data | byte[] |  |

### ByteBitmap(ByteBitmap bitmap) {#ByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public ByteBitmap(ByteBitmap bitmap)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

### ByteBitmap(byte[][] byteArray) {#ByteBitmap-byte-----}
```
public ByteBitmap(byte[][] byteArray)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteArray | byte[][] |  |

### BlackColor {#BlackColor}
```
public static final byte BlackColor
```


### Data {#Data}
```
public byte[] Data
```


### Height {#Height}
```
public int Height
```


### MaxColor {#MaxColor}
```
public static final byte MaxColor
```


### WhiteColor {#WhiteColor}
```
public static final byte WhiteColor
```


### Width {#Width}
```
public int Width
```


### deepClone() {#deepClone--}
```
public Object deepClone()
```




**Returns:**
java.lang.Object
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
### getPixelFast(ShortPoint point) {#getPixelFast-com.aspose.barcode.common.types.ShortPoint-}
```
public final byte getPixelFast(ShortPoint point)
```


Return color (skip validation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [ShortPoint](../../com.aspose.barcode.common.types/shortpoint) | a point |

**Returns:**
byte - color of pixel
### getPixelFast(System.Drawing.Point point) {#getPixelFast-com.aspose.ms.System.Drawing.Point-}
```
public final byte getPixelFast(System.Drawing.Point point)
```


Return color (skip validation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point | a point |

**Returns:**
byte - color of pixel
### getPixelFast(int x, int y) {#getPixelFast-int-int-}
```
public final byte getPixelFast(int x, int y)
```


Return color (skip validation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | x-coordinate |
| y | int | y-coordinate |

**Returns:**
byte - color of pixel
### getPixelSafe(System.Drawing.Point point) {#getPixelSafe-com.aspose.ms.System.Drawing.Point-}
```
public final byte getPixelSafe(System.Drawing.Point point)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
byte
### getPixelSafe(int x, int y) {#getPixelSafe-int-int-}
```
public final byte getPixelSafe(int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |

**Returns:**
byte
### getPixelSafe(int x, int y, byte aDef) {#getPixelSafe-int-int-byte-}
```
public final byte getPixelSafe(int x, int y, byte aDef)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| aDef | byte |  |

**Returns:**
byte
### get_Item(ShortPoint point) {#get-Item-com.aspose.barcode.common.types.ShortPoint-}
```
public byte get_Item(ShortPoint point)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [ShortPoint](../../com.aspose.barcode.common.types/shortpoint) |  |

**Returns:**
byte
### get_Item(System.Drawing.Point point) {#get-Item-com.aspose.ms.System.Drawing.Point-}
```
public byte get_Item(System.Drawing.Point point)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
byte
### get_Item(int x, int y) {#get-Item-int-int-}
```
public byte get_Item(int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |

**Returns:**
byte
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




### save(String path) {#save-java.lang.String-}
```
public void save(String path)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String |  |

### saveBinarized(String path) {#saveBinarized-java.lang.String-}
```
public void saveBinarized(String path)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String |  |

### setPixelFast(ShortPoint point, byte data) {#setPixelFast-com.aspose.barcode.common.types.ShortPoint-byte-}
```
public final void setPixelFast(ShortPoint point, byte data)
```


Set color (skip validation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [ShortPoint](../../com.aspose.barcode.common.types/shortpoint) | a point |
| data | byte | a new color of pixel |

### setPixelFast(System.Drawing.Point point, byte data) {#setPixelFast-com.aspose.ms.System.Drawing.Point-byte-}
```
public final void setPixelFast(System.Drawing.Point point, byte data)
```


Set color (skip validation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point | a point |
| data | byte | a new color of pixel |

### setPixelFast(int x, int y, byte data) {#setPixelFast-int-int-byte-}
```
public final void setPixelFast(int x, int y, byte data)
```


Set color (skip validation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | x-coordinate |
| y | int | y-coordinate |
| data | byte | a new color of pixel |

### setPixelSafe(int x, int y, byte data) {#setPixelSafe-int-int-byte-}
```
public final void setPixelSafe(int x, int y, byte data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| data | byte |  |

### set_Item(ShortPoint point, byte value) {#set-Item-com.aspose.barcode.common.types.ShortPoint-byte-}
```
public void set_Item(ShortPoint point, byte value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [ShortPoint](../../com.aspose.barcode.common.types/shortpoint) |  |
| value | byte |  |

### set_Item(System.Drawing.Point point, byte value) {#set-Item-com.aspose.ms.System.Drawing.Point-byte-}
```
public void set_Item(System.Drawing.Point point, byte value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |
| value | byte |  |

### set_Item(int x, int y, byte value) {#set-Item-int-int-byte-}
```
public void set_Item(int x, int y, byte value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| value | byte |  |

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

