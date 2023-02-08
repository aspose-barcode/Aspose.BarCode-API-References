---
title: PerspectiveTransformation
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 40
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/perspectivetransformation/
---
**Inheritance:**
java.lang.Object
```
public class PerspectiveTransformation
```
## Constructors

| Constructor | Description |
| --- | --- |
| [PerspectiveTransformation()](#PerspectiveTransformation--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getResultPointPositionNearestNeighbor(int resultWidth, int resultHeight, PerspectiveTransformation.Transformation aTransform, System.Drawing.Point originalPoint)](#getResultPointPositionNearestNeighbor-int-int-com.aspose.barcode.barcoderecognition.common.algorithms.PerspectiveTransformation.Transformation-com.aspose.ms.System.Drawing.Point-) | Returns the position of the point in transformed bitmap. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformBitmapBilinear(ByteBitmap bitmap, System.Drawing.Rectangle rectangle, System.Drawing.Size size)](#transformBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-com.aspose.ms.System.Drawing.Size-) | Transform bilinear a rectangle from the bitmap |
| [transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, PerspectiveTransformation.Transformation aTransform, byte aBackground)](#transformBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.PerspectiveTransformation.Transformation-byte-) | Transform shape defined by Transformation into rectangular bitmap with simple bilinear pixels interpolation |
| [transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aQuad, byte aBackground)](#transformBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-byte-) | Transform quadrangle shape into rectangular bitmap with bilinear pixels interpolation |
| [transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aResultQuad, QuadPointFs aQuad, byte aBackground)](#transformBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-byte-) | Transform quadrangle shape into rectangular bitmap with bilinear pixels interpolation |
| [transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPoints aQuad, byte aBackground)](#transformBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-byte-) | Transform quadrangle shape into rectangular bitmap with bilinear pixels interpolation |
| [transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, PerspectiveTransformation.Transformation aTransform, byte aBackground)](#transformBitmapNearestNeighbor-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.PerspectiveTransformation.Transformation-byte-) | Transform shape defined by Transformation into rectangular bitmap with simple nearest neighbor interpolation |
| [transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aQuad, byte aBackground)](#transformBitmapNearestNeighbor-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-byte-) | Transform quadrangle shape into rectangular bitmap with simple nearest neighbor interpolation |
| [transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aResultQuad, QuadPointFs aQuad, byte aBackground)](#transformBitmapNearestNeighbor-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-byte-) | Transform quadrangle shape into rectangular bitmap with simple nearest neighbor interpolation |
| [transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPoints aQuad, byte aBackground)](#transformBitmapNearestNeighbor-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-byte-) | Transform quadrangle shape into rectangular bitmap with simple nearest neighbor interpolation |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PerspectiveTransformation() {#PerspectiveTransformation--}
```
public PerspectiveTransformation()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getResultPointPositionNearestNeighbor(int resultWidth, int resultHeight, PerspectiveTransformation.Transformation aTransform, System.Drawing.Point originalPoint) {#getResultPointPositionNearestNeighbor-int-int-com.aspose.barcode.barcoderecognition.common.algorithms.PerspectiveTransformation.Transformation-com.aspose.ms.System.Drawing.Point-}
```
public static System.Drawing.Point getResultPointPositionNearestNeighbor(int resultWidth, int resultHeight, PerspectiveTransformation.Transformation aTransform, System.Drawing.Point originalPoint)
```


Returns the position of the point in transformed bitmap. NEED TO REPLACE!!!!!!! this just by aTransform.GetReversedTransformation().Transform(originalPoint);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resultWidth | int |  |
| resultHeight | int |  |
| aTransform | [Transformation](../../com.aspose.barcode.barcoderecognition.common.algorithms/transformation) |  |
| originalPoint | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
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
### transformBitmapBilinear(ByteBitmap bitmap, System.Drawing.Rectangle rectangle, System.Drawing.Size size) {#transformBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-com.aspose.ms.System.Drawing.Size-}
```
public static ByteBitmap transformBitmapBilinear(ByteBitmap bitmap, System.Drawing.Rectangle rectangle, System.Drawing.Size size)
```


Transform bilinear a rectangle from the bitmap

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bitmap |
| rectangle | com.aspose.ms.System.Drawing.Rectangle | A rectangle |
| size | com.aspose.ms.System.Drawing.Size | Result size |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - Transformed bitmap
### transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, PerspectiveTransformation.Transformation aTransform, byte aBackground) {#transformBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.PerspectiveTransformation.Transformation-byte-}
```
public static ByteBitmap transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, PerspectiveTransformation.Transformation aTransform, byte aBackground)
```


Transform shape defined by Transformation into rectangular bitmap with simple bilinear pixels interpolation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | original bitmap |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size | new bitmap size |
| aTransform | [Transformation](../../com.aspose.barcode.barcoderecognition.common.algorithms/transformation) | affine matrix https://en.wikipedia.org/wiki/3D\_projection |
| aBackground | byte | default color if we out of the original bitmap area |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - rectangular bitmap with size aResultBmpSize
### transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aQuad, byte aBackground) {#transformBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-byte-}
```
public static ByteBitmap transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aQuad, byte aBackground)
```


Transform quadrangle shape into rectangular bitmap with bilinear pixels interpolation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | original bitmap |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size | new bitmap size |
| aQuad | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) | quadrangle shape of the barcode element |
| aBackground | byte | default color if we out of the original bitmap area |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - rectangular bitmap with size aResultBmpSize
### transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aResultQuad, QuadPointFs aQuad, byte aBackground) {#transformBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-byte-}
```
public static ByteBitmap transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aResultQuad, QuadPointFs aQuad, byte aBackground)
```


Transform quadrangle shape into rectangular bitmap with bilinear pixels interpolation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | original bitmap |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size | new bitmap size |
| aResultQuad | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) | quadrangle shape on bitmap, could be different from 0, 0, Width, Height |
| aQuad | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) | quadrangle shape of the barcode element |
| aBackground | byte | default color if we out of the original bitmap area |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - rectangular bitmap with size aResultBmpSize
### transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPoints aQuad, byte aBackground) {#transformBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-byte-}
```
public static ByteBitmap transformBitmapBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPoints aQuad, byte aBackground)
```


Transform quadrangle shape into rectangular bitmap with bilinear pixels interpolation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | original bitmap |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size | new bitmap size |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | quadrangle shape of the barcode element |
| aBackground | byte | default color if we out of the original bitmap area |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - rectangular bitmap with size aResultBmpSize
### transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, PerspectiveTransformation.Transformation aTransform, byte aBackground) {#transformBitmapNearestNeighbor-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.PerspectiveTransformation.Transformation-byte-}
```
public static ByteBitmap transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, PerspectiveTransformation.Transformation aTransform, byte aBackground)
```


Transform shape defined by Transformation into rectangular bitmap with simple nearest neighbor interpolation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | original bitmap |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size | new bitmap size |
| aTransform | [Transformation](../../com.aspose.barcode.barcoderecognition.common.algorithms/transformation) | affine matrix https://en.wikipedia.org/wiki/3D\_projection |
| aBackground | byte | default color if we out of the original bitmap area |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - rectangular bitmap with size aResultBmpSize
### transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aQuad, byte aBackground) {#transformBitmapNearestNeighbor-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-byte-}
```
public static ByteBitmap transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aQuad, byte aBackground)
```


Transform quadrangle shape into rectangular bitmap with simple nearest neighbor interpolation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | original bitmap |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size | new bitmap size |
| aQuad | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) | quadrangle shape of the barcode element |
| aBackground | byte | default color if we out of the original bitmap area |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - rectangular bitmap with size aResultBmpSize
### transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aResultQuad, QuadPointFs aQuad, byte aBackground) {#transformBitmapNearestNeighbor-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-byte-}
```
public static ByteBitmap transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPointFs aResultQuad, QuadPointFs aQuad, byte aBackground)
```


Transform quadrangle shape into rectangular bitmap with simple nearest neighbor interpolation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | original bitmap |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size | new bitmap size |
| aResultQuad | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) | quadrangle shape on bitmap, could be different from 0, 0, Width, Height |
| aQuad | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) | quadrangle shape of the barcode element |
| aBackground | byte | default color if we out of the original bitmap area |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - rectangular bitmap with size aResultBmpSize
### transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPoints aQuad, byte aBackground) {#transformBitmapNearestNeighbor-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-byte-}
```
public static ByteBitmap transformBitmapNearestNeighbor(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, QuadPoints aQuad, byte aBackground)
```


Transform quadrangle shape into rectangular bitmap with simple nearest neighbor interpolation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | original bitmap |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size | new bitmap size |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | quadrangle shape of the barcode element |
| aBackground | byte | default color if we out of the original bitmap area |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - rectangular bitmap with size aResultBmpSize
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

