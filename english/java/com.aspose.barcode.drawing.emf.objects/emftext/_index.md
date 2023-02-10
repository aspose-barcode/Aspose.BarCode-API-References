---
title: EmfText
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 20
url: /java/com.aspose.barcode.drawing.emf.objects/emftext/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.drawing.emf.objects.XmfObject
```
public class EmfText extends XmfObject
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfText()](#EmfText--) |  |
| [EmfText(String text, EmfFontObj fontObj, System.Drawing.Point point, int objShift)](#EmfText-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Point-int-) |  |
| [EmfText(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode, int objShift, boolean transparent)](#EmfText-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Rectangle-long-int-boolean-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Chars](#Chars) | A 32-bit unsigned integer that specifies the number of characters in the string |
| [DxBuffer](#DxBuffer) | Gets or sets the optional character spacing buffer UndefinedSpace2 (variable): An optional number of unused bytes. |
| [OffDx](#OffDx) | A 32-bit unsigned integer that specifies the offset to an inter character spacing array, in bytes, from the start of the record in which this object is contained. |
| [OffString](#OffString) | A 32-bit unsigned integer that specifies the offset to the output string, in bytes, from the start of the record in which this object is contained. |
| [Options](#Options) | A 32-bit unsigned integer that specifies how to use the rectangle specified in the Rectangle field. |
| [PadBytesCntForStringBuffer](#PadBytesCntForStringBuffer) |  |
| [Rectangle](#Rectangle) | An optional WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a clipping and/or opaquing rectangle in logical units. |
| [Reference](#Reference) | A WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the coordinates of the reference point used to position the string. |
| [StringBuffer](#StringBuffer) | The character string buffer UndefinedSpace1 (variable): An optional number of unused bytes. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSize()](#getSize--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfText() {#EmfText--}
```
public EmfText()
```


### EmfText(String text, EmfFontObj fontObj, System.Drawing.Point point, int objShift) {#EmfText-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Point-int-}
```
public EmfText(String text, EmfFontObj fontObj, System.Drawing.Point point, int objShift)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| point | com.aspose.ms.System.Drawing.Point |  |
| objShift | int |  |

### EmfText(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode, int objShift, boolean transparent) {#EmfText-java.lang.String-com.aspose.barcode.drawing.emf.data.EmfFontObj-com.aspose.ms.System.Drawing.Rectangle-long-int-boolean-}
```
public EmfText(String text, EmfFontObj fontObj, System.Drawing.Rectangle rect, long textAlignmentMode, int objShift, boolean transparent)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |
| rect | com.aspose.ms.System.Drawing.Rectangle |  |
| textAlignmentMode | long |  |
| objShift | int |  |
| transparent | boolean |  |

### Chars {#Chars}
```
public long Chars
```


A 32-bit unsigned integer that specifies the number of characters in the string

### DxBuffer {#DxBuffer}
```
public long[] DxBuffer
```


Gets or sets the optional character spacing buffer UndefinedSpace2 (variable): An optional number of unused bytes. The OutputDx field is not required to follow immediately the preceding portion of this structure. OutputDx (variable): An array of 32-bit unsigned integers that specify the output spacing between the origins of adjacent character cells in logical units. The location of this field is specified by the value of offDx in bytes from the start of this record. If spacing is defined, this field contains the same number of values as characters in the output string. If the Options field of the EmrText object contains the ETO\_PDY flag, then this buffer contains twice as many values as there are characters in the output string, one horizontal and one vertical offset for each, in that order. If ETO\_RTLREADING is specified, characters are laid right to left instead of left to right. No other options affect the interpretation of this field.

### OffDx {#OffDx}
```
public long OffDx
```


A 32-bit unsigned integer that specifies the offset to an inter character spacing array, in bytes, from the start of the record in which this object is contained. This value MUST be 32-bit aligned.

### OffString {#OffString}
```
public long OffString
```


A 32-bit unsigned integer that specifies the offset to the output string, in bytes, from the start of the record in which this object is contained. This value MUST be 8- or 16-bit aligned, according to the character format

### Options {#Options}
```
public long Options
```


A 32-bit unsigned integer that specifies how to use the rectangle specified in the Rectangle field. This field can be a combination of more than one ExtTextOutOptions enumeration (section 2.1.11) values

### PadBytesCntForStringBuffer {#PadBytesCntForStringBuffer}
```
public int PadBytesCntForStringBuffer
```


### Rectangle {#Rectangle}
```
public WmfRectL Rectangle
```


An optional WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a clipping and/or opaquing rectangle in logical units. This rectangle is applied to the text output performed by the containing record.

### Reference {#Reference}
```
public WmfPointL Reference
```


A WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the coordinates of the reference point used to position the string. The reference point is defined by the last EMR\_SETTEXTALIGN record (section 2.3.11.25). If no such record has been set, the default alignment is TA\_LEFT,TA\_TOP.

### StringBuffer {#StringBuffer}
```
public byte[] StringBuffer
```


The character string buffer UndefinedSpace1 (variable): An optional number of unused bytes. The OutputString field is not required to follow immediately the preceding portion of this structure. OutputString (variable): An array of characters that specify the string to output. The location of this field is specified by the value of offString in bytes from the start of this record. The number of characters is specified by the value of Chars.

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
### getSize() {#getSize--}
```
public int getSize()
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

