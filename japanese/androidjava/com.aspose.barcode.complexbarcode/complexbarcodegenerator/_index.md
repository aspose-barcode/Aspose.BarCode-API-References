---
title: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "バックエンドの複雑なバーコード用 ComplexBarcodeGenerator（例）。"
type: docs
weight: 12
url: /ja/androidjava/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

バックエンドの複雑なバーコード（例：SwissQR）画像生成用 ComplexBarcodeGenerator。

--------------------

> ```
> This sample shows how to create and save a SwissQR image.
>   
>     SwissQRCodetext swissQRCodetext = new SwissQRCodetext();
>     swissQRCodetext.getBill().setAccount("Account");
>     swissQRCodetext.getBill().setBillInformation("BillInformation");
>     // init rest of the fields
>     ComplexBarcodeGenerator cg = new ComplexBarcodeGenerator(swissQRCodetext);
>     BufferedImage res = cg.generateBarCodeImage();
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | ComplexBarcodeGenerator のインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [dispose()](#dispose--) | 使用中のリソースをクリーンアップします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | 現在の設定で複雑なバーコード画像を生成します。 |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | 生成パラメーター。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | 現在の設定で複雑なバーコード画像を生成し、保存します。 |
| [save(String filename)](#save-java.lang.String-) | 現在の設定で複雑なバーコード画像を生成し、保存します。 |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | 現在の設定で複雑なバーコード画像を生成し、保存します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


ComplexBarcodeGenerator のインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | 複雑なコードテキスト |

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
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


現在の設定で複雑なバーコード画像を生成します。

**Returns:**
android.graphics.Bitmap - バーコード画像。参照 Bitmap。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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


現在の設定で複雑なバーコード画像を生成し、保存します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 出力 System.IO.Stream。 |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | 出力画像のファイル形式を指定します。 |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


現在の設定で複雑なバーコード画像を生成し、保存します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | java.lang.String | 保存先のパス。 |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


現在の設定で複雑なバーコード画像を生成し、保存します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | java.lang.String | 保存先のパス。 |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | 出力画像のファイル形式を指定します。 |

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

