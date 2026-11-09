---
title: "SvgParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "SVG パラメータ。"
type: docs
weight: 65
url: /ja/java/com.aspose.barcode.generation/svgparameters/
---
**Inheritance:**
java.lang.Object
```
public class SvgParameters
```

SVG パラメータ。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSvgColorMode()](#getSvgColorMode--) | svg ファイルの塗りつぶし色の可能なモード。RGB がデフォルトで、SVG 1.1 でサポートされています。 |
| [hashCode()](#hashCode--) |  |
| [isExplicitSizeInPixels()](#isExplicitSizeInPixels--) | SVG 画像にピクセル単位の明示的なサイズが含まれているか（推奨）。デフォルト値: true。 |
| [isTextDrawnInTextElement()](#isTextDrawnInTextElement--) | SVG 画像がパスではなくテキスト要素としてテキストを含んでいるか（推奨）。デフォルト値: true。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExplicitSizeInPixels(boolean explicitSizeInPixels)](#setExplicitSizeInPixels-boolean-) | SVG 画像にピクセル単位の明示的なサイズが含まれているか（推奨）。デフォルト値: true。 |
| [setSvgColorMode(SvgColorMode value)](#setSvgColorMode-com.aspose.barcode.generation.SvgColorMode-) | svg ファイルの塗りつぶし色の可能なモード。RGB がデフォルトで、SVG 1.1 でサポートされています。 |
| [setTextDrawnInTextElement(boolean textDrawnInTextElement)](#setTextDrawnInTextElement-boolean-) | SVG 画像がパスではなくテキスト要素としてテキストを含んでいるか（推奨）。デフォルト値: true。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSvgColorMode() {#getSvgColorMode--}
```
public SvgColorMode getSvgColorMode()
```


SVG ファイルで色を塗りつぶす際の可能なモード。RGB がデフォルトであり、SVG 1.1 でサポートされています。RGBA、HSL、HSLA は SVG 2.0 標準で許可されています。RGB の場合でも、不透明度は \"fill-opacity\" パラメータで設定されます。

**Returns:**
[SvgColorMode](../../com.aspose.barcode.generation/svgcolormode)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isExplicitSizeInPixels() {#isExplicitSizeInPixels--}
```
public boolean isExplicitSizeInPixels()
```


SVG 画像にピクセル単位の明示的なサイズが含まれているか（推奨）。デフォルト値: true。

**Returns:**
boolean
### isTextDrawnInTextElement() {#isTextDrawnInTextElement--}
```
public boolean isTextDrawnInTextElement()
```


SVG 画像がパスではなくテキスト要素としてテキストを含んでいるか（推奨）。デフォルト値: true。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setExplicitSizeInPixels(boolean explicitSizeInPixels) {#setExplicitSizeInPixels-boolean-}
```
public void setExplicitSizeInPixels(boolean explicitSizeInPixels)
```


SVG 画像にピクセル単位の明示的なサイズが含まれているか（推奨）。デフォルト値: true。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| explicitSizeInPixels | boolean |  |

### setSvgColorMode(SvgColorMode value) {#setSvgColorMode-com.aspose.barcode.generation.SvgColorMode-}
```
public void setSvgColorMode(SvgColorMode value)
```


SVG ファイルで色を塗りつぶす際の可能なモード。RGB がデフォルトであり、SVG 1.1 でサポートされています。RGBA、HSL、HSLA は SVG 2.0 標準で許可されています。RGB の場合でも、不透明度は \"fill-opacity\" パラメータで設定されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [SvgColorMode](../../com.aspose.barcode.generation/svgcolormode) |  |

### setTextDrawnInTextElement(boolean textDrawnInTextElement) {#setTextDrawnInTextElement-boolean-}
```
public void setTextDrawnInTextElement(boolean textDrawnInTextElement)
```


SVG 画像がパスではなくテキスト要素としてテキストを含んでいるか（推奨）。デフォルト値: true。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| textDrawnInTextElement | boolean |  |

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

