---
title: "Pdf417ParametersUI"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "UI ラッパー for com.aspose.barcode.generation.Pdf417Parameters クラス。"
type: docs
weight: 16
url: /ja/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

UI ラッパー for com.aspose.barcode.generation.Pdf417Parameters クラス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率です。 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 列数。 |
| [getECIEncoding()](#getECIEncoding--) | 拡張チャネル解釈識別子。 |
| [getEncodeMode()](#getEncodeMode--) | バーコードのエンコードモードの Pdf417 シンボロジータイプ。 |
| [getErrorLevel()](#getErrorLevel--) | バーコードのエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボロジータイプを取得します。level0 はエラー訂正情報がなく、level8 は最高のエラー訂正で、画像が大きくなります。 |
| [getMacroCharacters()](#getMacroCharacters--) | マクロ文字 05 と 06 の値は、特別モードでよりコンパクトなエンコードを取得するために使用されます。 |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 バーコードの受取人名（オプションフィールド）。 |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 バーコードのチェックサム（オプションフィールド）。 |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | 拡張チャネル解釈識別子。 |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | マクロ Pdf417 バーコードのファイル ID を取得します。 |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 バーコードのファイル名（オプションフィールド）。 |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 のファイルサイズ（オプションフィールド）。 |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | マクロ Pdf417 バーコードのセグメント ID を取得します。ID は 0 から MacroSegmentsCount - 1 までです。 |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | マクロ Pdf417 バーコードのセグメント数を取得します。 |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 バーコードの送信者名（オプションフィールド）。 |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | エンコーダにセグメントへ Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用されます。 |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。 |
| [getRows()](#getRows--) | 行数。 |
| [getTruncate()](#getTruncate--) | バーコードの Pdf417 シンボロジータイプが省略されているか（スペース削減のため）を示します。 |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | MicroPdf417 と併用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、また 910 と 911 もエンコードできますが、これは認識された MicroPdf417 が Code 128 として解釈できることを示すだけです。 |
| [isLinked()](#isLinked--) | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボロジーでは 906、907、912、913、914、915 の「Linked」UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボロジーでは、EAN.UCC 以外の関連線形コンポーネントへのリンクフラグ 918 をエンコードします。 |
| [isReaderInitialization()](#isReaderInitialization--) | シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率です。 |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | MicroPdf417 と併用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、また 910 と 911 もエンコードできますが、これは認識された MicroPdf417 が Code 128 として解釈できることを示すだけです。 |
| [setColumns(int value)](#setColumns-int-) | 列数。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 拡張チャネル解釈識別子。 |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | バーコードのエンコードモードの Pdf417 シンボロジータイプ。 |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | バーコードのエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボロジータイプを設定します。level0 はエラー訂正情報がなく、level8 は最高のエラー訂正で、画像が大きくなります。 |
| [setLinked(boolean value)](#setLinked-boolean-) | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボロジーでは 906、907、912、913、914、915 の「Linked」UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボロジーでは、EAN.UCC 以外の関連線形コンポーネントへのリンクフラグ 918 をエンコードします。 |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | マクロ文字 05 と 06 の値は、特別モードでよりコンパクトなエンコードを取得するために使用されます。 |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 バーコードの受取人名（オプションフィールド）。 |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 バーコードのチェックサム（オプションフィールド）。 |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | 拡張チャネル解釈識別子。 |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | マクロ Pdf417 バーコードのファイル ID を設定します。 |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 バーコードのファイル名（オプションフィールド）。 |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 のファイルサイズ（オプションフィールド）。 |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | マクロ Pdf417 バーコードのセグメント ID を設定します。ID は 0 から MacroSegmentsCount - 1 までです。 |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | マクロ Pdf417 バーコードのセグメント数を設定します。 |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 バーコードの送信者名（オプションフィールド）。 |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | エンコーダにセグメントへ Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用されます。 |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。 |
| [setRows(int value)](#setRows-int-) | 行数。 |
| [setTruncate(boolean value)](#setTruncate-boolean-) | バーコードの Pdf417 シンボロジータイプが省略されているか（スペース削減のため）を示します。 |
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


2D バーコードモジュールの高さ/幅比率です。

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


拡張チャネル解釈識別子。シンボル内のデータエンコードに使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装は、すべてのよく知られた文字セットエンコーディングで構成されています。

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


BarCode のエンコードモードの Pdf417 シンボロジータイプ。デフォルト値: Pdf417EncodeMode.Auto。

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


バーコードのエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボロジータイプを取得します。level0 はエラー訂正情報がなく、level8 は最高のエラー訂正で、画像が大きくなります。

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


マクロ文字 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを取得するために使用されます。MicroPdf417 と組み合わせてのみ使用でき、916 および 917 の MicroPdf417 モードをエンコードします。デフォルト値: MacroCharacters.None。

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 バーコードの受取人名（オプション フィールド）。MicroPDF417 バーコードの受取人名（構造付加モード用のオプション フィールド）

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 バーコードのチェックサム（オプション フィールド）。MicroPDF417 バーコードのチェックサム（構造付加モード用のオプション フィールド）チェックサムフィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


拡張チャネル解釈識別子。Macro PDF417 のテキストフィールドに適用されます。

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


マクロ Pdf417 バーコードのファイル ID を取得します。MacroPdf417 用です。

**Returns:**
int - マクロ Pdf417 バーコードのファイル ID。
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 バーコードのファイル名（オプション フィールド）。MicroPDF417 バーコードのファイル名（構造付加モード用のオプション フィールド）

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 ファイルサイズ（オプション フィールド）。MicroPDF417 ファイルサイズ（構造付加モード用のオプション フィールド）ファイルサイズフィールドは、元のソースファイル全体のバイト数を示します。

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


マクロ Pdf417 バーコードのセグメント ID を取得します。ID は 0 から MacroSegmentsCount - 1 までです。

**Returns:**
int - マクロ Pdf417 バーコードのセグメント ID。0 から始まり、MacroSegmentsCount - 1 までです。
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


マクロ Pdf417 バーコードのセグメント数を取得します。

**Returns:**
int - マクロ Pdf417 バーコードのセグメント数。
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 バーコードの送信者名（オプション フィールド）。MicroPDF417 バーコードの送信者名（構造付加モード用のオプション フィールド）

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


エンコーダーにセグメントに Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用されます。Macro PDF417 にのみ適用されます。

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 バーコードのタイムスタンプ（オプション フィールド）。MicroPDF417 バーコードのタイムスタンプ（構造付加モード用のオプション フィールド）

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


バーコードの Pdf417 シンボロジータイプが省略されているか（スペース削減のため）を示します。

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


MicroPdf417 と併用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、また 910 と 911 もエンコードできますが、これは認識された MicroPdf417 が Code 128 として解釈できることを示すだけです。

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボロジーでは 906、907、912、913、914、915 の「Linked」UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボロジーでは、EAN.UCC 以外の関連線形コンポーネントへのリンクフラグ 918 をエンコードします。

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。

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


2D バーコードモジュールの高さ/幅比率です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


MicroPdf417 と併用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、また 910 と 911 もエンコードできますが、これは認識された MicroPdf417 が Code 128 として解釈できることを示すだけです。

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


拡張チャネル解釈識別子。シンボル内のデータエンコードに使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。Macro PDF417 のテキストフィールドには適用されません。現在の実装は、すべてのよく知られた文字セットエンコーディングで構成されています。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


BarCode のエンコードモードの Pdf417 シンボロジータイプ。デフォルト値: Pdf417EncodeMode.Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


バーコードのエラー訂正レベル（level0 から level8）に対応する Pdf417 シンボロジータイプを設定します。level0 はエラー訂正情報がなく、level8 は最高のエラー訂正で、画像が大きくなります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | BarCode のエラー訂正レベルの Pdf417 シンボロジータイプは level0 から level8 まであり、level0 はエラー訂正情報がなく、level8 は最高のエラー訂正であり、より大きな画像になります。 |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボロジーでは 906、907、912、913、914、915 の「Linked」UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボロジーでは、EAN.UCC 以外の関連線形コンポーネントへのリンクフラグ 918 をエンコードします。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


マクロ文字 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを取得するために使用されます。MicroPdf417 と組み合わせてのみ使用でき、916 および 917 の MicroPdf417 モードをエンコードします。デフォルト値: MacroCharacters.None。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 バーコードの受取人名（オプション フィールド）。MicroPDF417 バーコードの受取人名（構造付加モード用のオプション フィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 バーコードのチェックサム（オプション フィールド）。MicroPDF417 バーコードのチェックサム（構造付加モード用のオプション フィールド）チェックサムフィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を含みます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


拡張チャネル解釈識別子。Macro PDF417 のテキストフィールドに適用されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


マクロ Pdf417 バーコードのファイル ID を設定します。MacroPdf417 用です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | マクロ Pdf417 バーコードのファイル ID。 |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 バーコードのファイル名（オプション フィールド）。MicroPDF417 バーコードのファイル名（構造付加モード用のオプション フィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 ファイルサイズ（オプション フィールド）。MicroPDF417 ファイルサイズ（構造付加モード用のオプション フィールド）ファイルサイズフィールドは、元のソースファイル全体のバイト数を示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


マクロ Pdf417 バーコードのセグメント ID を設定します。ID は 0 から MacroSegmentsCount - 1 までです。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | マクロ Pdf417 バーコードのセグメント ID。0 から始まり、MacroSegmentsCount - 1 までです。 |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


マクロ Pdf417 バーコードのセグメント数を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | マクロ Pdf417 バーコードのセグメント数。 |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 バーコードの送信者名（オプション フィールド）。MicroPDF417 バーコードの送信者名（構造付加モード用のオプション フィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


エンコーダーにセグメントに Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用されます。Macro PDF417 にのみ適用されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 バーコードのタイムスタンプ（オプション フィールド）。MicroPDF417 バーコードのタイムスタンプ（構造付加モード用のオプション フィールド）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。

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


バーコードの Pdf417 シンボロジータイプが省略されているか（スペース削減のため）を示します。

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

