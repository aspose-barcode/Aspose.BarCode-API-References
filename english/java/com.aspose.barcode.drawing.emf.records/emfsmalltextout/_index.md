---
title: EmfSmallTextOut
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 35
url: /java/com.aspose.barcode.drawing.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord)
```
public class EmfSmallTextOut extends EmfRecord
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSmallTextOut()](#EmfSmallTextOut--) |  |
| [EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.PointF point)](#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.PointF-) |  |
| [EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.Point point)](#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Point-) |  |
| [EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode)](#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.RectangleF-long-) |  |
| [EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode)](#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Rectangle-long-) |  |
| [EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode, boolean transparent)](#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.RectangleF-long-boolean-) |  |
| [EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode, boolean transparent)](#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Rectangle-long-boolean-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Bounds](#Bounds) | An optional, 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [CChars](#CChars) | A 32-bit unsigned integer specifying the number of 16-bit characters in the string. |
| [ExScale](#ExScale) | A 32-bit floating-point value that specifies how much to scale the text in the x-direction. |
| [EyScale](#EyScale) | A 32-bit floating-point value that specifies how much to scale the text in the y-direction. |
| [FuOptions](#FuOptions) | A 32-bit unsigned integer specifying the text output options to use. |
| [IGraphicsMode](#IGraphicsMode) | A 32-bit unsigned integer specifying the graphics mode, from the GraphicsMode enumeration (section 2.1.16). |
| [PadBytesCntForTextData](#PadBytesCntForTextData) |  |
| [RecordType](#RecordType) | The type of the record |
| [Size](#Size) | The size of the record |
| [TextData](#TextData) | A variable-length string that contains the text string to draw, in either 8-bit or 16-bit character codes, according to the value of the fuOptions field. |
| [X](#X) | A 32-bit signed integer specifying the x-coordinate of where to place the string. |
| [Y](#Y) | A 32-bit signed integer specifying the y-coordinate of where to place the string. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getObjectSize()](#getObjectSize--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfSmallTextOut() {#EmfSmallTextOut--}
```
public EmfSmallTextOut()
```


### EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.PointF point) {#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.PointF-}
```
public EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.PointF point)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| point | com.aspose.ms.System.Drawing.PointF |  |

### EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.Point point) {#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Point-}
```
public EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.Point point)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| point | com.aspose.ms.System.Drawing.Point |  |

### EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode) {#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.RectangleF-long-}
```
public EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| rect | com.aspose.ms.System.Drawing.RectangleF |  |
| textAlignmentMode | long |  |

### EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode) {#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Rectangle-long-}
```
public EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| rect | com.aspose.ms.System.Drawing.Rectangle |  |
| textAlignmentMode | long |  |

### EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode, boolean transparent) {#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.RectangleF-long-boolean-}
```
public EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode, boolean transparent)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| rect | com.aspose.ms.System.Drawing.RectangleF |  |
| textAlignmentMode | long |  |
| transparent | boolean |  |

### EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode, boolean transparent) {#EmfSmallTextOut-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Rectangle-long-boolean-}
```
public EmfSmallTextOut(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode, boolean transparent)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| rect | com.aspose.ms.System.Drawing.Rectangle |  |
| textAlignmentMode | long |  |
| transparent | boolean |  |

### Bounds {#Bounds}
```
public WmfRectL Bounds
```


An optional, 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units.

### CChars {#CChars}
```
public long CChars
```


A 32-bit unsigned integer specifying the number of 16-bit characters in the string. The string is NOT null-terminated.

### ExScale {#ExScale}
```
public float ExScale
```


A 32-bit floating-point value that specifies how much to scale the text in the x-direction.

### EyScale {#EyScale}
```
public float EyScale
```


A 32-bit floating-point value that specifies how much to scale the text in the y-direction.

### FuOptions {#FuOptions}
```
public long FuOptions
```


A 32-bit unsigned integer specifying the text output options to use. These options are specified by one or a combination of values from the ExtTextOutOptions enumeration (section 2.1.11).

### IGraphicsMode {#IGraphicsMode}
```
public long IGraphicsMode
```


A 32-bit unsigned integer specifying the graphics mode, from the GraphicsMode enumeration (section 2.1.16).

### PadBytesCntForTextData {#PadBytesCntForTextData}
```
public int PadBytesCntForTextData
```


### RecordType {#RecordType}
```
public long RecordType
```


The type of the record

### Size {#Size}
```
public int Size
```


The size of the record

### TextData {#TextData}
```
public byte[] TextData
```


A variable-length string that contains the text string to draw, in either 8-bit or 16-bit character codes, according to the value of the fuOptions field.

### X {#X}
```
public int X
```


A 32-bit signed integer specifying the x-coordinate of where to place the string.

### Y {#Y}
```
public int Y
```


A 32-bit signed integer specifying the y-coordinate of where to place the string.

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
### getObjectSize() {#getObjectSize--}
```
public int getObjectSize()
```




**Returns:**
int
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

