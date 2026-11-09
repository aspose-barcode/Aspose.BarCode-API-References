---
title: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "認識されたバーコードの MacroPdf417 メタデータ情報を格納します"
type: docs
weight: 36
url: /ja/java/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

認識されたバーコードの MacroPdf417 メタデータ情報を格納します

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
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された Pdf417ExtendedParameters の値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Macro PDF417 の受取人名（オプション）。 |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Macro PDF417 のチェックサム（オプション）。 |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | バーコードのファイル ID を取得します。MacroPdf417 のみで利用可能です。 |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Macro PDF417 のファイル名（オプション）。 |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Macro PDF417 のファイルサイズ（オプション）。 |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | バーコードのセグメント ID を取得します。MacroPdf417 のみで利用可能です。 |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Macro PDF417 バーコードのセグメント数を取得します。 |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Macro PDF417 の送信者名（オプション）。 |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | セグメントが Macro PDF417 ファイルの最後のセグメントかどうかを示します。 |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Macro PDF417 のタイムスタンプ（オプション）。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isCode128Emulation()](#isCode128Emulation--) | 908、909、910、または 911 Code 128 エミュレーションコードワードでエンコードされた MicroPdf417 バーコードであることを示すフラグです。 |
| [isEmpty()](#isEmpty--) | すべてのパラメーターがデフォルト値のみであるかテストします |
| [isLinked()](#isLinked--) | バーコードが 1D バーコードにリンクされる必要があることを示すフラグです。 |
| [isReaderInitialization()](#isReaderInitialization--) | シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この Pdf417ExtendedParameters の人間が読みやすい文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された Pdf417ExtendedParameters の値と等しいかどうかを示す値を返します。

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
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Macro PDF417 の受取人名（オプション）。

**Returns:**
java.lang.String - 受取人名です。
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Macro PDF417 のチェックサム（オプション）。

**Returns:**
int - チェックサムです。
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


バーコードのファイル ID を取得します。MacroPdf417 のみで利用可能です。

値: MacroPdf417 のファイル ID です。

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Macro PDF417 のファイル名（オプション）。

**Returns:**
java.lang.String - ファイル名です。
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Macro PDF417 のファイルサイズ（オプション）。

**Returns:**
int - ファイルサイズです。
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


バーコードのセグメント ID を取得します。MacroPdf417 のみで利用可能です。

値: バーコードのセグメントIDです。

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


マクロpdf417バーコードセグメントの数を取得します。デフォルト値は-1です。

値: セグメント数です。

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
boolean - 終端。
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Macro PDF417 のタイムスタンプ（オプション）。

**Returns:**
java.time.LocalDateTime - タイムスタンプ。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32ビット符号付き整数のハッシュコード。
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


908、909、910、または 911 Code 128 エミュレーションコードワードでエンコードされた MicroPdf417 バーコードであることを示すフラグです。

**Returns:**
boolean - Code 128 エミュレーションフラグ
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


すべてのパラメーターがデフォルト値のみであるかテストします

値: すべてのパラメーターがデフォルト値のみの場合 **true** を返し、そうでない場合は **false** を返します。

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


バーコードが 1D バーコードにリンクされる必要があることを示すフラグです。

値: リンケージフラグ

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。

値: リーダー初期化フラグ

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


この Pdf417ExtendedParameters の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この Pdf417ExtendedParameters を表す文字列です。
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

