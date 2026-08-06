---
title: BarcodeGenerator
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 用于后端条形码图像生成的 BarcodeGenerator。
type: docs
weight: 13
url: /zh/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

用于后端条形码图像生成的 BarcodeGenerator。

支持的符号类型：1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructors

| Constructor | 描述 |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | 创建 BarcodeGenerator 的实例。 |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | 创建 BarcodeGenerator 的实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [dispose()](#dispose--) | 清理正在使用的任何资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | 将 BarCode 属性导出到指定的 xml 流 |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | 将 BarCode 属性导出到指定的 xml 文件 |
| [generateBarCodeImage()](#generateBarCodeImage--) | 根据当前设置生成条形码图像。 |
| [getBarcodeType()](#getBarcodeType--) | 条形码符号类型。 |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | 要编码的文本。 |
| [getParameters()](#getParameters--) | 生成参数。 |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | 从指定的 xml 流导入 BarCode 属性并创建 BarcodeGenerator 实例。 |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | 从指定的 xml 文件导入 BarCode 属性并创建 BarcodeGenerator 实例。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | 以特定格式将 BarCodeImage 保存到流。 |
| [save(String filename)](#save-java.lang.String-) | 将条形码图像保存到指定文件。 |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | 将条形码图像以特定格式保存到指定文件。 |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | 条形码符号类型。 |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | 将 codetext 设置为字节序列。 |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | 要编码的文本。 |
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


创建 BarcodeGenerator 的实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | 条形码符号类型。使用 EncodeTypes 类来设置符号。 |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


创建 BarcodeGenerator 的实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | 条形码符号类型。使用 EncodeTypes 类来设置符号。 |
| codeText | java.lang.String | 要编码的文本。 |

### dispose() {#dispose--}
```
public void dispose()
```


清理正在使用的任何资源。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


将 BarCode 属性导出到指定的 xml 流

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| xml | java.io.OutputStream | XML 流 |

**Returns:**
布尔型 - 导出是否成功完成。成功时返回 **True**；否则返回 **False**
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


将 BarCode 属性导出到指定的 xml 文件

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| xml文件 | java.lang.String | 文件的名称 |

**Returns:**
boolean - 导出是否成功完成。

成功时返回  **True** ；否则返回  **False**
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


根据当前设置生成条形码图像。

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
android.graphics.Bitmap - 条码图像。参见 Bitmap。
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


条形码符号类型。

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


要编码的文本。

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


生成参数。

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


从指定的 xml 流导入 BarCode 属性并创建 BarcodeGenerator 实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| xml | java.io.InputStream | XML 流 |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


从指定的 xml 文件导入 BarCode 属性并创建 BarcodeGenerator 实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| xml文件 | java.lang.String | 文件的名称 |

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


以特定格式将 BarCodeImage 保存到流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


将条形码图像保存到指定文件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 保存路径。 |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


将条形码图像以特定格式保存到指定文件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 保存路径。 |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | 指定输出图像的文件格式。 |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


条形码符号类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


将 codetext 设置为字节序列。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| codeBytes | byte[] | codetext 的字节 |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


要编码的文本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


使用指定的 **encoding** 将 Unicode **codeText** 编码为字节序列。UTF-8 是最常用的编码。如果该编码支持，函数会自动插入一个 [byte order mark (BOM)][byte order mark _BOM]。

此函数仅用于 2D 条码（例如 Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR 等）。它允许使用国家或特殊编码对 Unicode 文本进行手动编码；但在现代应用中此方法已被视为过时。对于现代使用场景，建议使用 [ECI][] 编码来处理 Unicode 数据。

在 1D 条码、符合 GS1 标准的条码（包括 2D）或 HIBC 条码（包括 2D）中使用此函数不受相应条码标准支持，可能导致不可预期的结果。

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| codeText | java.lang.String | CodeText 字符串 |
| 编码 | java.nio.charset.Charset | 使用的编码 |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


使用指定的 **encoding** 将 Unicode **codeText** 编码为字节序列。UTF-8 是最常用的编码。如果该编码支持且 **insertBOM** 设置为 true，函数会在结果中包含一个 [byte order mark (BOM)][byte order mark _BOM]。

此函数仅用于 2D 条码（例如 Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR 等）。它允许使用国家或特殊编码对 Unicode 文本进行手动编码；但在现代应用中此方法已被视为过时。对于现代使用场景，建议使用 [ECI][] 编码来处理 Unicode 数据。

在 1D 条码、符合 GS1 标准的条码（包括 2D）或 HIBC 条码（包括 2D）中使用此函数不受相应条码标准支持，可能导致不可预期的结果。

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| codeText | java.lang.String | CodeText 字符串 |
| 编码 | java.nio.charset.Charset | 使用的编码 |
| insertBOM | boolean | 指示在指定的编码支持时是否插入字节顺序标记（BOM）（例如 UTF-8、UTF-16、UTF-32）。如果设置为 true，则添加 BOM；如果设置为 false，则即使编码通常使用 BOM 也会省略。 |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

