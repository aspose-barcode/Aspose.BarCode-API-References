---
title: "QREncodeMode"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "QR バーコードのエンコーディングモード。"
type: docs
weight: 102
url: /ja/androidjava/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

QR バーコードのエンコーディングモード。これらのサンプルは、拡張データ形式で QR バーコードをエンコードおよび保存する方法を示しています。

```
{@code
 //This sample shows how to use ECI encoding and save a BarCode image.

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText("12345TEXT");
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECI_ENCODING);
 generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
 generator.save("test.png");

 //This sample shows how to use FNC1 first position in Extended Mode.
 Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes.
 It is better to use QrExtCodetextBuilder for extended codetext generation.
 Use Display2DText property to set visible text by removing managing characters.
 Encoding Principles:
 All symbols "\" must be doubled "\\" in the codetext.
 FNC1 in first position is set in codetext as "<FNC1>".
 FNC1 in second position is set in codetext as "<FNC1(value)>". The value must be a single character from a-z or A-Z, or a two-digit number from 00 to 99.
 Group Separator for FNC1 modes is set as 0x1D character ''.
 If you need to insert "<FNC1>" string into barcode write it as "<\FNC1>".
 ECI identifiers are set as single slash and six digits identifier, for example "\000026" for UTF8 ECI identifier.
 The default ECI mode is ISO/IEC 8859-1 ECI identifier "\000003". It does not need to be encoded at the beginning of the codetext.
 To switch from another ECI mode to the default ECI mode, use "\000003".
 All unicode characters after ECI identifier are automatically encoded into correct character codeset.
 QR compaction mode selectors are set as single slash and mode name: "\auto", "\num", "\alnum", "\byte", "\kanji".
 "\auto" sets automatic compaction mode, "\num" sets Numeric mode, "\alnum" sets AlphaNumeric mode, "\byte" sets Bytes mode, and "\kanji" sets Kanji mode.
 The default compaction mode is "\auto".
 Compaction mode selectors define the encoding mode for the following data until the next compaction mode selector or ECI identifier is found.
 If the data cannot be encoded in the selected compaction mode, an ArgumentException is thrown.
 This mode is not supported by MicroQR barcodes.

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.GetExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.Extended);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.png");

 //This sample shows how to use FNC1 second position in Extended Mode.
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.GetExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.Extended);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.png");

 //This sample shows how to use multi ECI mode in Extended Mode.
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
 textBuilder.addPlainCodetext"t\e\\st");
 textBuilder.addAlphaNumericCodetext("ASPOSE2001");
 textBuilder.addNumericCodetext(@"20012026");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.getExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text";
 generator.save("test.png");
```
## フィールド

| フィールド | 説明 |
| --- | --- |
| [AUTO](#AUTO) | Auto モードでは、CodeText が最大のデータ圧縮でエンコードされます。 |
| [BINARY](#BINARY) | Binary モードでは、CodeText が最大のデータ圧縮でエンコードされます。 |
| [ECI](#ECI) | ECI モードでは、全メッセージが指定された ECIEncoding エンコーディングで再エンコードされ、ECI 識別子が挿入されます。 |
| [EXTENDED](#EXTENDED) | FNC1 の先頭位置、FNC1 の第2位置、マルチ ECI モードをサポートする拡張チャンネルモード。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final QREncodeMode AUTO
```


Auto モードでは、CodeText が最大のデータ圧縮でエンコードされます。Unicode 文字は可能であれば漢字モードでエンコードされ、そうでなければ指定された ECIEncoding エンコーディングで再エンコードされ、ECI 識別子が挿入されます。選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


Binaryモードでは、CodeTextは最大限のデータ圧縮でエンコードされます。Unicode文字が見つかった場合、例外がスローされます。

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


ECI モードでは、メッセージ全体が指定された ECIEncoding エンコーディングで再エンコードされ、ECI 識別子が挿入されます。選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。なお、古い（2006 年以前の）スキャナーの中にはこのモードをサポートしないものがあります。このモードは MicroQR バーコードではサポートされていません。

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


FNC1 の先頭位置、FNC1 の第2位置、マルチ ECI モードをサポートする拡張チャンネルモードです。拡張コードテキストの生成には QrExtCodetextBuilder の使用が推奨されます。Display2DText プロパティを使用して、管理文字を除去し可視テキストを設定します。エンコーディング原則: コードテキスト内では、すべての記号 "\\" を "\\\\" に二重にする必要があります。先頭位置の FNC1 はコードテキストで "<FNC1>" と設定されます。第2位置の FNC1 はコードテキストで "<FNC1(value)>" と設定されます。value は a‑z または A‑Z の単一文字、または 00 から 99 の二桁数字でなければなりません。FNC1 モードのグループセパレータは 0x1D の文字 '\u001d' として設定されます。バーコードに "<FNC1>" 文字列を挿入する必要がある場合は "<\\FNC1>" と記述します。ECI 識別子はスラッシュ1つと6桁の識別子で設定され、例として UTF8 ECI 識別子は "\\000026" です。デフォルトの ECI モードは ISO/IEC 8859-1 の ECI 識別子 "\\000003" です。コードテキストの先頭でエンコードする必要はありません。別の ECI モードからデフォルト ECI モードに切り替えるには "\\000003" を使用します。ECI 識別子の後のすべての Unicode 文字は自動的に正しい文字コードセットにエンコードされます。QR 圧縮モードセレクタはスラッシュ1つとモード名で設定されます: "\\auto", "\\num", "\\alnum", "\\byte", "\\kanji". "\\auto" は自動圧縮モード、"\\num" は数値モード、"\\alnum" は英数字モード、"\\byte" はバイトモード、"\\kanji" は漢字モードを設定します。デフォルトの圧縮モードは "\\auto" です。圧縮モードセレクタは、次の圧縮モードセレクタまたは ECI 識別子が見つかるまで、以下のデータのエンコーディングモードを定義します。選択された圧縮モードでデータをエンコードできない場合、ArgumentException がスローされます。このモードは MicroQR バーコードではサポートされていません。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QREncodeMode fromValue(int value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static QREncodeMode valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### values() {#values--}
```
public static QREncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.QREncodeMode[]
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

