---
title: CodetextParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 编码文本参数。
type: docs
weight: 27
url: /zh/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

编码文本参数。
## Constructors

| Constructor | 描述 |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 获取代码文本的对齐方式。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 指定显示的 CodeText 颜色。 |
| [getFont()](#getFont--) | 指定显示的 CodeText 字体。 |
| [getFontMode()](#getFontMode--) | 指定 FontMode。 |
| [getLocation()](#getLocation--) | 指定显示的 CodeText 位置，设置为 CodeLocation.None 可隐藏 CodeText。 |
|  | [getNoWrap()](#getNoWrap--) | ``` |
指定文本内的自动换行（换行符）。
``` |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  Unit  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(int value)](#setColor-int-) | Specify the displaying CodeText's Color. |
| [setFont(FontUnit value)](#setFont-com.aspose.barcode.generation.FontUnit-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | CodeText 与条形码之间的间距，以 Unit 为单位。 |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | 在二维条码中显示的文本，替代 codetext。 |
| [toString()](#toString--) | 返回此 CodetextParameters 的可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodetextParameters() {#CodetextParameters--}
```
public CodetextParameters()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


获取代码文本的对齐方式。默认值：TextAlignment.CENTER。

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
public int getColor()
```


指定显示的 CodeText 的颜色。默认值：Color.BLACK。

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


指定显示的 CodeText 的字体。默认值：Arial 5pt regular。若 FontMode 被设置为 FontMode.AUTO，则此设置被忽略。

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


指定 FontMode。若 FontMode 被设置为 Auto，字体大小将根据 xDimension 值自动计算。建议在 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 中使用 FontMode.AUTO。默认值：FontMode.AUTO。

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


指定显示的 CodeText 位置，设置为 CodeLocation.None 可隐藏 CodeText。默认值：1D 条码为 CodeLocation.BELOW，2D 条码为 CodeLocation.None。

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getNoWrap() {#getNoWrap--}
```
public boolean getNoWrap()
```


```
Specify word wraps (line breaks) within text.
 Default value: false.
```

**Returns:**
boolean
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


CodeText 与 BarCode 之间的间距（单位值）。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon 忽略此设置。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


在 2D 条码中将显示的文本（替代 codetext）。适用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode。

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


设置代码文本的对齐方式。默认值：TextAlignment.CENTER。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


指定显示的 CodeText 的颜色。默认值：Color.BLACK。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


指定显示的 CodeText 的字体。默认值：Arial 5pt regular。若 FontMode 被设置为 FontMode.AUTO，则此设置被忽略。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


指定 FontMode。若 FontMode 被设置为 Auto，字体大小将根据 xDimension 值自动计算。建议在 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 中使用 FontMode.AUTO。默认值：FontMode.AUTO。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


指定显示的 CodeText 位置，设置为 CodeLocation.None 可隐藏 CodeText。默认值：1D 条码为 CodeLocation.BELOW，2D 条码为 CodeLocation.None。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setNoWrap(boolean value) {#setNoWrap-boolean-}
```
public void setNoWrap(boolean value)
```


```
Specify word wraps (line breaks) within text
```

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


CodeText 与 BarCode 之间的间距（单位值）。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon 忽略此设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


在 2D 条码中将显示的文本（替代 codetext）。适用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


返回此 CodetextParameters 的可读字符串表示。

**Returns:**
java.lang.String - 表示此 CodetextParameters 的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

