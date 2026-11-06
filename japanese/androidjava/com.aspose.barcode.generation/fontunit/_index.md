---
title: "FontUnit"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "テキストのフォントフェイスサイズやスタイル属性を含む特定のフォーマットを定義します。サイズは Unit 値プロパティで指定されます。"
type: docs
weight: 43
url: /ja/androidjava/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

テキストの特定のフォーマットを定義し、フォントファミリー、サイズ、スタイル属性を含み、サイズは Unit 値プロパティで指定します。

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontUnit(FontUnit source)](#FontUnit-com.aspose.barcode.generation.FontUnit-) |  |
| [FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi)](#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-) |  |
| [FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style)](#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-int-) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | この Font のフォント名を取得します。 |
| [getSize()](#getSize--) | この FontUnit のサイズを Unit 値で取得します。 |
| [getStyle()](#getStyle--) | この FontUnit のスタイル情報を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(Typeface value)](#setFamilyName-android.graphics.Typeface-) | このフォントのフェイス名を設定します。 |
| [setStyle(int value)](#setStyle-int-) | この FontUnit のスタイル情報を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontUnit(FontUnit source) {#FontUnit-com.aspose.barcode.generation.FontUnit-}
```
public FontUnit(FontUnit source)
```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi) {#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-}
```
public FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi)
```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| familyName | android.graphics.Typeface |  |
| sizeValue | float |  |
| graphicsUnit | [GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit) |  |
| dpi | float |  |

### FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style) {#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-int-}
```
public FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style)
```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| familyName | android.graphics.Typeface |  |
| sizeValue | float |  |
| graphicsUnit | [GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit) |  |
| dpi | float |  |
| style | int |  |

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
### getFamilyName() {#getFamilyName--}
```
public Typeface getFamilyName()
```


この Font のフォント名を取得します。

**Returns:**
android.graphics.Typeface
### getSize() {#getSize--}
```
public Unit getSize()
```


この FontUnit のサイズを Unit 値で取得します。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStyle() {#getStyle--}
```
public int getStyle()
```


この FontUnit のスタイル情報を取得します。

**Returns:**
int
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




### setFamilyName(Typeface value) {#setFamilyName-android.graphics.Typeface-}
```
public void setFamilyName(Typeface value)
```


このフォントのフェイス名を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | android.graphics.Typeface |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


この FontUnit のスタイル情報を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

