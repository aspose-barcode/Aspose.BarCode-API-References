---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "PDF417 パラメータ。"
type: docs
weight: 58
url: /ja/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417 パラメータ。PDF417、MacroPDF417、MicroPDF417 および GS1MicroPdf417 のパラメータが含まれます。MacroPDF417 には 2 つのフィールドが必要です：Pdf417MacroFileID と Pdf417MacroSegmentID。その他のフィールドはすべてオプションです。Structured Append モード（MacroPDF417 モードと同じ）での MicroPDF417 には 2 つのフィールドが必要です：Pdf417MacroFileID と Pdf417MacroSegmentID。その他のフィールドはすべてオプションです。

これらのサンプルは、GS1MicroPdf417 で UCC/EAN-128 の非リンクモードをエンコードする方法を示しています。

```

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2Dバーコードモジュールの高さ/幅比率。 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 列数。 |
| [getECIEncoding()](#getECIEncoding--) | 拡張チャネル解釈識別子。 |
| [getEncodeMode()](#getEncodeMode--) | Pdf417 エンコードモードを識別します。 |
| [getErrorLevel()](#getErrorLevel--) | BarCode のエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを取得します。level0 はエラー訂正情報がないことを意味し、level8 は最高のエラー訂正であり、より大きな画像を意味します。 |
| [getMacroCharacters()](#getMacroCharacters--) | マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコーディングを取得するために使用されます。 |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 バーコードの受取人名（オプションフィールド）。 |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 バーコードのチェックサム（オプションフィールド）。 |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | 拡張チャネル解釈識別子。 |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | MacroPdf417 バーコードのファイル ID（必須フィールド）。 |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 バーコードのファイル名（オプションフィールド）。 |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 ファイルサイズ（オプションフィールド）。 |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | MacroPdf417 バーコードのセグメント ID（必須フィールド）。0 から始まり、MacroSegmentsCount - 1 までです。 |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | MacroPdf417 バーコードのセグメント数（オプションフィールド）。 |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 バーコードの送信者名（オプションフィールド）。 |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | エンコーダーにセグメントにマクロ PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用されます。 |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。 |
| [getRows()](#getRows--) | 行数。 |
| [getTruncate()](#getTruncate--) | BarCode の Pdf417 シンボルタイプが省略されているかどうか（スペース削減のため）。 |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | MicroPdf417 と組み合わせてのみ使用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、さらに 910 と 911 もエンコード可能です。これらは、認識された MicroPdf417 が Code 128 として解釈できることを示します。 |
| [isLinked()](#isLinked--) | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 「Linked」 UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボルでは、EAN.UCC 以外の関連線形コンポーネントへの 918 リンケージフラグをエンコードします。 |
| [isReaderInitialization()](#isReaderInitialization--) | リーダーにシンボル内のデータをリーダー初期化用プログラミングとして解釈させるために使用されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2Dバーコードモジュールの高さ/幅比率。 |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | MicroPdf417 と組み合わせてのみ使用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、さらに 910 と 911 もエンコード可能です。これらは、認識された MicroPdf417 が Code 128 として解釈できることを示します。 |
| [setColumns(int value)](#setColumns-int-) | 列数。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 拡張チャネル解釈識別子。 |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Pdf417 エンコードモードを識別します。 |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | BarCode のエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを設定します。level0 はエラー訂正情報がないことを意味し、level8 は最高のエラー訂正であり、より大きな画像を意味します。 |
| [setLinked(boolean value)](#setLinked-boolean-) | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 「Linked」 UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボルでは、EAN.UCC 以外の関連線形コンポーネントへの 918 リンケージフラグをエンコードします。 |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコーディングを取得するために使用されます。 |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 バーコードの受取人名（オプションフィールド）。 |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 バーコードのチェックサム（オプションフィールド）。 |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | 拡張チャネル解釈識別子。 |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | MacroPdf417 バーコードのファイル ID（必須フィールド）。 |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 バーコードのファイル名（オプションフィールド）。 |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 ファイルサイズ（オプションフィールド）。 |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | MacroPdf417 バーコードのセグメント ID（必須フィールド）。0 から始まり、MacroSegmentsCount - 1 までです。 |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | MacroPdf417 バーコードのセグメント数（オプションフィールド）。 |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 バーコードの送信者名（オプションフィールド）。 |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | エンコーダーにセグメントにマクロ PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用されます。 |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | リーダーにシンボル内のデータをリーダー初期化用プログラミングとして解釈させるために使用されます。 |
| [setRows(int value)](#setRows-int-) | 行数。 |
| [setTruncate(boolean value)](#setTruncate-boolean-) | BarCode の Pdf417 シンボルタイプが省略されているかどうか（スペース削減のため）。 |
| [toString()](#toString--) | この [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) の人間が読みやすい文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2Dバーコードモジュールの高さ/幅比率。

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


拡張チャネル解釈識別子です。シンボル内のデータをエンコードする際に使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装は、すべての既知の文字セットエンコーディングで構成されています。

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Pdf417 のエンコードモードを識別します。デフォルト値: Auto。

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


BarCode のエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを取得します。level0 はエラー訂正情報がないことを意味し、level8 は最高のエラー訂正であり、より大きな画像を意味します。

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


マクロ文字 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを取得するために使用されます。MicroPdf417 でのみ使用でき、916 および 917 の MicroPdf417 モードをエンコードします。デフォルト値: MacroCharacters.None。

これらのサンプルは、MicroPdf417 でマクロ文字をエンコードする方法を示しています。

```

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 バーコードの受取人名（オプションフィールド）。MicroPDF417 バーコードの受取人名（Structured Append モード用のオプションフィールド）

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 バーコードのチェックサム（オプションフィールド）。MicroPDF417 バーコードのチェックサム（Structured Append モード用のオプションフィールド）チェックサムフィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


