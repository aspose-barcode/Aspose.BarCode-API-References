---
title: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "モード4、5、6用の MaxiCode コードテキストをエンコードおよびデコードするクラスです。"
type: docs
weight: 29
url: /ja/java/com.aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public class MaxiCodeStandardCodetext extends MaxiCodeCodetext
```

モード 4、5、6 用の MaxiCode コードテキストをエンコードおよびデコードするクラス。

```
//Mode 4
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 5
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_5);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 6
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_6);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MaxiCodeStandardCodetext()](#MaxiCodeStandardCodetext--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された MaxiCodeStandardCodetext の値と等しいかどうかを示す値を返します。 |
| [getBarcodeType()](#getBarcodeType--) | バーコードのタイプを取得します。 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | コードテキストを構築します |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを取得します。 |
| [getEncodeMode()](#getEncodeMode--) | MaxiCode のエンコードモードを取得します。 |
| [getMessage()](#getMessage--) | メッセージを取得します。 |
| [getMode()](#getMode--) | MaxiCode モードを取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 構築されたコードテキストからインスタンスを初期化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI エンコーディングを設定します。 |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode エンコードモードを設定します。 |
| [setMessage(String value)](#setMessage-java.lang.String-) | メッセージを設定します。 |
| [setMode(MaxiCodeMode mode)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | MaxiCode モードを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStandardCodetext() {#MaxiCodeStandardCodetext--}
```
public MaxiCodeStandardCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された MaxiCodeStandardCodetext の値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための MaxiCodeStandardCodetext の値。 |

**Returns:**
boolean - obj がこのインスタンスと同じ値を持つ場合は true、そうでない場合は **false**。
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


バーコードのタイプを取得します。

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


コードテキストを構築します

**Returns:**
java.lang.String - 構築されたコードテキスト
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI エンコーディングを取得します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1

**Returns:**
int - ECI エンコーディング。
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


MaxiCode エンコードモードを取得します。デフォルト値: Auto。

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMessage() {#getMessage--}
```
public String getMessage()
```


メッセージを取得します。

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public MaxiCodeMode getMode()
```


MaxiCode モードを取得します。

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


構築されたコードテキストからインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 構築されたコードテキスト。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI エンコーディングを設定します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | ECI エンコーディング。 |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode エンコードモードを設定します。デフォルト値: Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCode エンコードモード。 |

### setMessage(String value) {#setMessage-java.lang.String-}
```
public void setMessage(String value)
```


メッセージを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMode(MaxiCodeMode mode) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public void setMode(MaxiCodeMode mode)
```


MaxiCode モードを設定します。標準コードテキストはモード4、5、6でのみ使用できます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mode | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) |  |

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

