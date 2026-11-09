---
title: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "認識された DataMatrix バーコードの特別なデータを格納します"
type: docs
weight: 29
url: /ja/java/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

認識された DataMatrix バーコードの特別なデータを格納します

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming));
>  }
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された DataMatrixExtendedParameters の値と等しいかどうかを示す値を返します |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | DataMatrix構造付加モードバーコードのIDを取得します |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | DataMatrix の構造化付加モードバーコードの数を取得します。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | DataMatrix構造付加モードバーコードのIDを取得します |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | すべてのパラメーターがデフォルト値のみであるかテストします |
| [isReaderProgramming()](#isReaderProgramming--) | コードが、バーコードリーダーの初期化または再プログラミングの指示として、以下のデータを解釈するようリーダーに指示するために使用されるかどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この DataMatrixExtendedParameters の人間が読みやすい文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された DataMatrixExtendedParameters の値と等しいかどうかを示す値を返します

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
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


DataMatrix の構造化付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は -1 です。

値: DataMatrix の構造化付加モードバーコードの ID。

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


DataMatrix の構造化付加モードバーコードの数を取得します。デフォルト値は -1 です。カウントは 1 から 35 の範囲である必要があります。

値: DataMatrix の構造化付加モードバーコードの数。

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


DataMatrix の構造化付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は -1 です。

値: DataMatrix の構造化付加モードバーコードの ID。

**Returns:**
int
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
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


コードが、バーコードリーダーの初期化または再プログラミングの指示として、以下のデータを解釈させるために使用されるかどうかを示します。デフォルト値は false です。

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


この DataMatrixExtendedParameters の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この DataMatrixExtendedParameters を表す文字列です。
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

