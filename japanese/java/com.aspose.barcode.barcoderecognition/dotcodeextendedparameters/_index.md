---
title: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "認識された DotCode バーコードの特別なデータを格納します"
type: docs
weight: 31
url: /ja/java/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

認識された DotCode バーコードの特別なデータを格納します

このサンプルは DotCode の生データを取得する方法を示しています

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");
 
 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) の値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | DotCode の構造化付加モードバーコードの ID を取得します。 |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | DotCode の構造化付加モードバーコードの数を取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | すべてのパラメーターがデフォルト値のみであるかテストします |
| [isReaderInitialization()](#isReaderInitialization--) | コードが、バーコードリーダーの初期化または再プログラミングの指示として、以下のデータを解釈するようリーダーに指示するために使用されるかどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) の人間が読める文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) の値と等しいかどうかを示す値を返します。

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
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


DotCode の構造化付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコードの数以下である必要があります。デフォルト値は -1 です。

値: DotCode の構造化付加モードバーコードの ID。

**Returns:**
int - DotCode の構造化付加モードバーコードの ID。
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


DotCode の構造化付加モードバーコードの数を取得します。デフォルト値は -1 です。カウントは 1 から 35 の範囲である必要があります。

値: DotCode 構造付加モードバーコードの数。

**Returns:**
int - DotCode 構造付加モードバーコードの数。
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
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
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


この [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) を表す文字列です。
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

