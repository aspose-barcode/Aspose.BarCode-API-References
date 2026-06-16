---
title: Pdf417Parameters
second_title: Aspose.BarCode for Android via Java API Reference
description: PDF417 パラメータ。
type: docs
weight: 60
url: /ja/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417 パラメータ。PDF417、MacroPDF417、MicroPDF417 および GS1MicroPdf417 のパラメータを含みます。MacroPDF417 には 2 つのフィールド、Pdf417MacroFileID と Pdf417MacroSegmentID が必要です。他のすべてのフィールドはオプションです。構造付加モード（MacroPDF417 モードと同じ）での MicroPDF417 には、Pdf417MacroFileID と Pdf417MacroSegmentID の 2 つのフィールドが必要です。他のすべてのフィールドはオプションです。

これらのサンプルは、GS1MicroPdf417 で UCC/EAN-128 の非リンクモードをエンコードする方法を示しています。

```

 [C#]
 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率。 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 列数。 |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getEncodeMode()](#getEncodeMode--) | Pdf417 エンコードモードを識別します。 |
| [getErrorLevel()](#getErrorLevel--) | BarCode のエラ訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを取得します。level0 はエラ訂正情報がなく、level8 は最高のエラ訂正であり、画像が大きくなります。 |
| [getMacroCharacters()](#getMacroCharacters--) | マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを取得するために使用されます。 |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 バーコードの受取人名（オプションフィールド）。 |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 バーコードのチェックサム（オプションフィールド）。 |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | MacroPdf417 バーコードのファイル ID（必須フィールド）。 |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 バーコードのファイル名（オプション フィールド）。 |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 ファイルサイズ（オプション フィールド）。 |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | MacroPdf417 バーコードのセグメント ID（必須フィールド）、0 から始まり MacroSegmentsCount - 1 までです。 |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | MacroPdf417 バーコードのセグメント数（オプション フィールド）。 |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 バーコードの送信者名（オプション フィールド）。 |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | エンコーダーにセグメントへ Macro PDF417 ターミネータ (コードワード 922) を追加するかどうかを指示するために使用されます。 |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 バーコードのタイムスタンプ（オプション フィールド）。 |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Pdf417 のシンボルタイプ（BarCode のコンパクションモード）。 |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | Pdf417 エンコードモードを識別します。 |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | BarCode のエラ訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを取得します。level0 はエラ訂正情報がなく、level8 は最高のエラ訂正であり、画像が大きくなります。 |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | MacroPdf417 バーコードの受取人名（オプションフィールド）。 |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | MacroPdf417 バーコードのチェックサム（オプションフィールド）。 |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | MacroPdf417 バーコードのファイル ID（必須フィールド）。 |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | MacroPdf417 バーコードのファイル名（オプション フィールド）。 |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | MacroPdf417 ファイルサイズ（オプション フィールド）。 |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | MacroPdf417 バーコードのセグメント ID（必須フィールド）、0 から始まり MacroSegmentsCount - 1 までです。 |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | MacroPdf417 バーコードのセグメント数（オプション フィールド）。 |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | MacroPdf417 バーコードの送信者名（オプション フィールド）。 |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | エンコーダーにセグメントへ Macro PDF417 ターミネータ (コードワード 922) を追加するかどうかを指示するために使用されます。 |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | MacroPdf417 バーコードのタイムスタンプ（オプション フィールド）。 |
| [getPdf417Truncate()](#getPdf417Truncate--) | Pdf417 のシンボルタイプ（BarCode）が省略されているか（スペース削減のため）。 |
| [getRows()](#getRows--) | 行数。 |
| [getTruncate()](#getTruncate--) | Pdf417 のシンボルタイプ（BarCode）が省略されているか（スペース削減のため）。 |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | MicroPdf417 と併用でき、Code 128 エミュレーションモードをエンコードします。FNC1 を第2位置でエンコードできるモード 908 と 909、さらに 910 と 911 もエンコードでき、これらは認識された MicroPdf417 が Code 128 として解釈できることを示します。 |
| [isLinked()](#isLinked--) | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 の「Linked」UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボルでは、EAN.UCC 以外の関連リニアコンポーネントへの 918 リンケージフラグをエンコードします。 |
| [isReaderInitialization()](#isReaderInitialization--) | シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率。 |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | MicroPdf417 と併用でき、Code 128 エミュレーションモードをエンコードします。FNC1 を第2位置でエンコードできるモード 908 と 909、さらに 910 と 911 もエンコードでき、これらは認識された MicroPdf417 が Code 128 として解釈できることを示します。 |
| [setColumns(int value)](#setColumns-int-) | 列数。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Pdf417 エンコードモードを識別します。 |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Pdf417 のシンボルタイプのエラ訂正レベルを level0 から level8 の範囲で設定します。level0 はエラ訂正情報がないことを意味し、level8 は最高のエラ訂正で、画像が大きくなることを意味します。 |
| [setLinked(boolean value)](#setLinked-boolean-) | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 の「Linked」UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボルでは、EAN.UCC 以外の関連リニアコンポーネントへの 918 リンケージフラグをエンコードします。 |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを取得するために使用されます。 |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 バーコードの受取人名（オプションフィールド）。 |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 バーコードのチェックサム（オプションフィールド）。 |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | MacroPdf417 バーコードのファイル ID（必須フィールド）。 |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 バーコードのファイル名（オプション フィールド）。 |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 ファイルサイズ（オプション フィールド）。 |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | MacroPdf417 バーコードのセグメント ID（必須フィールド）、0 から始まり MacroSegmentsCount - 1 までです。 |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | MacroPdf417 バーコードのセグメント数（オプション フィールド）。 |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 バーコードの送信者名（オプション フィールド）。 |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | エンコーダーにセグメントへ Macro PDF417 ターミネータ (コードワード 922) を追加するかどうかを指示するために使用されます。 |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 バーコードのタイムスタンプ（オプション フィールド）。 |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Pdf417 のシンボルタイプ（BarCode のコンパクションモード）。 |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setPdf417EncodeMode(Pdf417EncodeMode value)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Pdf417 エンコードモードを識別します。 |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Pdf417 のシンボルタイプのエラ訂正レベルを level0 から level8 の範囲で設定します。level0 はエラ訂正情報がないことを意味し、level8 は最高のエラ訂正で、画像が大きくなることを意味します。 |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | MacroPdf417 バーコードの受取人名（オプションフィールド）。 |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | MacroPdf417 バーコードのチェックサム（オプションフィールド）。 |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | MacroPdf417 バーコードのファイル ID（必須フィールド）。 |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | MacroPdf417 バーコードのファイル名（オプション フィールド）。 |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | MacroPdf417 ファイルサイズ（オプション フィールド）。 |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | MacroPdf417 バーコードのセグメント ID（必須フィールド）、0 から始まり MacroSegmentsCount - 1 までです。 |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | MacroPdf417 バーコードのセグメント数（オプション フィールド）。 |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | MacroPdf417 バーコードの送信者名（オプション フィールド）。 |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | エンコーダーにセグメントへ Macro PDF417 ターミネータ (コードワード 922) を追加するかどうかを指示するために使用されます。 |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | MacroPdf417 バーコードのタイムスタンプ（オプション フィールド）。 |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | Pdf417 のシンボルタイプ（BarCode）が省略されているか（スペース削減のため）。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。 |
| [setRows(int value)](#setRows-int-) | 行数。 |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Pdf417 のシンボルタイプ（BarCode）が省略されているか（スペース削減のため）。 |
| [toString()](#toString--) | この [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) の人間が読める文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D バーコードモジュールの高さ/幅比率。

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


列数。

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


拡張チャンネル解釈識別子です。シンボル内のデータエンコードに使用された参照の詳細をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装は、すべての既知の文字セットエンコーディングを含みます。

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Pdf417 エンコードモードを識別します。デフォルト値: Auto。

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


BarCode のエラ訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを取得します。level0 はエラ訂正情報がなく、level8 は最高のエラ訂正であり、画像が大きくなります。

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを得るために使用されます。MicroPdf417 と併用でき、916 と 917 の MicroPdf417 モードをエンコードします。デフォルト値: MacroCharacters.None。

これらのサンプルは、MicroPdf417 でマクロ文字をエンコードする方法を示しています。

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 バーコードの受取人名（オプション フィールド）。MicroPDF417 バーコードの受取人名（Structured Append モード用のオプション フィールド）

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 バーコードのチェックサム（オプション フィールド）。MicroPDF417 バーコードのチェックサム（Structured Append モード用のオプション フィールド）チェックサムフィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


拡張チャンネル解釈識別子です。Macro PDF417 のテキストフィールドに適用されます。

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


MacroPdf417 バーコードのファイル ID（必須フィールド）。MicroPDF417 バーコードのファイル ID（Structured Append モード用の必須フィールド）

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 バーコードのファイル名（オプション フィールド）。MicroPDF417 バーコードのファイル名（Structured Append モード用のオプション フィールド）

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 ファイルサイズ（オプション フィールド）。MicroPDF417 ファイルサイズ（Structured Append モード用のオプション フィールド）ファイルサイズフィールドは、ソース全体のバイト数を示します。

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


MacroPdf417 バーコードのセグメント ID（必須フィールド）、0 から始まり MacroSegmentsCount - 1 までです。MicroPDF417 バーコードのセグメント ID（Structured Append モード用の必須フィールド）

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


MacroPdf417 バーコードのセグメント数（オプション フィールド）。MicroPDF417 バーコードのセグメント数（Structured Append モード用のオプション フィールド）

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 バーコードの送信者名（オプション フィールド）。MicroPDF417 バーコードの送信者名（Structured Append モード用のオプション フィールド）。

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


エンコーダに、セグメントに Macro PDF417 Terminator（コードワード 922）を追加するかどうかを指示するために使用されます。Macro PDF417 にのみ適用されます。

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。MicroPDF417 バーコードのタイムスタンプ（Structured Append モード用のオプションフィールド）

**Returns:**
java.time.LocalDateTime
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public final Pdf417CompactionMode getPdf417CompactionMode()
```


