---
title: BarcodeGenerator
second_title: Aspose.BarCode for Android via Java API Reference
description: BarcodeGenerator for backend barcode images generation.
type: docs
weight: 13
url: /ja/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator for backend barcode images generation.

サポートされているシンボロジー: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | BarcodeGenerator のインスタンスを作成します。 |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | BarcodeGenerator のインスタンスを作成します。 |
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Clean up any resources being used. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | 指定された xml-stream に BarCode プロパティをエクスポートします。 |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | 指定された xml-file に BarCode プロパティをエクスポートします。 |
| [generateBarCodeImage()](#generateBarCodeImage--) | 現在の設定でバーコード画像を生成します。 |
| [getBarcodeType()](#getBarcodeType--) | バーコードシンボロジーの種類。 |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | エンコードするテキスト。 |
| [getParameters()](#getParameters--) | Generation parameters. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | 指定された XML ストリームから BarCode プロパティをインポートし、BarcodeGenerator のインスタンスを作成します。 |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | 指定された XML ファイルから BarCode プロパティをインポートし、BarcodeGenerator のインスタンスを作成します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | BarCodeImage を特定の形式でストリームに保存します。 |
| [save(String filename)](#save-java.lang.String-) | バーコード画像を特定のファイルに保存します。 |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | バーコード画像を特定の形式で特定のファイルに保存します。 |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | バーコードシンボロジーの種類。 |
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
| Parameter | Type | Description |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | バーコードシンボロジーの種類。EncodeTypes クラスを使用してシンボロジーを設定します。 |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


BarcodeGenerator のインスタンスを作成します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | バーコードシンボロジーの種類。EncodeTypes クラスを使用してシンボロジーを設定します。 |
| codeText | java.lang.String | エンコードするテキスト。 |

### dispose() {#dispose--}
```
public void dispose()
```


Clean up any resources being used.

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
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


指定された xml-stream に BarCode プロパティをエクスポートします。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xml | java.io.OutputStream | xmlストリーム |

**Returns:**
boolean - エクスポートが正常に完了したかどうか。成功した場合は **True** を返し、そうでない場合は **False** を返します。
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


指定された xml-file に BarCode プロパティをエクスポートします。

**Parameters:**
| Parameter | Type | Description |
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
android.graphics.Bitmap - Barcode image. See  Bitmap .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


バーコードシンボロジーの種類。

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


Generation parameters.

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


指定された XML ストリームから BarCode プロパティをインポートし、BarcodeGenerator のインスタンスを作成します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xml | java.io.InputStream | xmlストリーム |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


指定された XML ファイルから BarCode プロパティをインポートし、BarcodeGenerator のインスタンスを作成します。

**Parameters:**
| Parameter | Type | Description |
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


BarCodeImage を特定の形式でストリームに保存します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


バーコード画像を特定のファイルに保存します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ファイル名 | java.lang.String | Path to save to. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


バーコード画像を特定の形式で特定のファイルに保存します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ファイル名 | java.lang.String | Path to save to. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specifies the file format of the output image. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


バーコードシンボロジーの種類。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


codetext をバイト列として設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codeBytes | byte[] | codetext のバイト |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


エンコードするテキスト。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


指定された **encoding** を使用して、Unicode の **codeText** をバイト列にエンコードします。UTF-8 は最も一般的に使用されるエンコーディングです。エンコーディングがサポートしている場合、関数は自動的に [byte order mark (BOM)][byte order mark _BOM] を挿入します。

この関数は 2D バーコード（例: Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR など）のみを対象としています。国別または特殊なエンコーディングを使用した Unicode テキストの手動エンコードを可能にしますが、現代のアプリケーションではこの方法は旧式と見なされています。最新のユースケースでは、Unicode データに対して [ECI][] エンコーディングの使用が推奨されます。

この関数を 1D バーコード、GS1 準拠のバーコード（2D を含む）、または HIBC バーコード（2D を含む）で使用することは、該当するバーコード規格でサポートされておらず、予測できない結果を招く可能性があります。

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
| Parameter | Type | Description |
| --- | --- | --- |
| codeText | java.lang.String | CodeText 文字列 |
| エンコーディング | java.nio.charset.Charset | 適用されたエンコーディング |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


指定された **encoding** を使用して、Unicode の **codeText** をバイト列にエンコードします。UTF-8 は最も一般的に使用されるエンコーディングです。エンコーディングがサポートし、**insertBOM** が true に設定されている場合、関数は [byte order mark (BOM)][byte order mark _BOM] を含めます。

この関数は 2D バーコード（例: Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR など）のみを対象としています。国別または特殊なエンコーディングを使用した Unicode テキストの手動エンコードを可能にしますが、現代のアプリケーションではこの方法は旧式と見なされています。最新のユースケースでは、Unicode データに対して [ECI][] エンコーディングの使用が推奨されます。

この関数を 1D バーコード、GS1 準拠のバーコード（2D を含む）、または HIBC バーコード（2D を含む）で使用することは、該当するバーコード規格でサポートされておらず、予測できない結果を招く可能性があります。

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
| Parameter | Type | Description |
| --- | --- | --- |
| codeText | java.lang.String | CodeText 文字列 |
| エンコーディング | java.nio.charset.Charset | 適用されたエンコーディング |
| insertBOM | boolean | 指定されたエンコーディングがサポートしている場合にバイトオーダーマーク (BOM) を挿入するかどうかを示します（例: UTF-8、UTF-16、UTF-32）。true に設定すると BOM が追加され、false に設定すると、エンコーディングが通常 BOM を使用する場合でも省略されます。 |

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

