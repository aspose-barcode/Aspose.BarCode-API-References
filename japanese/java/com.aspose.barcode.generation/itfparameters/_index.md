---
title: "ITFParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "ITF パラメータ。"
type: docs
weight: 50
url: /ja/java/com.aspose.barcode.generation/itfparameters/
---
**Inheritance:**
java.lang.Object
```
public class ITFParameters
```

ITF パラメータ。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBorderThickness()](#getBorderThickness--) | ITF のボーダー（ベアラーバー）の厚さを単位値で取得します。 |
| [getBorderType()](#getBorderType--) | ITF バーコードのボーダータイプ。 |
| [getClass()](#getClass--) |  |
| [getQuietZoneCoef()](#getQuietZoneCoef--) | xDimension における静止領域のサイズ。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBorderThickness(Unit value)](#setBorderThickness-com.aspose.barcode.generation.Unit-) | ITF のボーダー（ベアラーバー）の厚さを単位値で設定します。 |
| [setBorderType(ITF14BorderType value)](#setBorderType-com.aspose.barcode.generation.ITF14BorderType-) | ITF バーコードのボーダータイプ。 |
| [setQuietZoneCoef(int value)](#setQuietZoneCoef-int-) | xDimension における静止領域のサイズ。 |
| [toString()](#toString--) | この [ITFParameters](../../com.aspose.barcode.generation/itfparameters) の人間が読みやすい文字列表現を返します。 |
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
### getBorderThickness() {#getBorderThickness--}
```
public final Unit getBorderThickness()
```


ITF のボーダー（ベアラーバー）の厚さを単位値で取得します。デフォルト値: 12pt。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - an ITF border (bearer bar) thickness in Unit value.
### getBorderType() {#getBorderType--}
```
public final ITF14BorderType getBorderType()
```


ITF バーコードのボーダータイプ。デフォルト値: ITF14BorderType.Bar。

**Returns:**
[ITF14BorderType](../../com.aspose.barcode.generation/itf14bordertype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getQuietZoneCoef() {#getQuietZoneCoef--}
```
public final int getQuietZoneCoef()
```


xDimension における静止領域のサイズ。デフォルト値: 10、つまり xDimension = 2px の場合、静止領域は 20px になります。

**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
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




### setBorderThickness(Unit value) {#setBorderThickness-com.aspose.barcode.generation.Unit-}
```
public final void setBorderThickness(Unit value)
```


ITF のボーダー（ベアラーバー）の厚さを単位値で設定します。デフォルト値: 12pt。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | ITF のボーダー（ベアラーバー）の厚さ（単位値）。 |

### setBorderType(ITF14BorderType value) {#setBorderType-com.aspose.barcode.generation.ITF14BorderType-}
```
public final void setBorderType(ITF14BorderType value)
```


ITF バーコードのボーダータイプ。デフォルト値: ITF14BorderType.Bar。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ITF14BorderType](../../com.aspose.barcode.generation/itf14bordertype) |  |

### setQuietZoneCoef(int value) {#setQuietZoneCoef-int-}
```
public final void setQuietZoneCoef(int value)
```


xDimension における静止領域のサイズ。デフォルト値: 10、つまり xDimension = 2px の場合、静止領域は 20px になります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toString() {#toString--}
```
public String toString()
```


この [ITFParameters](../../com.aspose.barcode.generation/itfparameters) の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この [ITFParameters](../../com.aspose.barcode.generation/itfparameters) を表す文字列です。
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

