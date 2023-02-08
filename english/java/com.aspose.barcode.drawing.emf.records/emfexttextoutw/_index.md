---
title: EmfExtTextOutW
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 16
url: /java/com.aspose.barcode.drawing.emf.records/emfexttextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord)
```
public class EmfExtTextOutW extends EmfRecord
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfExtTextOutW()](#EmfExtTextOutW--) |  |
| [EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.PointF point)](#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.PointF-) |  |
| [EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.Point point)](#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Point-) |  |
| [EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode)](#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Rectangle-long-) |  |
| [EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode)](#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.RectangleF-long-) |  |
| [EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode, boolean transparent)](#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.RectangleF-long-boolean-) |  |
| [EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode, boolean transparent)](#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Rectangle-long-boolean-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Bounds](#Bounds) | A WMF RectL object ([MS-WMF] section 2.2.2.19). |
| [ExScale](#ExScale) | A 32-bit floating-point value that specifies the scale factor to apply along the X axis to convert from page space units to .01mm units. |
| [EyScale](#EyScale) | A 32-bit floating-point value that specifies the scale factor to apply along the Y axis to convert from page space units to .01mm units. |
| [IGraphicsMode](#IGraphicsMode) | A 32-bit unsigned integer that specifies the graphics mode from the GraphicsMode enumeration (section 2.1.16). |
| [RecordType](#RecordType) | The type of the record |
| [Size](#Size) | The size of the record |
| [WEmrText](#WEmrText) | An EmrText object (section 2.2.5) that specifies the output string in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfExtTextOutW() {#EmfExtTextOutW--}
```
public EmfExtTextOutW()
```


### EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.PointF point) {#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.PointF-}
```
public EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.PointF point)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| point | com.aspose.ms.System.Drawing.PointF |  |

### EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.Point point) {#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Point-}
```
public EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.Point point)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| point | com.aspose.ms.System.Drawing.Point |  |

### EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode) {#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Rectangle-long-}
```
public EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| rect | com.aspose.ms.System.Drawing.Rectangle |  |
| textAlignmentMode | long |  |

### EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode) {#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.RectangleF-long-}
```
public EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| rect | com.aspose.ms.System.Drawing.RectangleF |  |
| textAlignmentMode | long |  |

### EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode, boolean transparent) {#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.RectangleF-long-boolean-}
```
public EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.RectangleF rect, long textAlignmentMode, boolean transparent)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| rect | com.aspose.ms.System.Drawing.RectangleF |  |
| textAlignmentMode | long |  |
| transparent | boolean |  |

### EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode, boolean transparent) {#EmfExtTextOutW-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Rectangle-long-boolean-}
```
public EmfExtTextOutW(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode, boolean transparent)
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


A WMF RectL object ([MS-WMF] section 2.2.2.19). It is not used and MUST be ignored on receipt.

### ExScale {#ExScale}
```
public float ExScale
```


A 32-bit floating-point value that specifies the scale factor to apply along the X axis to convert from page space units to .01mm units. This SHOULD be used only if the graphics mode specified by iGraphicsMode is GM\_COMPATIBLE.

### EyScale {#EyScale}
```
public float EyScale
```


A 32-bit floating-point value that specifies the scale factor to apply along the Y axis to convert from page space units to .01mm units. This SHOULD be used only if the graphics mode specified by iGraphicsMode is GM\_COMPATIBLE.

### IGraphicsMode {#IGraphicsMode}
```
public long IGraphicsMode
```


A 32-bit unsigned integer that specifies the graphics mode from the GraphicsMode enumeration (section 2.1.16).

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

### WEmrText {#WEmrText}
```
public EmfText WEmrText
```


An EmrText object (section 2.2.5) that specifies the output string in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values.

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

