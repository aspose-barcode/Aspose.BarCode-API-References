---
title: "FontUnit"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "フォントのフェイスサイズやスタイル属性を含むテキストの特定の形式を定義します。サイズは Unit 値プロパティで指定します。"
type: docs
weight: 42
url: /ja/java/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

フォントファミリ、サイズ、スタイル属性を含むテキストの特定の形式を定義します（サイズは Unit 値プロパティで指定）。

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | この Font のフェイス名を取得します。 |
| [getSize()](#getSize--) | この FontUnit のサイズを Unit 値で取得します。 |
| [getStyle()](#getStyle--) | この FontUnit のスタイル情報を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | この Font のフェイス名を設定します。 |
| [setStyle(int value)](#setStyle-int-) | この FontUnit のスタイル情報を設定します。 |
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
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


この Font のフェイス名を取得します。

**Returns:**
java.lang.String
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




### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


この Font のフェイス名を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

