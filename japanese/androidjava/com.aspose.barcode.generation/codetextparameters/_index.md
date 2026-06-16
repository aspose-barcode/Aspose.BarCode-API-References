---
title: CodetextParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Codetext parameters.
type: docs
weight: 27
url: /ja/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Codetext parameters.
## Constructors

| Constructor | Description |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
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
|  | [getNoWrap()](#getNoWrap--) | ``` |
Specify word wraps (line breaks) within text.
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
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Space between the CodeText and the BarCode in  Unit  value. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Text that will be displayed instead of codetext in 2D barcodes. |
| [toString()](#toString--) | Returns a human-readable string representation of this  CodetextParameters . |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Gets the alignment of the code text. Default value: TextAlignment.CENTER.

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


表示される CodeText の色を指定します。デフォルト値: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


表示される CodeText のフォントを指定します。デフォルト値: Arial 5pt regular。FontMode が FontMode.AUTO に設定されている場合は無視されます。

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


FontMode を指定します。FontMode が Auto に設定されている場合、フォントサイズは xDimension の値に基づいて自動的に計算されます。特に AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION を使用する場合は FontMode.AUTO の使用が推奨されます。デフォルト値: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


表示される CodeText の位置を指定します。CodeLocation.None に設定すると CodeText が非表示になります。デフォルト値: 1D バーコードの場合は CodeLocation.BELOW、2D バーコードの場合は CodeLocation.None。

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


CodeText と BarCode の間のスペース（単位値）。デフォルト値: 2pt。EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon では無視されます。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


2D バーコードで codetext の代わりに表示されるテキスト。使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode。

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


コードテキストの配置を設定します。デフォルト値: TextAlignment.CENTER。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


表示される CodeText の色を指定します。デフォルト値: Color.BLACK.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


表示される CodeText のフォントを指定します。デフォルト値: Arial 5pt regular。FontMode が FontMode.AUTO に設定されている場合は無視されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


FontMode を指定します。FontMode が Auto に設定されている場合、フォントサイズは xDimension の値に基づいて自動的に計算されます。特に AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION を使用する場合は FontMode.AUTO の使用が推奨されます。デフォルト値: FontMode.AUTO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


表示される CodeText の位置を指定します。CodeLocation.None に設定すると CodeText が非表示になります。デフォルト値: 1D バーコードの場合は CodeLocation.BELOW、2D バーコードの場合は CodeLocation.None。

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


CodeText と BarCode の間のスペース（単位値）。デフォルト値: 2pt。EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon では無視されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


2D バーコードで codetext の代わりに表示されるテキスト。使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  CodetextParameters .

**Returns:**
java.lang.String - この CodetextParameters を表す文字列です。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

