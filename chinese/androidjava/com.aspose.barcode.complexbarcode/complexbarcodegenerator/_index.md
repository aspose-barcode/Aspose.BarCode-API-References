---
title: ComplexBarcodeGenerator
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: ComplexBarcodeGenerator 用于后端复杂条码，例如
type: docs
weight: 12
url: /zh/androidjava/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator 用于后端复杂条码（例如 SwissQR）图像生成。

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
## Constructors

| Constructor | 描述 |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | 创建 ComplexBarcodeGenerator 的实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [dispose()](#dispose--) | 清理正在使用的任何资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | 在当前设置下生成复杂条码图像。 |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | 生成参数。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | 在当前设置下生成并保存复杂条码图像。 |
| [save(String filename)](#save-java.lang.String-) | 在当前设置下生成并保存复杂条码图像。 |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | 在当前设置下生成并保存复杂条码图像。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


创建 ComplexBarcodeGenerator 的实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | 复杂代码文本 |

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
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


在当前设置下生成复杂条码图像。

**Returns:**
android.graphics.Bitmap - 条码图像。参见 Bitmap。
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


生成参数。

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


在当前设置下生成并保存复杂条码图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出 System.IO.Stream。 |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | 指定输出图像的文件格式。 |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


在当前设置下生成并保存复杂条码图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 保存路径。 |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


在当前设置下生成并保存复杂条码图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 保存路径。 |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | 指定输出图像的文件格式。 |

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

