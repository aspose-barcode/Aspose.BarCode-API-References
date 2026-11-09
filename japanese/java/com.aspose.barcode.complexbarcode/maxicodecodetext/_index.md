---
title: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするための基底クラス。"
type: docs
weight: 25
url: /ja/java/com.aspose.barcode.complexbarcode/maxicodecodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class MaxiCodeCodetext implements IComplexCodetext
```

MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするための基底クラス。

このサンプルは、生の MaxiCode コードテキストを MaxiCodeCodetext インスタンスにデコードする方法を示しています。

```

 BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
 for (BarCodeResult result : reader.readBarCodes())
 {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMode(), result.getCodeText());
      System.out.println("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
      System.out.println("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
      System.out.println("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
 }
 
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MaxiCodeCodetext()](#MaxiCodeCodetext--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | バーコードのタイプを取得します。 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | コードテキストを構築します |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを取得します。 |
| [getEncodeMode()](#getEncodeMode--) | MaxiCode のエンコードモードを取得します。 |
| [getMode()](#getMode--) | MaxiCode モードを取得します。 |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 構築されたコードテキストからインスタンスを初期化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI エンコーディングを設定します。 |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode エンコードモードを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeCodetext() {#MaxiCodeCodetext--}
```
public MaxiCodeCodetext()
```


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
public abstract String getConstructedCodetext()
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
### getMode() {#getMode--}
```
public abstract MaxiCodeMode getMode()
```


MaxiCode モードを取得します。

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public abstract void initFromString(String constructedCodetext)
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

