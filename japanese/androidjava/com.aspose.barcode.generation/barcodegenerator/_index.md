---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "バックエンドのバーコード画像生成のための BarcodeGenerator。"
type: docs
weight: 13
url: /ja/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

バックエンドのバーコード画像生成のための BarcodeGenerator。

サポートされているシンボル: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | BarcodeGenerator のインスタンスを作成します。 |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | BarcodeGenerator のインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [dispose()](#dispose--) | 使用中のリソースをクリーンアップします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | 指定された XML ストリームに BarCode のプロパティをエクスポートします |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | 指定された XML ファイルに BarCode のプロパティをエクスポートします |
| [generateBarCodeImage()](#generateBarCodeImage--) | 現在の設定でバーコード画像を生成します。 |
| [getBarcodeType()](#getBarcodeType--) | バーコードのシンボロジータイプ。 |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | エンコードするテキスト。 |
| [getParameters()](#getParameters--) | 生成パラメーター。 |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | 指定された xml-stream から BarCode プロパティをインポートし、BarcodeGenerator のインスタンスを作成します。 |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | 指定された xml-file から BarCode プロパティをインポートし、BarcodeGenerator のインスタンスを作成します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | BarCodeImage を指定された形式でストリームに保存します。 |
| [save(String filename)](#save-java.lang.String-) | バーコード画像を指定されたファイルに保存します。 |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | バーコード画像を指定された形式で指定されたファイルに保存します。 |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | バーコードのシンボロジータイプ。 |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | codetext をバイト列として設定します。 |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | エンコードするテキスト。 |
| [setCodeText(String codeText, Charset encoding)](#setCodeText-java.lang.String-java.nio.charset.Charset-) |  |
| [setCodeText(String codeText, Charset encoding, boolean insertBOM)](#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeGenerator(BaseEncodeType type) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-}
```
public BarcodeGenerator(BaseEncodeType type)
```


BarcodeGenerator のインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | バーコードのシンボロジータイプ。シンボロジーを設定するには EncodeTypes クラスを使用します。 |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


BarcodeGenerator のインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | バーコードのシンボロジータイプ。シンボロジーを設定するには EncodeTypes クラスを使用します。 |
| codeText | java.lang.String | エンコードするテキスト。 |

### dispose() {#dispose--}
```
public void dispose()
```


使用中のリソースをクリーンアップします。

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
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


指定された XML ストリームに BarCode のプロパティをエクスポートします

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xml | java.io.OutputStream | xml-stream |

**Returns:**
boolean - エクスポートが正常に完了したかどうか。成功した場合は **True** を返し、そうでない場合は **False** を返します。
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


指定された XML ファイルに BarCode のプロパティをエクスポートします

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlFile | java.lang.String | ファイルの名前 |

**Returns:**
boolean - エクスポートが正常に完了したかどうか。

成功した場合は **True** を返し、そうでない場合は **False** を返します。
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


現在の設定でバーコード画像を生成します。

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          File outputFile = new File("test.png");
>          OutputStream os = new FileOutputStream(outputFile);
>          Bitmap generatedBitmap = generator.generateBarCodeImage();
>          generatedBitmap.compress(Bitmap.CompressFormat.PNG, 100, os);
>          os.flush();
>          os.close();
> ```

**Returns:**
android.graphics.Bitmap - バーコード画像。参照 Bitmap。
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


バーコードのシンボロジータイプ。

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


エンコードするテキスト。

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


生成パラメーター。

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importFromXml(InputStream xml) {#importFromXml-java.io.InputStream-}
```
public static BarcodeGenerator importFromXml(InputStream xml)
```


指定された xml-stream から BarCode プロパティをインポートし、BarcodeGenerator のインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xml | java.io.InputStream | xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


指定された xml-file から BarCode プロパティをインポートし、BarcodeGenerator のインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlFile | java.lang.String | ファイルの名前 |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream, BarCodeImageFormat format) {#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(OutputStream stream, BarCodeImageFormat format)
```


BarCodeImage を指定された形式でストリームに保存します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


バーコード画像を指定されたファイルに保存します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | java.lang.String | 保存先のパス。 |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


バーコード画像を指定された形式で指定されたファイルに保存します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | java.lang.String | 保存先のパス。 |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | 出力画像のファイル形式を指定します。 |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


バーコードのシンボロジータイプ。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


codetext をバイト列として設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| codeBytes | byte[] | codetext のバイト数 |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


エンコードするテキスト。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


指定された **encoding** を使用して Unicode の **codeText** をバイト列にエンコードします。UTF-8 は最も一般的に使用されるエンコーディングです。エンコーディングがサポートしている場合、関数は自動的に [byte order mark (BOM)][byte order mark _BOM] を挿入します。

この関数は 2D バーコードのみでの使用を想定しています（例: Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR など）。国別または特殊なエンコーディングを使用して Unicode テキストを手動でエンコードできるようにしますが、現代のアプリケーションではこの方法は時代遅れと見なされています。最新のユースケースでは Unicode データに対して [ECI][] エンコーディングの使用が推奨されます。

この関数を 1D バーコード、GS1 準拠のバーコード（2D を含む）または HIBC バーコード（2D を含む）で使用することは、該当するバーコード規格でサポートされておらず、予測できない結果を招く可能性があります。

--------------------

> ```
> This example shows how to use ```
> SetCodeText
> ``` setting Unicode-encoded text for 2D barcodes using different encodings:
>   
>   //Encode QR Code text using UTF-8 with BOM
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8;
>   gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  	//Encode DataMatrix text using Shift-JIS (Japanese encoding)
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| codeText | java.lang.String | CodeText 文字列 |
| encoding | java.nio.charset.Charset | 適用されたエンコーディング |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


指定された **encoding** を使用して Unicode の **codeText** をバイト列にエンコードします。UTF-8 は最も一般的に使用されるエンコーディングです。エンコーディングがサポートし、かつ **insertBOM** が true に設定されている場合、関数は [byte order mark (BOM)][byte order mark _BOM] を含めます。

この関数は 2D バーコードのみでの使用を想定しています（例: Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR など）。国別または特殊なエンコーディングを使用して Unicode テキストを手動でエンコードできるようにしますが、現代のアプリケーションではこの方法は時代遅れと見なされています。最新のユースケースでは Unicode データに対して [ECI][] エンコーディングの使用が推奨されます。

この関数を 1D バーコード、GS1 準拠のバーコード（2D を含む）または HIBC バーコード（2D を含む）で使用することは、該当するバーコード規格でサポートされておらず、予測できない結果を招く可能性があります。

--------------------

> ```
> This example shows how to use ```
> SetCodeText
> ``` with or without a BOM for 2D barcodes.
>   
>  	//Encode codetext using UTF-8 with BOM
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8, true);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  	//Encode codetext using UTF-8 without BOM
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8, false);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| codeText | java.lang.String | CodeText 文字列 |
| encoding | java.nio.charset.Charset | 適用されたエンコーディング |
| insertBOM | boolean | 指定されたエンコーディングがサポートしている場合にバイトオーダーマーク（BOM）を挿入するかどうかを示します（例: UTF-8、UTF-16、UTF-32）。true に設定するとBOMが追加され、false に設定すると、エンコーディングが通常BOMを使用する場合でも省略されます。 |

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

