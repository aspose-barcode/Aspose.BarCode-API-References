---
title: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: 
type: docs
weight: 34
url: /ja/androidjava/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

DotCodeEncodeMode の ExtendedCodetext モード用の 2D DotCode バーコード向け拡張コードテキストジェネレータ

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | 拡張チャネル識別子付きのコードテキストを追加します |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | 拡張コードテキスト項目に FNC1 フォーマット識別子を追加します |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | 拡張コードテキスト項目に FNC3 リーダー初期化を追加します |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | 拡張コードテキスト項目に FNC3 シンボル区切りを追加します |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | プレーンコードテキストを拡張コードテキスト項目に追加します |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | 拡張コードテキスト項目に構造化付加モードを追加します |
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
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
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

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


拡張コードテキスト項目に FNC1 フォーマット識別子を追加します

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


拡張コードテキスト項目に FNC3 リーダー初期化を追加します

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


拡張コードテキスト項目に FNC3 シンボル区切りを追加します

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


プレーンコードテキストを拡張コードテキスト項目に追加します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| コードテキスト | java.lang.String | 拡張コードテキスト項目として追加するUnicodeのコードテキスト |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


拡張コードテキスト項目に構造化付加モードを追加します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| barcodeId | int | バーコードの ID |
| barcodesCount | int | バーコードの数 |

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

