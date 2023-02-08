---
title: Zebra3DExtendUnion
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 16
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebra3dextendunion/
---
**Inheritance:**
java.lang.Object
```
public class Zebra3DExtendUnion
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Zebra3DExtendUnion()](#Zebra3DExtendUnion--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extendZebraUnion3D(ZebraUnion aUnion, ByteBitmap aBitmap, IExtend3DZebraProcessor aProcessor, int aSelection)](#extendZebraUnion3D-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.zebraxd.IExtend3DZebraProcessor-int-) | Extends ZebraUnion with 3D fan |
| [extendZebraUnionList3D(List<ZebraUnion> aUnions, ByteBitmap aBitmap, IExtend3DZebraProcessor aProcessor, int aSelection)](#extendZebraUnionList3D-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.zebraxd.IExtend3DZebraProcessor-int-) | Extends ZebraUnion list with 3D fan multithreadly |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Zebra3DExtendUnion() {#Zebra3DExtendUnion--}
```
public Zebra3DExtendUnion()
```


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
### extendZebraUnion3D(ZebraUnion aUnion, ByteBitmap aBitmap, IExtend3DZebraProcessor aProcessor, int aSelection) {#extendZebraUnion3D-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.zebraxd.IExtend3DZebraProcessor-int-}
```
public static ZebraUnion extendZebraUnion3D(ZebraUnion aUnion, ByteBitmap aBitmap, IExtend3DZebraProcessor aProcessor, int aSelection)
```


Extends ZebraUnion with 3D fan

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) | extended zebraunion |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | bitmap |
| aProcessor | [IExtend3DZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextend3dzebraprocessor) | 3d processor for extending |
| aSelection | int | selecton what to extend Start, End, Both. Both is the most common variant |

**Returns:**
[ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) - extended union with 3D fan
### extendZebraUnionList3D(List<ZebraUnion> aUnions, ByteBitmap aBitmap, IExtend3DZebraProcessor aProcessor, int aSelection) {#extendZebraUnionList3D-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.zebraxd.IExtend3DZebraProcessor-int-}
```
public static List<ZebraUnion> extendZebraUnionList3D(List<ZebraUnion> aUnions, ByteBitmap aBitmap, IExtend3DZebraProcessor aProcessor, int aSelection)
```


Extends ZebraUnion list with 3D fan multithreadly

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnions | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion> | extended zebraunion list |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | bitmap |
| aProcessor | [IExtend3DZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextend3dzebraprocessor) | 3d processor for extending |
| aSelection | int | selecton what to extend Start, End, Both. Both is the most common variant |

**Returns:**
[List](../../java.util/list) - extended union list with 3D fan
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

