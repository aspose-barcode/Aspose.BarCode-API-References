---
title: "ITFParameters"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "ITF パラメータ。"
type: docs
weight: 50
url: /ja/androidjava/com.aspose.barcode.generation/itfparameters/
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
| [getBorderThickness()](#getBorderThickness--) | ITFのボーダー（ベアラーバー）の厚さを単位値で取得します。 |
| [getBorderType()](#getBorderType--) | ITFバーコードのボーダータイプ。 |
| [getClass()](#getClass--) |  |
| [getQuietZoneCoef()](#getQuietZoneCoef--) | xDimensionにおけるクワイエットゾーンのサイズ。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBorderThickness(Unit value)](#setBorderThickness-com.aspose.barcode.generation.Unit-) | ITFのボーダー（ベアラーバー）の厚さを単位値で設定します。 |
| [setBorderType(ITF14BorderType value)](#setBorderType-com.aspose.barcode.generation.ITF14BorderType-) | ITFバーコードのボーダータイプ。 |
| [setQuietZoneCoef(int value)](#setQuietZoneCoef-int-) | xDimensionにおけるクワイエットゾーンのサイズ。 |
| [toString()](#toString--) | この[ITFParameters](../../com.aspose.barcode.generation/itfparameters)の人間が読める文字列表現を返します。 |
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


ITFのボーダー（ベアラーバー）の厚さを単位値で取得します。デフォルト値: 12pt。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - an ITF border (bearer bar) thickness in Unit value.
### getBorderType() {#getBorderType--}
```
public final ITF14BorderType getBorderType()
```


ITFバーコードのボーダータイプ。デフォルト値: ITF14BorderType.Bar。

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


xDimensionにおけるクワイエットゾーンのサイズ。デフォルト値: 10、つまりxDimensionが2pxの場合、クワイエットゾーンは20pxになります。

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


ITFのボーダー（ベアラーバー）の厚さを単位値で設定します。デフォルト値: 12pt。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | 単位値で表したITFボーダー（ベアラーバー）の厚さ。 |

### setBorderType(ITF14BorderType value) {#setBorderType-com.aspose.barcode.generation.ITF14BorderType-}
```
public final void setBorderType(ITF14BorderType value)
```


ITFバーコードのボーダータイプ。デフォルト値: ITF14BorderType.Bar。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ITF14BorderType](../../com.aspose.barcode.generation/itf14bordertype) |  |

### setQuietZoneCoef(int value) {#setQuietZoneCoef-int-}
```
public final void setQuietZoneCoef(int value)
```


xDimensionにおけるクワイエットゾーンのサイズ。デフォルト値: 10、つまりxDimensionが2pxの場合、クワイエットゾーンは20pxになります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toString() {#toString--}
```
public String toString()
```


この[ITFParameters](../../com.aspose.barcode.generation/itfparameters)の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この[ITFParameters](../../com.aspose.barcode.generation/itfparameters)を表す文字列。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

