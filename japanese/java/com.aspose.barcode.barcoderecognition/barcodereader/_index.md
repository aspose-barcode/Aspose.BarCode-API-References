---
title: "BarCodeReader"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "BarCodeReader は、1 つまたは複数のバーコードを含む可能性のある画像をカプセル化し、バーコードを検出するために ReadBarCodes 操作を実行できます。"
type: docs
weight: 14
url: /ja/java/com.aspose.barcode.barcoderecognition/barcodereader/
---
**Inheritance:**
java.lang.Object
```
public class BarCodeReader
```

BarCodeReader は、1 つまたは複数のバーコードを含む可能性のある画像をカプセル化し、バーコードを検出するために ReadBarCodes 操作を実行できます。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BarCodeReader()](#BarCodeReader--) | BarCodeReader クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [BarCodeReader(BufferedImage image)](#BarCodeReader-java.awt.image.BufferedImage-) | 画像から BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(BufferedImage image, BaseDecodeType decodeType)](#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(BufferedImage image, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(BufferedImage image, Rectangle area, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(String imagePath, Rectangle[] areas, BaseDecodeType type)](#BarCodeReader-java.lang.String-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(InputStream stream, Rectangle area, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(String imagePath, Rectangle area, BaseDecodeType type)](#BarCodeReader-java.lang.String-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(InputStream stream, Rectangle[] areas, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(BufferedImage image, Rectangle[] areas, BaseDecodeType type)](#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(String filename)](#BarCodeReader-java.lang.String-) | ファイルから BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(String filename, BaseDecodeType type)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(String filename, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(InputStream stream)](#BarCodeReader-java.io.InputStream-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(InputStream stream, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [abort()](#abort--) | 関数は、別スレッドから現在の認識セッションの終了を要求します。 |
| [dispose()](#dispose--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xmlStream)](#exportToXml-java.io.OutputStream-) | 指定された XML ストリームに BarCode プロパティをエクスポートします |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | 指定された XML ファイルに BarCode プロパティをエクスポートします |
| [getBarCodeReadType()](#getBarCodeReadType--) | 入力バーコードデコードのデコードタイプを取得します |
| [getBarcodeSettings()](#getBarcodeSettings--) | 主なバーコードデコードパラメータです。 |
| [getClass()](#getClass--) |  |
| [getFoundBarCodes()](#getFoundBarCodes--) | 認識された BarCodeResult 配列を取得します |
| [getFoundCount()](#getFoundCount--) | 認識されたバーコードの数を取得します |
| [getProcessorSettings()](#getProcessorSettings--) | プロセッサコアの使用設定を取得します。 |
| [getQualitySettings()](#getQualitySettings--) | QualitySettings は、認識の品質と速度を手動で構成できるようにします |
| [getTimeout()](#getTimeout--) | 認識プロセスのタイムアウト（ミリ秒）を取得します。 |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xmlStream)](#importFromXml-java.io.InputStream-) | 指定されたXMLストリームからバーコードプロパティをインポートし、現在のBarCodeReaderインスタンスに適用します。 |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | 指定されたXMLファイルからバーコードプロパティをインポートし、現在のBarCodeReaderインスタンスに適用します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBarCodes()](#readBarCodes--) | 画像からBarCodeResultを読み取ります。 |
| [setBarCodeImage(BufferedImage value)](#setBarCodeImage-java.awt.image.BufferedImage-) | 認識用にビットマップ画像を設定します。 |
| [setBarCodeImage(BufferedImage value, Rectangle area)](#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle-) | 認識用にビットマップ画像と領域を設定します。 |
| [setBarCodeImage(BufferedImage value, Rectangle[] areas)](#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle---) | 認識用にビットマップ画像と複数の領域を設定します。 |
| [setBarCodeImage(InputStream stream)](#setBarCodeImage-java.io.InputStream-) | 認識用に画像ストリームを設定します。 |
| [setBarCodeImage(String filename)](#setBarCodeImage-java.lang.String-) | 認識用に画像ファイルを設定します。 |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 認識用にデコードタイプを設定します。 |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | 認識用にSingleDecodeType型の配列を設定します。 |
| [setQualitySettings(QualitySettings value)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings は、認識の品質と速度を手動で構成できるようにします |
| [setTimeout(int value)](#setTimeout-int-) | 認識プロセスのタイムアウト（ミリ秒）を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeReader() {#BarCodeReader--}
```
public BarCodeReader()
```


デフォルト値でBarCodeReaderクラスの新しいインスタンスを初期化します。ReadBarCodes()メソッドを呼び出す前に画像を設定（SetBitmapImage()）する必要があります。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage("c:\\test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

### BarCodeReader(BufferedImage image) {#BarCodeReader-java.awt.image.BufferedImage-}
```
public BarCodeReader(BufferedImage image)
```


画像から BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp);
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | java.awt.image.BufferedImage | 画像を含むBitmapインスタンス |

### BarCodeReader(BufferedImage image, BaseDecodeType decodeType) {#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(BufferedImage image, BaseDecodeType decodeType)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | java.awt.image.BufferedImage | 画像です。 |
| decodeType | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプ1です。単一または複数に設定できます。 |

### BarCodeReader(BufferedImage image, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(BufferedImage image, BaseDecodeType[] decodeTypes)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | java.awt.image.BufferedImage | 画像です。 |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプ。 |

### BarCodeReader(BufferedImage image, Rectangle area, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(BufferedImage image, Rectangle area, BaseDecodeType[] decodeTypes)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | java.awt.image.BufferedImage | 画像です。 |
| 領域 | java.awt.Rectangle | 認識用の領域です。 |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプ。 |

### BarCodeReader(String imagePath, Rectangle[] areas, BaseDecodeType type) {#BarCodeReader-java.lang.String-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rectangle[] areas, BaseDecodeType type)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imagePath | java.lang.String | 画像のパス。 |
| 領域 | java.awt.Rectangle[] | 認識用の領域です。 |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプです。 |

### BarCodeReader(InputStream stream, Rectangle area, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rectangle area, BaseDecodeType type)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 画像ストリームです。 |
| 領域 | java.awt.Rectangle | 認識用の領域です。 |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプです。 |

### BarCodeReader(String imagePath, Rectangle area, BaseDecodeType type) {#BarCodeReader-java.lang.String-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rectangle area, BaseDecodeType type)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imagePath | java.lang.String | 画像のパス。 |
| 領域 | java.awt.Rectangle | 認識用の領域です。 |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプです。 |

### BarCodeReader(InputStream stream, Rectangle[] areas, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rectangle[] areas, BaseDecodeType type)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 画像ストリームです。 |
| 領域 | java.awt.Rectangle[] | 認識用の領域です。 |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプです。 |

### BarCodeReader(BufferedImage image, Rectangle[] areas, BaseDecodeType type) {#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(BufferedImage image, Rectangle[] areas, BaseDecodeType type)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | java.awt.image.BufferedImage | 画像です。 |
| 領域 | java.awt.Rectangle[] | 認識用の領域です。 |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプです。 |

### BarCodeReader(String filename) {#BarCodeReader-java.lang.String-}
```
public BarCodeReader(String filename)
```


ファイルから BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png");
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | ファイル名です。 |

### BarCodeReader(String filename, BaseDecodeType type) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String filename, BaseDecodeType type)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | ファイル名です。 |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプです。 |

### BarCodeReader(String filename, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(String filename, BaseDecodeType[] decodeTypes)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | ファイル名です。 |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプ。 |

### BarCodeReader(InputStream stream) {#BarCodeReader-java.io.InputStream-}
```
public BarCodeReader(InputStream stream)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(fstr);
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ストリームです。 |

### BarCodeReader(InputStream stream, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, BaseDecodeType type)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader(fstr, new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ストリームです。 |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプです。 |

### BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)
```


BarCodeReader クラスの新しいインスタンスを初期化します。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(fstr, DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ストリームです。 |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプ。 |

### abort() {#abort--}
```
public void abort()
```


関数は別スレッドから現在の認識セッションの終了を要求します。Abort はブロックできないメソッドで、呼び出し直後に制御が戻ります。認識プロセスが長時間かかる場合にこのメソッドを使用すべきです。

--------------------

> ```
> This sample shows how to call Abort function from other thread
>  
>   final BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>   Thread thread1 = new Thread(new Runnable()
>   {
>       public void run()
>       {
>           for(BarCodeResult result : reader.readBarCodes())
>           {
>               System.out.println("BarCode Type: " + result.getCodeType());
>               System.out.println("BarCode CodeText: " + result.getCodeText());
>           }
>        }
>   });
>   thread1.start();
>   Thread.sleep(100);
>   reader.abort();
> ```

### dispose() {#dispose--}
```
public void dispose()
```




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
### exportToXml(OutputStream xmlStream) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xmlStream)
```


指定された XML ストリームに BarCode プロパティをエクスポートします

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlStream | java.io.OutputStream | 保存用の xml ストリームです。 |

**Returns:**
boolean - エクスポートが正常に完了したかどうか。

成功した場合は **True** を返し、そうでない場合は **False** を返します。
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


指定された XML ファイルに BarCode プロパティをエクスポートします

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlFile | java.lang.String | ファイルの名前です。 |

**Returns:**
boolean - エクスポートが正常に完了したかどうか。

成功した場合は **True** を返し、そうでない場合は **False** を返します。
### getBarCodeReadType() {#getBarCodeReadType--}
```
public BaseDecodeType getBarCodeReadType()
```


入力バーコードデコードのデコードタイプを取得します

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


主な BarCode デコードパラメータです。認識されたデータに影響を与えるパラメータが含まれます。

**Returns:**
[BarcodeSettings](../../com.aspose.barcode.barcoderecognition/barcodesettings) - The main BarCode decoding parameters
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFoundBarCodes() {#getFoundBarCodes--}
```
public BarCodeResult[] getFoundBarCodes()
```


認識された BarCodeResult 配列を取得します

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  {
>      reader.readBarCodes();
>      for(int i = 0; reader.getFoundCount() > i; ++i)
>          System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
>  }
> ```

値: 認識された BarCodeResult 配列

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[]
### getFoundCount() {#getFoundCount--}
```
public int getFoundCount()
```


認識されたバーコードの数を取得します

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

値: 認識されたバーコードの数

**Returns:**
int
### getProcessorSettings() {#getProcessorSettings--}
```
public static ProcessorSettings getProcessorSettings()
```


プロセッサコアの使用設定を取得します。

--------------------

> ```
> This sample shows how to use ProcessorSettings to add maximum multi-threaded performnce
>  
>  //this allows to use all cores for single BarCodeReader call
>  BarCodeReader.getProcessorSettings().setUseAllCores(true);
>  //this allows to use current count of cores
>  BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```

**Returns:**
[ProcessorSettings](../../com.aspose.barcode.barcoderecognition/processorsettings)
### getQualitySettings() {#getQualitySettings--}
```
public final QualitySettings getQualitySettings()
```


QualitySettings は認識の品質と速度を手動で設定できるようにします。組み込みのプリセット（HighPerformance、NormalQuality、HighQuality、MaxBarCodes）を使用して QualitySettings をすばやく設定することも、個別のオプションを手動で構成することもできます。QualitySettings のデフォルト値は NormalQuality です。

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //normal quality mode is set by default
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  //set separate options
>  reader.getQualitySettings().setAllowMedianSmoothing(true);
>  reader.getQualitySettings().setMedianSmoothingWindowSize(5);
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

値: 認識品質と速度を設定する QualitySettings。

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


認識プロセスのタイムアウト（ミリ秒）を取得します。

```
BarCodeReader reader = new BarCodeReader("c:\\test.png");
     reader.setTimeout(5000);
     for(BarCodeResult result : reader.readBarCodes())
         System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Returns:**
int - タイムアウトです。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importFromXml(InputStream xmlStream) {#importFromXml-java.io.InputStream-}
```
public static BarCodeReader importFromXml(InputStream xmlStream)
```


指定されたXMLストリームからバーコードプロパティをインポートし、現在のBarCodeReaderインスタンスに適用します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlStream | java.io.InputStream | ロード用の xml ストリーム |

**Returns:**
[BarCodeReader](../../com.aspose.barcode.barcoderecognition/barcodereader) - Returns  **True**  in case of success;

 **False**  Otherwise
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarCodeReader importFromXml(String xmlFile)
```


指定されたXMLファイルからバーコードプロパティをインポートし、現在のBarCodeReaderインスタンスに適用します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlFile | java.lang.String | ファイルの名前です。 |

**Returns:**
[BarCodeReader](../../com.aspose.barcode.barcoderecognition/barcodereader) - Returns  **True**  in case of success;

 **False**  Otherwise
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readBarCodes() {#readBarCodes--}
```
public BarCodeResult[] readBarCodes()
```


画像からBarCodeResultを読み取ります。

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[] - 画像上で認識された BarCodeResult の配列を返します。何も認識されなかった場合、長さ0の配列が返されます。
### setBarCodeImage(BufferedImage value) {#setBarCodeImage-java.awt.image.BufferedImage-}
```
public void setBarCodeImage(BufferedImage value)
```


認識用にビットマップ画像を設定します。ReadBarCodes() メソッドの前に呼び出す必要があります。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader())
>  {
>      reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>      reader.setBarCodeImage(bmp);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>      }
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.image.BufferedImage | 認識用のビットマップ画像です。 |

### setBarCodeImage(BufferedImage value, Rectangle area) {#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle-}
```
public final void setBarCodeImage(BufferedImage value, Rectangle area)
```


認識用にビットマップ画像と領域を設定します。ReadBarCodes() メソッドの前に呼び出す必要があります。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()));
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.image.BufferedImage | 認識用のビットマップ画像です。 |
| 領域 | java.awt.Rectangle | 認識用の領域 |

### setBarCodeImage(BufferedImage value, Rectangle[] areas) {#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle---}
```
public final void setBarCodeImage(BufferedImage value, Rectangle[] areas)
```


認識用にビットマップ画像と複数の領域を設定します。ReadBarCodes() メソッドの前に呼び出す必要があります。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()) });
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.image.BufferedImage | 認識用のビットマップ画像です。 |
| 領域 | java.awt.Rectangle[] | 認識用の領域リスト |

### setBarCodeImage(InputStream stream) {#setBarCodeImage-java.io.InputStream-}
```
public final void setBarCodeImage(InputStream stream)
```


認識用に画像ストリームを設定します。ReadBarCodes() メソッドの前に呼び出す必要があります。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage(fstr);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 認識用の画像ストリームです。 |

### setBarCodeImage(String filename) {#setBarCodeImage-java.lang.String-}
```
public void setBarCodeImage(String filename)
```


認識用に画像ファイルを設定します。ReadBarCodes() メソッドの前に呼び出す必要があります。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader())
>  {
>      reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>      reader.setBarCodeImage("c:\\test.png");
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>      }
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | 認識用の画像ファイルです。 |

### setBarCodeReadType(BaseDecodeType type) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public void setBarCodeReadType(BaseDecodeType type)
```


認識用にデコードタイプを設定します。ReadBarCodes() メソッドの前に呼び出す必要があります。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128));
>  reader.setBarCodeImage("c:/test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
>  System.out.println("BarCodeReadType: " + reader.getBarCodeReadType().toString());
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 読み取るバーコードのタイプです。 |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


認識用に SingleDecodeType 型の配列を設定します。ReadBarCodes() メソッドの前に呼び出す必要があります。

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage("c:\\test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 読み取る SingleDecodeType 型の配列です。 |

### setQualitySettings(QualitySettings value) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public final void setQualitySettings(QualitySettings value)
```


QualitySettings は認識の品質と速度を手動で設定できるようにします。組み込みのプリセット（HighPerformance、NormalQuality、HighQuality、MaxBarCodes）を使用して QualitySettings をすばやく設定することも、個別のオプションを手動で構成することもできます。QualitySettings のデフォルト値は NormalQuality です。

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //normal quality mode is set by default
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  //set separate options
>  reader.getQualitySettings().setAllowMedianSmoothing(true);
>  reader.getQualitySettings().setMedianSmoothingWindowSize(5);
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

値: 認識品質と速度を設定する QualitySettings。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) |  |

### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


認識プロセスのタイムアウト（ミリ秒）を設定します。

```
BarCodeReader reader = new BarCodeReader("c:\\test.png");
 reader.setTimeout(5000);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | タイムアウトです。 |

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

