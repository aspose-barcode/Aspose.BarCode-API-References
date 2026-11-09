---
title: "GS1CompositeBarExtendedParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "GS1 Composite Bar が認識したバーコードの特別なデータを格納します"
type: docs
weight: 32
url: /ja/java/com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class GS1CompositeBarExtendedParameters extends BaseExtendedParameters
```

認識された **GS1 Composite Bar** の特別なデータを格納します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された  GS1CompositeBarExtendedParameters  の値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getOneDCodeText()](#getOneDCodeText--) | GS1 Composite の 1D（線形）バーコード値を取得します |
| [getOneDType()](#getOneDType--) | GS1 Composite の 1D（線形）バーコードタイプを取得します |
| [getTwoDCodeText()](#getTwoDCodeText--) | GS1 Composite の 2D バーコード値を取得します |
| [getTwoDType()](#getTwoDType--) | GS1 Composite の 2D バーコードタイプを取得します |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | すべてのパラメーターがデフォルト値のみであるかテストします |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この  GS1CompositeBarExtendedParameters の人間が読みやすい文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された  GS1CompositeBarExtendedParameters  の値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための System.Object 値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は **false** 。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOneDCodeText() {#getOneDCodeText--}
```
public String getOneDCodeText()
```


GS1 Composite の 1D（線形）バーコード値を取得します

値: 1D バーコード値

**Returns:**
java.lang.String
### getOneDType() {#getOneDType--}
```
public SingleDecodeType getOneDType()
```


GS1 Composite の 1D（線形）バーコードタイプを取得します

値: 2D バーコードタイプ

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getTwoDCodeText() {#getTwoDCodeText--}
```
public String getTwoDCodeText()
```


GS1 Composite の 2D バーコード値を取得します

値: 2D バーコード値

**Returns:**
java.lang.String
### getTwoDType() {#getTwoDType--}
```
public SingleDecodeType getTwoDType()
```


GS1 Composite の 2D バーコードタイプを取得します

値: 2D バーコードタイプ

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32ビット符号付き整数のハッシュコード。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


すべてのパラメーターがデフォルト値のみであるかテストします

値: すべてのパラメーターがデフォルト値のみの場合 **true** を返し、そうでない場合は **false** を返します。

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




### toString() {#toString--}
```
public String toString()
```


この  GS1CompositeBarExtendedParameters の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この  GS1CompositeBarExtendedParameters を表す文字列です。
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

