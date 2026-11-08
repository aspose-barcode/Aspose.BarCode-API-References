---
title: "CodetextParametersUI"
second_title: "Aspose.BarCode for Java API Reference"
description: "UI 包装器用于 com.aspose.barcode.generation.CodetextParameters 类。"
type: docs
weight: 13
url: /zh/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

UI 包装器用于 com.aspose.barcode.generation.CodetextParameters 类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 获取代码文本的对齐方式。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 指定显示的 CodeText 的颜色。 |
| [getFont()](#getFont--) | 指定显示的 CodeText 的字体。 |
| [getFontMode()](#getFontMode--) | 指定 FontMode。 |
| [getLocation()](#getLocation--) | 指定显示的 CodeText 位置，设置为 CodeLocation.None 可隐藏 CodeText。 |
| [getSpace()](#getSpace--) | CodeText 与 BarCode 之间的间距，以  值计。 |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | 将在 2D 条码中显示的文本，替代 codetext。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | 设置代码文本的对齐方式。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 指定显示的 CodeText 的颜色。 |
| [setFont(Font value)](#setFont-java.awt.Font-) | 指定显示的 CodeText 的字体。 |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | 指定 FontMode。 |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | 指定显示的 CodeText 位置，设置为 CodeLocation.None 可隐藏 CodeText。 |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | 将在 2D 条码中显示的文本，替代 codetext。 |
| [toString()](#toString--) | 返回此 CodetextParameters 的可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


获取代码文本的对齐方式。默认值：StringAlignment.Center。

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


指定显示的 CodeText 的颜色。默认值：Color.BLACK。

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


指定显示的 CodeText 的字体。默认值：Arial 5pt regular。如果 FontMode 设置为 FontMode.AUTO，则忽略此设置。

**Returns:**
java.awt.Font
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


指定 FontMode。如果 FontMode 设置为 Auto，字体大小将根据 xDimension 值自动计算。建议在 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 中使用 FontMode.AUTO。默认值：FontMode.AUTO。

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


指定显示的 CodeText 位置，设置为 CodeLocation.None 可隐藏 CodeText。默认值：1D 条码为 CodeLocation.BELOW，2D 条码为 CodeLocation.None。

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


CodeText 与 BarCode 之间的间距，以  值计。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon 忽略。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


将在 2D 条码中显示的文本，替代 codetext。用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode。

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


设置代码文本的对齐方式。默认值：StringAlignment.Center。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


指定显示的 CodeText 的颜色。默认值：Color.BLACK。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


指定显示的 CodeText 的字体。默认值：Arial 5pt regular。如果 FontMode 设置为 FontMode.AUTO，则忽略此设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


指定 FontMode。如果 FontMode 设置为 Auto，字体大小将根据 xDimension 值自动计算。建议在 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 中使用 FontMode.AUTO。默认值：FontMode.AUTO。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


指定显示的 CodeText 位置，设置为 CodeLocation.None 可隐藏 CodeText。默认值：1D 条码为 CodeLocation.BELOW，2D 条码为 CodeLocation.None。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


将在 2D 条码中显示的文本，替代 codetext。用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


返回此 CodetextParameters 的可读字符串表示。

**Returns:**
java.lang.String - 一个表示此 CodetextParameters 的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

