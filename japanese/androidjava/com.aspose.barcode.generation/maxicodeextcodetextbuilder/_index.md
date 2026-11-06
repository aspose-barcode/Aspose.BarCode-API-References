---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "MaxiCode バーコードの ExtendedCodetext モード用の拡張コードテキストジェネレータで、BarcodeGenerator の TwoDDisplayText プロパティを使用して、表示テキストを設定し、管理文字を除去します。"
type: docs
weight: 54
url: /ja/androidjava/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

MaxiCode バーコードの ExtendedCodetext モード（MaxiCodeEncodeMode 用）向けの拡張コードテキストジェネレータです。BarcodeGenerator の TwoDDisplayText プロパティを使用して、表示テキストを設定し、管理文字を除去します。このサンプルは Extended モードで MaxiCodeExtCodetextBuilder を使用する方法を示しています。

```
//create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | 拡張チャネル識別子付きのコードテキストを追加します |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | プレーンコードテキストを拡張コードテキスト項目に追加します |
| [clear()](#clear--) | 拡張コードテキスト項目をクリアします |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 拡張コードテキストリストから拡張コードテキストを生成します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeExtCodetextBuilder() {#MaxiCodeExtCodetextBuilder--}
```
public MaxiCodeExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


拡張チャネル識別子付きのコードテキストを追加します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ECIEncoding | int | 拡張チャネル識別子 |
| コードテキスト | java.lang.String | 拡張チャネル識別子付きの拡張コードテキスト項目として追加するUnicodeのコードテキスト |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


プレーンコードテキストを拡張コードテキスト項目に追加します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| コードテキスト | java.lang.String | 拡張コードテキスト項目として追加するUnicodeのコードテキスト |

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
public String getExtendedCodetext()
```


拡張コードテキストリストから拡張コードテキストを生成します。

**Returns:**
java.lang.String - 拡張コードテキスト（文字列）
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

