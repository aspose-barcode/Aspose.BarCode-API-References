---
title: "CaptionParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "キャプションパラメーター。"
type: docs
weight: 20
url: /ja/java/com.aspose.barcode.generation/captionparameters/
---
**Inheritance:**
java.lang.Object
```
public class CaptionParameters
```

キャプションパラメーター。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CaptionParameters()](#CaptionParameters--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | キャプションテストの水平配置。 |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | キャプション フォント。 |
|  | [getNoWrap()](#getNoWrap--) | ``` |
テキスト内の単語折り返し（改行）を指定します。
``` |
| [getPadding()](#getPadding--) | Captions paddings. |
| [getText()](#getText--) | Caption text. |
| [getTextColor()](#getTextColor--) | Caption text color. |
| [getVisible()](#getVisible--) | Caption text visibility. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Caption test horizontal alignment. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setPadding(Padding value)](#setPadding-com.aspose.barcode.generation.Padding-) | キャプションの余白。 |
| [setText(String value)](#setText-java.lang.String-) | キャプション テキスト。 |
| [setTextColor(Color value)](#setTextColor-java.awt.Color-) | キャプション テキストの色。 |
| [setVisible(boolean value)](#setVisible-boolean-) | キャプション テキストの表示。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CaptionParameters() {#CaptionParameters--}
```
public CaptionParameters()
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


キャプション テストの水平配置。デフォルト値: StringAlignment.Center。

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFont() {#getFont--}
```
public FontUnit getFont()
```


キャプション フォント。デフォルト値: Arial 8pt regular。

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
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
### getPadding() {#getPadding--}
```
public Padding getPadding()
```


キャプションの余白。CaptionAbove のデフォルト値: 5pt 5pt 0 5pt。CaptionBelow のデフォルト値: 0 5pt 5pt 5pt。

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getText() {#getText--}
```
public String getText()
```


キャプション テキスト。デフォルト値: empty string。

**Returns:**
java.lang.String
### getTextColor() {#getTextColor--}
```
public Color getTextColor()
```


キャプション テキストの色。デフォルト値: Color.BLACK。

**Returns:**
java.awt.Color
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


キャプション テキストの表示。デフォルト値: false。

**Returns:**
boolean
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


キャプション テストの水平配置。デフォルト値: StringAlignment.Center。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

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

### setPadding(Padding value) {#setPadding-com.aspose.barcode.generation.Padding-}
```
public void setPadding(Padding value)
```


キャプションの余白。CaptionAbove のデフォルト値: 5pt 5pt 0 5pt。CaptionBelow のデフォルト値: 0 5pt 5pt 5pt。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Padding](../../com.aspose.barcode.generation/padding) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


キャプション テキスト。デフォルト値: empty string。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setTextColor(Color value) {#setTextColor-java.awt.Color-}
```
public void setTextColor(Color value)
```


キャプション テキストの色。デフォルト値: Color.BLACK。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


キャプション テキストの表示。デフォルト値: false。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