Pdf417 シンボルタイプのバーコードのコンパクションモード。デフォルト値: Pdf417CompactionMode.Auto.

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public final int getPdf417ECIEncoding()
```


拡張チャンネル解釈識別子です。シンボル内のデータエンコードに使用された参照の詳細をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装は、すべての既知の文字セットエンコーディングを含みます。

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public final Pdf417EncodeMode getPdf417EncodeMode()
```


Pdf417 エンコードモードを識別します。デフォルト値: Auto。

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public final Pdf417ErrorLevel getPdf417ErrorLevel()
```


BarCode のエラ訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを取得します。level0 はエラ訂正情報がなく、level8 は最高のエラ訂正であり、画像が大きくなります。

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public final String getPdf417MacroAddressee()
```


MacroPdf417 バーコードの受取人名（オプション フィールド）。MicroPDF417 バーコードの受取人名（Structured Append モード用のオプション フィールド）

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public final int getPdf417MacroChecksum()
```


MacroPdf417 バーコードのチェックサム（オプション フィールド）。MicroPDF417 バーコードのチェックサム（Structured Append モード用のオプション フィールド）チェックサムフィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public final int getPdf417MacroECIEncoding()
```


拡張チャンネル解釈識別子です。Macro PDF417 のテキストフィールドに適用されます。

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public final int getPdf417MacroFileID()
```


MacroPdf417 バーコードのファイル ID（必須フィールド）。MicroPDF417 バーコードのファイル ID（Structured Append モード用の必須フィールド）

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public final String getPdf417MacroFileName()
```


