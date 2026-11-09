---
title: "CodetextParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "Codetext パラメータ。"
type: docs
weight: 26
url: /ja/java/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Codetext パラメータ。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | コードテキストの配置を取得します。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 表示されるCodeTextの色を指定します。 |
| [getFont()](#getFont--) | 表示されるCodeTextのフォントを指定します。 |
| [getFontMode()](#getFontMode--) | FontModeを指定します。 |
| [getLocation()](#getLocation--) | 表示されるCodeTextの位置を指定します。CodeLocation.Noneに設定するとCodeTextが非表示になります。 |
|  | [getNoWrap()](#getNoWrap--) | ``` |
テキスト内の単語折り返し（改行）を指定します。
``` |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  Unit  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Specify the displaying CodeText's Color. |
| [setFont(FontUnit value)](#setFont-com.aspose.barcode.generation.FontUnit-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | CodeText と BarCode の間のスペース（単位値）。 |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | 2Dバーコードでcodetextの代わりに表示されるテキストです。 |
| [toString()](#toString--) | この CodetextParameters の人間が読める文字列表現を返します。 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


コードテキストの配置を取得します。デフォルト値: TextAlignment.CENTER。

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


表示されるCodeTextの色を指定します。デフォルト値: Color.BLACK。

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public FontUnit getFont()
```


表示されるCodeTextのフォントを指定します。デフォルト値: Arial 5pt regular。FontModeがFontMode.AUTOに設定されている場合は無視されます。

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


FontModeを指定します。FontModeがAutoに設定されている場合、フォントサイズはxDimension値に基づいて自動的に計算されます。特にAutoSizeMode.NEARESTまたはAutoSizeMode.INTERPOLATIONで使用する場合はFontMode.AUTOの使用が推奨されます。デフォルト値: FontMode.AUTO。

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


表示されるCodeTextの位置を指定します。CodeLocation.Noneに設定するとCodeTextが非表示になります。デフォルト値: 1Dバーコードの場合はCodeLocation.BELOW、2Dバーコードの場合はCodeLocation.Noneです。

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


2Dバーコードでcodetextの代わりに表示されるテキストです。使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


表示されるCodeTextの色を指定します。デフォルト値: Color.BLACK。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


表示されるCodeTextのフォントを指定します。デフォルト値: Arial 5pt regular。FontModeがFontMode.AUTOに設定されている場合は無視されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


FontModeを指定します。FontModeがAutoに設定されている場合、フォントサイズはxDimension値に基づいて自動的に計算されます。特にAutoSizeMode.NEARESTまたはAutoSizeMode.INTERPOLATIONで使用する場合はFontMode.AUTOの使用が推奨されます。デフォルト値: FontMode.AUTO。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


表示されるCodeTextの位置を指定します。CodeLocation.Noneに設定するとCodeTextが非表示になります。デフォルト値: 1Dバーコードの場合はCodeLocation.BELOW、2Dバーコードの場合はCodeLocation.Noneです。

**Parameters:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


CodeText と BarCode の間のスペース（単位値）。デフォルト値: 2pt。EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon では無視されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


2Dバーコードでcodetextの代わりに表示されるテキストです。使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


この CodetextParameters の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この CodetextParameters を表す文字列です。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

