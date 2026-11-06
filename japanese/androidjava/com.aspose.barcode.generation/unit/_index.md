---
title: "単位"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "ピクセル、インチなど、さまざまな単位でサイズ値を指定します。"
type: docs
weight: 67
url: /ja/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

サイズ値を異なる単位（ピクセル、インチなど）で指定します。

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスと、同じく Unit オブジェクトである必要がある指定されたオブジェクトが同じ値かどうかを判断します。 |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 文書単位でサイズ値を取得します。 |
| [getInches()](#getInches--) | インチ単位でサイズ値を取得します。 |
| [getMillimeters()](#getMillimeters--) | ミリメートル単位でサイズ値を取得します。 |
| [getPixels()](#getPixels--) | ピクセル単位でサイズ値を取得します。 |
| [getPoint()](#getPoint--) | ポイント単位でサイズ値を取得します。 |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | このオブジェクトのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | 文書単位でサイズ値を設定します。 |
| [setInches(float value)](#setInches-float-) | インチ単位でサイズ値を設定します。 |
| [setMillimeters(float value)](#setMillimeters-float-) | ミリメートル単位でサイズ値を設定します。 |
| [setPixels(float value)](#setPixels-float-) | ピクセル単位でサイズ値を設定します。 |
| [setPoint(float value)](#setPoint-float-) | ポイント単位でサイズ値を設定します。 |
| [toString()](#toString--) | この  Unit  の人が読める文字列表現を返します。 |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスと、同じく Unit オブジェクトである必要がある指定されたオブジェクトが同じ値かどうかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための  Unit  。 |

**Returns:**
boolean - obj が  Unit  であり、その値がこのインスタンスと同じ場合は true、そうでなければ false。obj が null の場合、メソッドは false を返します。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


文書単位でサイズ値を取得します。

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


インチ単位でサイズ値を取得します。

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


ミリメートル単位でサイズ値を取得します。

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


ピクセル単位でサイズ値を取得します。

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


ポイント単位でサイズ値を取得します。

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


このオブジェクトのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


文書単位でサイズ値を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


インチ単位でサイズ値を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


ミリメートル単位でサイズ値を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


ピクセル単位でサイズ値を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


ポイント単位でサイズ値を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### toString() {#toString--}
```
public String toString()
```


この  Unit  の人が読める文字列表現を返します。

**Returns:**
java.lang.String - この  Unit  を表す文字列。
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dpi | float |  |

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