MacroPdf417 バーコードのファイル名（オプション フィールド）。MicroPDF417 バーコードのファイル名（Structured Append モード用のオプション フィールド）

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public final int getPdf417MacroFileSize()
```


MacroPdf417 ファイルサイズ（オプション フィールド）。MicroPDF417 ファイルサイズ（Structured Append モード用のオプション フィールド）ファイルサイズフィールドは、ソース全体のバイト数を示します。

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public final int getPdf417MacroSegmentID()
```


MacroPdf417 バーコードのセグメント ID（必須フィールド）、0 から始まり MacroSegmentsCount - 1 までです。MicroPDF417 バーコードのセグメント ID（Structured Append モード用の必須フィールド）

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public final int getPdf417MacroSegmentsCount()
```


MacroPdf417 バーコードのセグメント数（オプション フィールド）。MicroPDF417 バーコードのセグメント数（Structured Append モード用のオプション フィールド）

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public final String getPdf417MacroSender()
```


MacroPdf417 バーコードの送信者名（オプション フィールド）。MicroPDF417 バーコードの送信者名（Structured Append モード用のオプション フィールド）。

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public final Pdf417MacroTerminator getPdf417MacroTerminator()
```


エンコーダに、セグメントに Macro PDF417 Terminator（コードワード 922）を追加するかどうかを指示するために使用されます。Macro PDF417 にのみ適用されます。

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public final LocalDateTime getPdf417MacroTimeStamp()
```


MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。MicroPDF417 バーコードのタイムスタンプ（Structured Append モード用のオプションフィールド）

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public final boolean getPdf417Truncate()
```


Pdf417 シンボルタイプのバーコードが省略されているか（スペース削減のため）。CompactPDF417 とも呼ばれます。このモードでは右側の行インジケータと右側のストップパターンが削除されます。

**Returns:**
boolean
### getRows() {#getRows--}
```
public final int getRows()
```


行数。

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Pdf417 シンボルタイプのバーコードが省略されているか（スペース削減のため）。CompactPDF417 とも呼ばれます。このモードでは右側の行インジケータと右側のストップパターンが削除されます。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


MicroPdf417 と併用でき、Code 128 エミュレーションモードをエンコードします。FNC1 を第2位置でエンコードできるモード 908 と 909、さらに 910 と 911 もエンコードでき、これらは認識された MicroPdf417 が Code 128 として解釈できることを示します。

これらのサンプルは、FNC1 を2番目の位置に入れた場合と入れない場合の Code 128 エミュレーションモードのエンコード方法を示しています。この方法により MicroPdf417 を Code 128 バーコードとしてデコードできます。

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 の「Linked」UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボルでは、EAN.UCC 以外の関連リニアコンポーネントへの 918 リンケージフラグをエンコードします。

これらのサンプルは、GS1MicroPdf417 の \"Linked\" UCC/EAN-128 モードと、MicroPdf417 および Pdf417 バーコードの Linkage Flag (918) のエンコード方法を示しています。

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。

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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D バーコードモジュールの高さ/幅比率。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


MicroPdf417 と併用でき、Code 128 エミュレーションモードをエンコードします。FNC1 を第2位置でエンコードできるモード 908 と 909、さらに 910 と 911 もエンコードでき、これらは認識された MicroPdf417 が Code 128 として解釈できることを示します。

これらのサンプルは、FNC1 を2番目の位置に入れた場合と入れない場合の Code 128 エミュレーションモードのエンコード方法を示しています。この方法により MicroPdf417 を Code 128 バーコードとしてデコードできます。

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


列数。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


拡張チャンネル解釈識別子です。シンボル内のデータエンコードに使用された参照の詳細をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装は、すべての既知の文字セットエンコーディングを含みます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Pdf417 エンコードモードを識別します。デフォルト値: Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Pdf417 のシンボルタイプのエラ訂正レベルを level0 から level8 の範囲で設定します。level0 はエラ訂正情報がないことを意味し、level8 は最高のエラ訂正で、画像が大きくなることを意味します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417 シンボルタイプのバーコードのエラー訂正レベルは level0 から level8 まであり、level0 はエラー訂正情報がなく、level8 は最高のエラー訂正であり、より大きな画像になります。 |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 の「Linked」UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボルでは、EAN.UCC 以外の関連リニアコンポーネントへの 918 リンケージフラグをエンコードします。

これらのサンプルは、GS1MicroPdf417 の \"Linked\" UCC/EAN-128 モードと、MicroPdf417 および Pdf417 バーコードの Linkage Flag (918) のエンコード方法を示しています。

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを得るために使用されます。MicroPdf417 と併用でき、916 と 917 の MicroPdf417 モードをエンコードします。デフォルト値: MacroCharacters.None。

これらのサンプルは、MicroPdf417 でマクロ文字をエンコードする方法を示しています。

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 バーコードの受取人名（オプション フィールド）。MicroPDF417 バーコードの受取人名（Structured Append モード用のオプション フィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 バーコードのチェックサム（オプション フィールド）。MicroPDF417 バーコードのチェックサム（Structured Append モード用のオプション フィールド）チェックサムフィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


拡張チャンネル解釈識別子です。Macro PDF417 のテキストフィールドに適用されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


MacroPdf417 バーコードのファイル ID（必須フィールド）。MicroPDF417 バーコードのファイル ID（Structured Append モード用の必須フィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 バーコードのファイル名（オプション フィールド）。MicroPDF417 バーコードのファイル名（Structured Append モード用のオプション フィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 ファイルサイズ（オプション フィールド）。MicroPDF417 ファイルサイズ（Structured Append モード用のオプション フィールド）ファイルサイズフィールドは、ソース全体のバイト数を示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


MacroPdf417 バーコードのセグメント ID（必須フィールド）、0 から始まり MacroSegmentsCount - 1 までです。MicroPDF417 バーコードのセグメント ID（Structured Append モード用の必須フィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


MacroPdf417 バーコードのセグメント数（オプション フィールド）。MicroPDF417 バーコードのセグメント数（Structured Append モード用のオプション フィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 バーコードの送信者名（オプション フィールド）。MicroPDF417 バーコードの送信者名（Structured Append モード用のオプション フィールド）。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


エンコーダに、セグメントに Macro PDF417 Terminator（コードワード 922）を追加するかどうかを指示するために使用されます。Macro PDF417 にのみ適用されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。MicroPDF417 バーコードのタイムスタンプ（Structured Append モード用のオプションフィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.time.LocalDateTime |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public final void setPdf417CompactionMode(Pdf417CompactionMode value)
```


