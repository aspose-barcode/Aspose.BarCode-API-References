---
title: CaptionParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Caption parameters.
type: docs
weight: 20
url: /ja/androidjava/com.aspose.barcode.generation/captionparameters/
---
**Inheritance:**
java.lang.Object
```
public class CaptionParameters
```

Caption parameters.
## Constructors

| Constructor | Description |
| --- | --- |
| [CaptionParameters()](#CaptionParameters--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | キャプションテストの水平配置。 |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | キャプションフォント。 |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Specify word wraps (line breaks) within text.
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
| [setText(String value)](#setText-java.lang.String-) | キャプションテキスト。 |
| [setTextColor(int value)](#setTextColor-int-) | キャプションテキストの色。 |
| [setVisible(boolean value)](#setVisible-boolean-) | キャプションテキストの表示可否。 |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


キャプションテストの水平配置。デフォルト値: StringAlignment.Center。

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


キャプションフォント。デフォルト値: Arial 8pt regular。

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


キャプションテキスト。デフォルト値: 空文字列。

**Returns:**
java.lang.String
### getTextColor() {#getTextColor--}
```
public int getTextColor()
```


キャプションテキストの色。デフォルト値: Color.BLACK。

**Returns:**
int
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


キャプションテキストの表示可否。デフォルト値: false。

**Returns:**
boolean
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


キャプションテストの水平配置。デフォルト値: StringAlignment.Center。

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### setPadding(Padding value) {#setPadding-com.aspose.barcode.generation.Padding-}
```
public void setPadding(Padding value)
```


キャプションの余白。CaptionAbove のデフォルト値: 5pt 5pt 0 5pt。CaptionBelow のデフォルト値: 0 5pt 5pt 5pt。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Padding](../../com.aspose.barcode.generation/padding) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


キャプションテキスト。デフォルト値: 空文字列。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setTextColor(int value) {#setTextColor-int-}
```
public void setTextColor(int value)
```


キャプションテキストの色。デフォルト値: Color.BLACK。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


キャプションテキストの表示可否。デフォルト値: false。

**Parameters:**
| Parameter | Type | Description |
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

