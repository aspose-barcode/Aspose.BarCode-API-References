---
title: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: 
type: docs
weight: 32
url: /ja/androidjava/com.aspose.barcode.generation/datamatrixextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DataMatrixExtCodetextBuilder extends ExtCodetextBuilder
```

EncodeMode の ExtendedCodetext モード用の 2D DataMatrix バーコード向け拡張コードテキストジェネレータ

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.BYTES, "World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DataMatrixExtCodetextBuilder()](#DataMatrixExtCodetextBuilder--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)](#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | 定義されたエンコードモードでコードテキストを拡張コードテキスト項目に追加します |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | 拡張チャネル識別子付きのコードテキストを追加します |
| [addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)](#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | 定義されたエンコードモードで拡張チャネル識別子を使用してコードテキストを追加します |
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
### DataMatrixExtCodetextBuilder() {#DataMatrixExtCodetextBuilder--}
```
public DataMatrixExtCodetextBuilder()
```


### addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext) {#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)
```


定義されたエンコードモードでコードテキストを拡張コードテキスト項目に追加します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | エンコードモードの値 |
| コードテキスト | java.lang.String | 拡張コードテキスト項目として追加するUnicodeのコードテキスト |

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

### addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext) {#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)
```


定義されたエンコードモードで拡張チャネル識別子を使用してコードテキストを追加します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ECIEncoding | int | 拡張チャネル識別子 |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | エンコードモードの値 |
| コードテキスト | java.lang.String | 定義されたエンコードモードで拡張チャネル識別子を使用して拡張コードテキスト項目として追加するUnicodeのコードテキスト |

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