拡張チャネル解釈識別子です。Macro PDF417 のテキストフィールドに適用されます。

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


MacroPdf417 バーコードのファイル名（オプションフィールド）。MicroPDF417 バーコードのファイル名（Structured Append モード用のオプションフィールド）

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 のファイルサイズ（オプションフィールド）。MicroPDF417 のファイルサイズ（Structured Append モード用のオプションフィールド）ファイルサイズフィールドは、元のソースファイル全体のバイト数を示します。

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


MacroPdf417 バーコードのセグメント ID（必須フィールド）。0 から MacroSegmentsCount - 1 までです。MicroPDF417 バーコードのセグメント ID（Structured Append モード用の必須フィールド）

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


MacroPdf417 バーコードのセグメント数（オプションフィールド）。MicroPDF417 バーコードのセグメント数（Structured Append モード用のオプションフィールド）

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 バーコードの送信者名（オプションフィールド）。MicroPDF417 バーコードの送信者名（Structured Append モード用のオプションフィールド）

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


エンコーダに、セグメントに Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用します。Macro PDF417 にのみ適用されます。

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。MicroPDF417 バーコードのタイムスタンプ（Structured Append モード用のオプションフィールド）

**Returns:**
java.time.LocalDateTime
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


BarCode の Pdf417 シンボルタイプが省略されているかどうか（スペース削減のため）。CompactPDF417 とも呼ばれます。このモードでは右側の行インジケータと右側のストップパターンが削除されます。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


MicroPdf417 と組み合わせてのみ使用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、さらに 910 と 911 もエンコード可能です。これらは、認識された MicroPdf417 が Code 128 として解釈できることを示します。

これらのサンプルは、2 番目の位置に FNC1 を入れた場合と入れない場合の Code 128 エミュレーションモードのエンコード方法を示しています。この方法により MicroPdf417 は Code 128 バーコードとしてデコードできます。

```

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 「Linked」 UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボルでは、EAN.UCC 以外の関連線形コンポーネントへの 918 リンケージフラグをエンコードします。

これらのサンプルは、GS1MicroPdf417 の「リンク」 UCC/EAN-128 モードと、MicroPdf417 および Pdf417 バーコードのリンクフラグ（918）のエンコード方法を示しています。

```

