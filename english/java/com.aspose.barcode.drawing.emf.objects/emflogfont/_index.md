---
title: EmfLogFont
second_title: Aspose.BarCode for Java API Reference
description: The LogFont object specifies the basic attributes of a logical font.
type: docs
weight: 15
url: /java/com.aspose.barcode.drawing.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.drawing.emf.objects.XmfObject
```
public class EmfLogFont extends XmfObject
```

The LogFont object specifies the basic attributes of a logical font. https://docs.microsoft.com/en-us/windows/win32/api/wingdi/ns-wingdi-logfonta
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogFont()](#EmfLogFont--) |  |
| [EmfLogFont(EmfFontObj fontObj)](#EmfLogFont-com.aspose.barcode.drawing.emf.data.EmfFontObj-) |  |
## Fields

| Field | Description |
| --- | --- |
| [CharSet](#CharSet) | An 8-bit unsigned integer that specifies the set of character glyphs. |
| [ClipPrecision](#ClipPrecision) | An 8-bit unsigned integer that specifies the clipping precision. |
| [Escapement](#Escapement) | A 32-bit signed integer that specifies the angle, in tenths of degrees, between the escapement vector and the x-axis of the device. |
| [FacenameData](#FacenameData) | A string of no more than 32 Unicode characters that specifies the typeface name of the font. |
| [Height](#Height) | A 32-bit signed integer that specifies the height, in logical units, of the font's character cell or character. |
| [Italic](#Italic) | An 8-bit unsigned integer that specifies an italic font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [Orientation](#Orientation) | A 32-bit signed integer that specifies the angle, in tenths of degrees, between each character's baseline and the x-axis of the device. |
| [OutPrecision](#OutPrecision) | An 8-bit unsigned integer that specifies the output precision. |
| [PitchAndFamily](#PitchAndFamily) | A WMF PitchAndFamily object ([MS-WMF] section 2.2.2.14) that specifies the pitch and family of the font. |
| [Quality](#Quality) | An 8-bit unsigned integer that specifies the output quality. |
| [StrikeOut](#StrikeOut) | An 8-bit unsigned integer that specifies a strikeout font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [Underline](#Underline) | An 8-bit unsigned integer that specifies an underlined font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [Weight](#Weight) | A 32-bit signed integer that specifies the weight of the font in the range zero through 1000. |
| [Width](#Width) | A 32-bit signed integer that specifies the average width, in logical units, of characters in the font. |
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
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### EmfLogFont(EmfFontObj fontObj) {#EmfLogFont-com.aspose.barcode.drawing.emf.data.EmfFontObj-}
```
public EmfLogFont(EmfFontObj fontObj)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontObj | [EmfFontObj](../../com.aspose.barcode.drawing.emf.data/emffontobj) |  |

### CharSet {#CharSet}
```
public byte CharSet
```


An 8-bit unsigned integer that specifies the set of character glyphs. It MUST be a value in the WMF CharacterSet enumeration ([MS-WMF] section 2.1.1.5). If the character set is unknown, metafile processing SHOULD NOT attempt to translate or interpret strings that are rendered with that font.

### ClipPrecision {#ClipPrecision}
```
public byte ClipPrecision
```


An 8-bit unsigned integer that specifies the clipping precision. The clipping precision defines how to clip characters that are partially outside the clipping region. It can be one or more of the WMF ClipPrecision Flags

### Escapement {#Escapement}
```
public int Escapement
```


A 32-bit signed integer that specifies the angle, in tenths of degrees, between the escapement vector and the x-axis of the device. The escapement vector is parallel to the baseline of a row of text.

### FacenameData {#FacenameData}
```
public byte[] FacenameData
```


A string of no more than 32 Unicode characters that specifies the typeface name of the font. If the length of this string is less than 32 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

### Height {#Height}
```
public int Height
```


A 32-bit signed integer that specifies the height, in logical units, of the font's character cell or character. The character height value, also known as the em size, is the character cell height value minus the internal leading value. The font mapper SHOULD interpret the value specified in the Height field in the following manner. +0 = points; -0 pixels

### Italic {#Italic}
```
public byte Italic
```


An 8-bit unsigned integer that specifies an italic font if set to 0x01; otherwise, it MUST be set to 0x00.

### Orientation {#Orientation}
```
public int Orientation
```


A 32-bit signed integer that specifies the angle, in tenths of degrees, between each character's baseline and the x-axis of the device.

### OutPrecision {#OutPrecision}
```
public byte OutPrecision
```


An 8-bit unsigned integer that specifies the output precision. The output precision defines how closely the font is required to match the requested height, width, character orientation, escapement, pitch, and font type. It MUST be a value from the WMF OutPrecision enumeration

### PitchAndFamily {#PitchAndFamily}
```
public WmfPitchAndFamily PitchAndFamily
```


A WMF PitchAndFamily object ([MS-WMF] section 2.2.2.14) that specifies the pitch and family of the font. Font families describe the look of a font in a general way. They are intended for specifying a font when the specified typeface is not available.

### Quality {#Quality}
```
public byte Quality
```


An 8-bit unsigned integer that specifies the output quality. The output quality defines how closely to attempt to match the logical-font attributes to those of an actual physical font. It MUST be one of the values in the WMF FontQuality enumeration ([MS-WMF] section 2.1.1.10).

### StrikeOut {#StrikeOut}
```
public byte StrikeOut
```


An 8-bit unsigned integer that specifies a strikeout font if set to 0x01; otherwise, it MUST be set to 0x00.

### Underline {#Underline}
```
public byte Underline
```


An 8-bit unsigned integer that specifies an underlined font if set to 0x01; otherwise, it MUST be set to 0x00.

### Weight {#Weight}
```
public int Weight
```


A 32-bit signed integer that specifies the weight of the font in the range zero through 1000. For example, 400 is normal and 700 is bold. If this value is zero, a default weight can be used.

### Width {#Width}
```
public int Width
```


A 32-bit signed integer that specifies the average width, in logical units, of characters in the font. If the Width field value is zero, an appropriate value SHOULD be calculated from other LogFont values to find a font that has the typographer's intended aspect ratio

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

