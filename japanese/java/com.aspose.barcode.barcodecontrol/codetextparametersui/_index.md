---
title: "CodetextParametersUI"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "UI ラッパー for com.aspose.barcode.generation.CodetextParameters クラス。"
type: docs
weight: 13
url: /ja/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

UI ラッパー for com.aspose.barcode.generation.CodetextParameters クラス。
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
| [getSpace()](#getSpace--) | CodeTextとBarCodeの間のスペース（単位はvalue）。 |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | 2Dバーコードでcodetextの代わりに表示されるテキストです。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | コードテキストの配置を設定します。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 表示されるCodeTextの色を指定します。 |
| [setFont(Font value)](#setFont-java.awt.Font-) | 表示されるCodeTextのフォントを指定します。 |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | FontModeを指定します。 |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | 表示されるCodeTextの位置を指定します。CodeLocation.Noneに設定するとCodeTextが非表示になります。 |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | 2Dバーコードでcodetextの代わりに表示されるテキストです。 |
| [toString()](#toString--) | このCodetextParametersの人間が読める文字列表現を返します。 |
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
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


コードテキストの配置を取得します。デフォルト値: StringAlignment.Center。

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
public Font getFont()
```


表示されるCodeTextのフォントを指定します。デフォルト値: Arial 5pt regular。FontModeがFontMode.AUTOに設定されている場合は無視されます。

**Returns:**
java.awt.Font
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
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


CodeTextとBarCodeの間のスペース（単位はvalue）。デフォルト値: 2pt。EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCouponでは無視されます。

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


コードテキストの配置を設定します。デフォルト値: StringAlignment.Center。

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

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


表示されるCodeTextのフォントを指定します。デフォルト値: Arial 5pt regular。FontModeがFontMode.AUTOに設定されている場合は無視されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Font |  |

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


このCodetextParametersの人間が読める文字列表現を返します。

**Returns:**
java.lang.String - このCodetextParametersを表す文字列です。
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

