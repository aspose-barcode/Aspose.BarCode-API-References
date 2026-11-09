---
title: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API リファレンス"
description: 
type: docs
weight: 61
url: /ja/java/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

EncodeMode の ExtendedCodetext モード用 2D QR バーコードの拡張コードテキストジェネレータ

BarcodeGeneratorのTwoDDisplayTextプロパティを使用して、表示テキストを設定し、管理文字を除去します。

このサンプルは、Extended Mode で FNC1 の最初の位置を使用する方法を示しています。

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

このサンプルは、Extended Mode で FNC1 の2番目の位置を使用する方法を示しています。

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

このサンプルは、Extended Mode でマルチ ECI モードを使用する方法を示しています。

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.WIN_1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF_8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF_16_BE, "Power");
 textBuilder.addPlainCodetext("t\\e\\\\st");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.ALPHA_NUMERIC, "ASPOSE2001");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.NUMERIC, "20012026");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | 指定された QR コンパクションモードのコードテキストを拡張コードテキスト項目に追加します。 |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | 拡張チャンネル識別子付きのコードテキストを追加します |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | 最初の位置に FNC1 を設定します。 |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | 拡張コードテキスト項目にグループ区切り文字 (GS - '\\\\u001D') を追加します。 |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | 2番目の位置に FNC1 を設定します。 |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | プレーンなコードテキストを拡張コードテキスト項目に追加します |
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
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
```


### addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext) {#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-}
```
public final void addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)
```


指定された QR コンパクションモードのコードテキストを拡張コードテキスト項目に追加します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | コードテキスト用 QR コンパクションモード。 |
| コードテキスト | java.lang.String | 拡張コードテキスト項目として追加する Unicode のコードテキスト。 |

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

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


最初の位置に FNC1 を設定します。以前に別の FNC1 モードが設定されていた場合、置き換えられます。

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


拡張コードテキスト項目にグループ区切り文字 (GS - '\\\\u001D') を追加します。

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


2番目の位置に FNC1 を設定します。以前に別の FNC1 モードが設定されていた場合、置き換えられます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| コードテキスト | java.lang.String | 2番目の位置にある FNC1 の値。値は a-z または A-Z の単一文字、または 00 から 99 の2桁の数字でなければなりません。 |

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
public String getExtendedCodetext()
```


拡張コードテキストリストから拡張コードテキストを生成します。

**Returns:**
java.lang.String - 拡張コードテキストを文字列として
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

