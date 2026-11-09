---
title: "ExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "拡張コードテキストモードの自動コードテキスト生成のためのヘルパークラス"
type: docs
weight: 38
url: /ja/java/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

拡張コードテキストモードの自動コードテキスト生成のためのヘルパークラス
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | 拡張チャンネル識別子付きのコードテキストを追加します |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | プレーンなコードテキストを拡張コードテキスト項目に追加します |
| [clear()](#clear--) | 拡張コードテキスト項目をクリアします |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 生成項目リストから拡張コードテキストを生成します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtCodetextBuilder() {#ExtCodetextBuilder--}
```
public ExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


拡張チャンネル識別子付きのコードテキストを追加します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ECIEncoding | int | 拡張チャンネル識別子 |
| コードテキスト | java.lang.String | 拡張チャンネル識別子付きの拡張コードテキスト項目として追加するUnicodeのコードテキスト |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


プレーンなコードテキストを拡張コードテキスト項目に追加します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| コードテキスト | java.lang.String | 拡張コードテキスト項目として追加するためのUnicodeのコードテキスト |

### clear() {#clear--}
```
public void clear()
```


拡張コードテキスト項目をクリアします

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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public abstract String getExtendedCodetext()
```


生成項目リストから拡張コードテキストを生成します

**Returns:**
java.lang.String - 拡張コードテキストの文字列を返します
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

