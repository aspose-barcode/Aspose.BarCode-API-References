---
title: BarcodeGenerator
second_title: Aspose.BarCode for Java API Reference
description: BarcodeGenerator for backend barcode images generation.
type: docs
weight: 13
url: /java/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator for backend barcode images generation.

supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | Creates an instance of BarcodeGenerator. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | Creates an instance of BarcodeGenerator. |
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Clean up any resources being used. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | Exports BarCode properties to the xml-stream specified |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Exports BarCode properties to the xml-file specified |
| [generateBarCodeImage()](#generateBarCodeImage--) | Generate the barcode image under current settings. |
| [getBarcodeType()](#getBarcodeType--) | Barcode symbology type. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Text to be encoded. |
| [getParameters()](#getParameters--) | Generation parameters. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Imports BarCode properties from the xml-stream specified and creates BarcodeGenerator instance. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Imports BarCode properties from the xml-file specified and creates BarcodeGenerator instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Save barcode image to stream in specific format. |
| [save(String filename)](#save-java.lang.String-) | Save barcode image to specific file. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Save barcode image to specific file in specific format. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Barcode symbology type. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | Set codetext as sequence of bytes. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Text to be encoded. |
| [setCodeText(String codeText, Charset encoding)](#setCodeText-java.lang.String-java.nio.charset.Charset-) | Encodes codetext with byte order mark (BOM) using specified encoding. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeGenerator(BaseEncodeType type) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-}
```
public BarcodeGenerator(BaseEncodeType type)
```


Creates an instance of BarcodeGenerator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Barcode symbology type. Use  EncodeTypes  class to setup a symbology. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


Creates an instance of BarcodeGenerator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Barcode symbology type. Use  EncodeTypes  class to setup a symbology. |
| codeText | java.lang.String | Text to be encoded. |

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


Exports BarCode properties to the xml-stream specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xml | java.io.OutputStream | The xml-stream |

**Returns:**
boolean - Whether or not export completed successfully. Returns **True** in case of success; **False** Otherwise
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Exports BarCode properties to the xml-file specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | java.lang.String | The name of the file |

**Returns:**
boolean - Whether or not export completed successfully.

Returns  **True**  in case of success;  **False**  Otherwise
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


Generate the barcode image under current settings.

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          File outputFile = new File("test.png");
>          BufferedImage image = generator.generateBarCodeImage();
>          ImageIO.write(image, "png",outputFile);
> ```

**Returns:**
java.awt.image.BufferedImage - Barcode image. See  Bitmap .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Barcode symbology type.

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


Text to be encoded.

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


Imports BarCode properties from the xml-stream specified and creates BarcodeGenerator instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xml | java.io.InputStream | The xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Imports BarCode properties from the xml-file specified and creates BarcodeGenerator instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | java.lang.String | The name of the file |

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


Save barcode image to stream in specific format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output OutputStream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specifies the file format of the output image. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Save barcode image to specific file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Path to save to. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Save barcode image to specific file in specific format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Path to save to. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specifies the file format of the output image. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Barcode symbology type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


Set codetext as sequence of bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codeBytes | byte[] | Bytes of codetext |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Text to be encoded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Encodes codetext with byte order mark (BOM) using specified encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codeText | java.lang.String | CodeText string |
| encoding | java.nio.charset.Charset | Applied encoding |

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