Pdf417 シンボルタイプのバーコードのコンパクションモード。デフォルト値: Pdf417CompactionMode.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public final void setPdf417ECIEncoding(int value)
```


拡張チャンネル解釈識別子です。シンボル内のデータエンコードに使用された参照の詳細をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装は、すべての既知の文字セットエンコーディングを含みます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode value) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setPdf417EncodeMode(Pdf417EncodeMode value)
```


Pdf417 エンコードモードを識別します。デフォルト値: Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


Pdf417 のシンボルタイプのエラ訂正レベルを level0 から level8 の範囲で設定します。level0 はエラ訂正情報がないことを意味し、level8 は最高のエラ訂正で、画像が大きくなることを意味します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417 シンボルタイプのバーコードのエラー訂正レベルは level0 から level8 まであり、level0 はエラー訂正情報がなく、level8 は最高のエラー訂正であり、より大きな画像になります。 |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public final void setPdf417MacroAddressee(String value)
```


MacroPdf417 バーコードの受取人名（オプション フィールド）。MicroPDF417 バーコードの受取人名（Structured Append モード用のオプション フィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public final void setPdf417MacroChecksum(int value)
```


MacroPdf417 バーコードのチェックサム（オプション フィールド）。MicroPDF417 バーコードのチェックサム（Structured Append モード用のオプション フィールド）チェックサムフィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public final void setPdf417MacroECIEncoding(int value)
```


拡張チャンネル解釈識別子です。Macro PDF417 のテキストフィールドに適用されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public final void setPdf417MacroFileID(int value)
```


MacroPdf417 バーコードのファイル ID（必須フィールド）。MicroPDF417 バーコードのファイル ID（Structured Append モード用の必須フィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public final void setPdf417MacroFileName(String value)
```


MacroPdf417 バーコードのファイル名（オプション フィールド）。MicroPDF417 バーコードのファイル名（Structured Append モード用のオプション フィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public final void setPdf417MacroFileSize(int value)
```


MacroPdf417 ファイルサイズ（オプション フィールド）。MicroPDF417 ファイルサイズ（Structured Append モード用のオプション フィールド）ファイルサイズフィールドは、ソース全体のバイト数を示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public final void setPdf417MacroSegmentID(int value)
```


MacroPdf417 バーコードのセグメント ID（必須フィールド）、0 から始まり MacroSegmentsCount - 1 までです。MicroPDF417 バーコードのセグメント ID（Structured Append モード用の必須フィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public final void setPdf417MacroSegmentsCount(int value)
```


MacroPdf417 バーコードのセグメント数（オプション フィールド）。MicroPDF417 バーコードのセグメント数（Structured Append モード用のオプション フィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public final void setPdf417MacroSender(String value)
```


MacroPdf417 バーコードの送信者名（オプション フィールド）。MicroPDF417 バーコードの送信者名（Structured Append モード用のオプション フィールド）。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


エンコーダに、セグメントに Macro PDF417 Terminator（コードワード 922）を追加するかどうかを指示するために使用されます。Macro PDF417 にのみ適用されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public final void setPdf417MacroTimeStamp(LocalDateTime value)
```


MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。MicroPDF417 バーコードのタイムスタンプ（Structured Append モード用のオプションフィールド）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.time.LocalDateTime |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public final void setPdf417Truncate(boolean value)
```


Pdf417 シンボルタイプのバーコードが省略されているか（スペース削減のため）。CompactPDF417 とも呼ばれます。このモードでは右側の行インジケータと右側のストップパターンが削除されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


行数。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Pdf417 シンボルタイプのバーコードが省略されているか（スペース削減のため）。CompactPDF417 とも呼ばれます。このモードでは右側の行インジケータと右側のストップパターンが削除されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


この [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) を表す文字列です。
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

