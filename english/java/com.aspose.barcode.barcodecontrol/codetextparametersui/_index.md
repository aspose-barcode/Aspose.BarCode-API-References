---
title: CodetextParametersUI
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Gets the alignment of the code text. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Specify the displaying CodeText's Color. |
| [getFont()](#getFont--) | Specify the displaying CodeText's font. |
| [getFontMode()](#getFontMode--) | Specify FontMode. |
| [getLocation()](#getLocation--) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Specify the displaying CodeText's Color. |
| [setFont(Font value)](#setFont-java.awt.Font-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Text that will be displayed instead of codetext in 2D barcodes. |
| [toString()](#toString--) | Returns a human-readable string representation of this . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Gets the alignment of the code text. Default value: StringAlignment.Center.

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Specify the displaying CodeText's Color. Default value: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


Specify the displaying CodeText's font. Default value: Arial 5pt regular. Ignored if FontMode is set to FontMode.AUTO.

**Returns:**
java.awt.Font
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Specify FontMode. If FontMode is set to Auto, font size will be calculated automatically based on xDimension value. It is recommended to use FontMode.AUTO especially in AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. Default value: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. Default value: CodeLocation.BELOW for 1D barcodes and CodeLocation.None for 2D barcodes.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Space between the CodeText and the BarCode in  value. Default value: 2pt. Ignored for EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Text that will be displayed instead of codetext in 2D barcodes. Used for: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Returns:**
java.lang.String
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




### setAlignment(TextAlignment value) {#setAlignment-com.aspose.barcode.generation.TextAlignment-}
```
public void setAlignment(TextAlignment value)
```


Sets the alignment of the code text. Default value: StringAlignment.Center.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Specify the displaying CodeText's Color. Default value: Color.BLACK.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


Specify the displaying CodeText's font. Default value: Arial 5pt regular. Ignored if FontMode is set to FontMode.AUTO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Specify FontMode. If FontMode is set to Auto, font size will be calculated automatically based on xDimension value. It is recommended to use FontMode.AUTO especially in AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. Default value: FontMode.AUTO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. Default value: CodeLocation.BELOW for 1D barcodes and CodeLocation.None for 2D barcodes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Text that will be displayed instead of codetext in 2D barcodes. Used for: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this .

**Returns:**
java.lang.String - A string that represents this .
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