```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


リーダーにシンボル内のデータをリーダー初期化用プログラミングとして解釈させるために使用されます。

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


2Dバーコードモジュールの高さ/幅比率。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


MicroPdf417 と組み合わせてのみ使用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、さらに 910 と 911 もエンコード可能です。これらは、認識された MicroPdf417 が Code 128 として解釈できることを示します。

これらのサンプルは、2 番目の位置に FNC1 を入れた場合と入れない場合の Code 128 エミュレーションモードのエンコード方法を示しています。この方法により MicroPdf417 は Code 128 バーコードとしてデコードできます。

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


列数。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


拡張チャネル解釈識別子です。シンボル内のデータをエンコードする際に使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装は、すべての既知の文字セットエンコーディングで構成されています。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Pdf417 のエンコードモードを識別します。デフォルト値: Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


BarCode のエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボルタイプを設定します。level0 はエラー訂正情報がないことを意味し、level8 は最高のエラー訂正であり、より大きな画像を意味します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | BarCode の Pdf417 シンボルタイプの誤り訂正レベルは level0 から level8 まであり、level0 は誤り訂正情報がなく、level8 は最高の誤り訂正であり、画像が大きくなります。 |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 「Linked」 UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボルでは、EAN.UCC 以外の関連線形コンポーネントへの 918 リンケージフラグをエンコードします。

これらのサンプルは、GS1MicroPdf417 の「リンク」 UCC/EAN-128 モードと、MicroPdf417 および Pdf417 バーコードのリンクフラグ（918）のエンコード方法を示しています。

```

 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked modes 906, 907 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());
 
```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


マクロ文字 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを取得するために使用されます。MicroPdf417 でのみ使用でき、916 および 917 の MicroPdf417 モードをエンコードします。デフォルト値: MacroCharacters.None。

これらのサンプルは、MicroPdf417 でマクロ文字をエンコードする方法を示しています。

```

```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 バーコードの受取人名（オプションフィールド）。MicroPDF417 バーコードの受取人名（Structured Append モード用のオプションフィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 バーコードのチェックサム（オプションフィールド）。MicroPDF417 バーコードのチェックサム（Structured Append モード用のオプションフィールド）チェックサムフィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


拡張チャネル解釈識別子です。Macro PDF417 のテキストフィールドに適用されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


MacroPdf417 バーコードのファイル ID（必須フィールド）。MicroPDF417 バーコードのファイル ID（Structured Append モード用の必須フィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 バーコードのファイル名（オプションフィールド）。MicroPDF417 バーコードのファイル名（Structured Append モード用のオプションフィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 のファイルサイズ（オプションフィールド）。MicroPDF417 のファイルサイズ（Structured Append モード用のオプションフィールド）ファイルサイズフィールドは、元のソースファイル全体のバイト数を示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


MacroPdf417 バーコードのセグメント ID（必須フィールド）。0 から MacroSegmentsCount - 1 までです。MicroPDF417 バーコードのセグメント ID（Structured Append モード用の必須フィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


MacroPdf417 バーコードのセグメント数（オプションフィールド）。MicroPDF417 バーコードのセグメント数（Structured Append モード用のオプションフィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 バーコードの送信者名（オプションフィールド）。MicroPDF417 バーコードの送信者名（Structured Append モード用のオプションフィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


エンコーダに、セグメントに Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用します。Macro PDF417 にのみ適用されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。MicroPDF417 バーコードのタイムスタンプ（Structured Append モード用のオプションフィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


リーダーにシンボル内のデータをリーダー初期化用プログラミングとして解釈させるために使用されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


行数。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


BarCode の Pdf417 シンボルタイプが省略されているかどうか（スペース削減のため）。CompactPDF417 とも呼ばれます。このモードでは右側の行インジケータと右側のストップパターンが削除されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


この [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) の人間が読みやすい文字列表現を返します。

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

