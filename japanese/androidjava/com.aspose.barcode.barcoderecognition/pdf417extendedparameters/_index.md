---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Stores a MacroPdf417 metadata information of recognized barcode
type: docs
weight: 40
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Stores a MacroPdf417 metadata information of recognized barcode

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された Pdf417ExtendedParameters の値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Macro PDF417 の受取人名（オプション）。 |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Macro PDF417 のチェックサム（オプション）。 |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | バーコードのファイル ID を取得します。MacroPdf417 のみで利用可能です。 |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Macro PDF417 のファイル名（オプション）。 |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Macro PDF417 のファイルサイズ（オプション）。 |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | バーコードのセグメント ID を取得します。MacroPdf417 のみで利用可能です。 |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | macro pdf417 バーコードのセグメント数を取得します。 |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Macro PDF417 の送信者名（オプション）。 |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | セグメントが Macro PDF417 ファイルの最後のセグメントかどうかを示します。 |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Macro PDF417 のタイムスタンプ（オプション）。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isCode128Emulation()](#isCode128Emulation--) | 908、909、910、または 911 の Code 128 エミュレーションコードワードでエンコードされた MicroPdf417 バーコードであることを示すフラグ。 |
| [isEmpty()](#isEmpty--) | すべてのパラメーターがデフォルト値のみであるかどうかをテストします。 |
| [isLinked()](#isLinked--) | バーコードを 1D バーコードにリンクする必要があることを示すフラグ。 |
| [isReaderInitialization()](#isReaderInitialization--) | シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この Pdf417ExtendedParameters の人間が読める文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された Pdf417ExtendedParameters の値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
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
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Macro PDF417 の受取人名（オプション）。

**Returns:**
java.lang.String - 受取人名。
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Macro PDF417 のチェックサム（オプション）。

**Returns:**
int - チェックサム。
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


バーコードのファイル ID を取得します。MacroPdf417 のみで利用可能です。

値: MacroPdf417 のファイル ID

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Macro PDF417 のファイル名（オプション）。

**Returns:**
java.lang.String - ファイル名。
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Macro PDF417 のファイルサイズ（オプション）。

**Returns:**
int - ファイルサイズ。
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


バーコードのセグメント ID を取得します。MacroPdf417 のみで利用可能です。

値: バーコードのセグメント ID。

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


macro pdf417 バーコードのセグメント数を取得します。デフォルト値は -1 です。

値: セグメント数。

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Macro PDF417 の送信者名（オプション）。

**Returns:**
java.lang.String - 送信者名
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


セグメントが Macro PDF417 ファイルの最後のセグメントかどうかを示します。

**Returns:**
boolean - ターミネータ。
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Macro PDF417 のタイムスタンプ（オプション）。

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


908、909、910、または 911 の Code 128 エミュレーションコードワードでエンコードされた MicroPdf417 バーコードであることを示すフラグ。

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


すべてのパラメーターがデフォルト値のみであるかどうかをテストします。

値: すべてのパラメーターがデフォルト値のみである場合 **true** を返し、そうでない場合は **false** を返します。

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


バーコードを 1D バーコードにリンクする必要があることを示すフラグ。

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。

Value: Reader initialization flag

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


この Pdf417ExtendedParameters の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

