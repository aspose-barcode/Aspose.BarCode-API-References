---
title: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "DataMatrix エンコーダのエンコーディングモードはデフォルトで Auto です。"
type: docs
weight: 81
url: /ja/java/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

DataMatrix エンコーダのエンコーディングモード（デフォルトは Auto）

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ANSIX12](#ANSIX12) | ANSI X12 エンコーディングを使用します。 |
| [ASCII](#ASCII) | 1 バイトあたり 1 つの英数字または 2 つの数字文字をエンコードします。 |
| [AUTO](#AUTO) | Auto モードでは、CodeText は最大のデータ圧縮でエンコードされます。 |
| [BASE_256](#BASE-256) | 8 ビット値をエンコードします。 |
| [BINARY](#BINARY) | Binary モードでは、CodeText は最大のデータ圧縮でエンコードされます。 |
| [C40](#C40) | C40 エンコーディングを使用します。 |
| [ECI](#ECI) | ECIモードでは、メッセージ全体がECIEncodingで指定されたエンコーディングで再エンコードされ、ECI識別子が挿入されます。 |
| [EDIFACT](#EDIFACT) | EDIFACTエンコーディングを使用します。 |
| [EXTENDED](#EXTENDED) | ExtendedCodetextモードでは、コードテキスト内でエンコーディング方式とECIエンコーディングを手動で切り替えることができます。 |
| [TEXT](#TEXT) | Textエンコーディングを使用します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


ANSI X12 エンコーディングを使用します。

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


1 バイトあたり 1 つの英数字または 2 つの数字文字をエンコードします。

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


Autoモードでは、CodeTextが最大限のデータ圧縮でエンコードされます。Unicode文字はECIEncodingで指定されたエンコーディングで再エンコードされ、ECI識別子が挿入されます。選択されたECIエンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


8 ビット値をエンコードします。

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


Binaryモードでは、CodeTextが最大限のデータ圧縮でエンコードされます。Unicode文字が見つかった場合、例外がスローされます。

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


C40エンコーディングを使用します。大文字英数字、小文字、特殊文字をエンコードします。

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


ECIモードでは、メッセージ全体がECIEncodingで指定されたエンコーディングで再エンコードされ、ECI識別子が挿入されます。選択されたECIエンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。なお、2006年以前の古いスキャナーはこのモードをサポートしていない可能性があります。

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


EDIFACTエンコーディングを使用します。1文字あたり6ビットを使用し、数字、大文字、さまざまな句読点をエンコードしますが、小文字はサポートされていません。

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


ExtendedCodetextモードでは、コードテキスト内でエンコーディング方式とECIエンコーディングを手動で切り替えることができます。拡張コードテキストの生成にはDataMatrixExtCodetextBuilderを使用する方が適しています。Display2DTextプロパティを使用して、表示テキストを設定し、管理文字を除去します。ECI識別子は単一スラッシュと6桁の識別子 "\\000026"（UTF8 ECI識別子）として設定されます。ECI識別子以降のすべてのUnicode文字は自動的に正しい文字コードセットにエンコードされます。エンコーディング方式は次の形式で設定します： "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text"。使用可能なエンコーディング方式は、EDIFACT、ANSIX12、ASCII、C40、Text、Autoです。テキスト内のすべてのバックスラッシュ（\\）は二重にする必要があります。

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Textエンコーディングを使用します。小文字英数字、大文字、特殊文字をエンコードします。

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
public static DataMatrixEncodeMode fromValue(int value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
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

