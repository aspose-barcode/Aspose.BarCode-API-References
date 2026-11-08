---
title: "ComplexBarcodeGenerator"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "ComplexBarcodeGenerator للباركود المعقد في الخلفية مثلاً"
type: docs
weight: 12
url: /ar/java/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator لتوليد صور الباركود المعقد في الخلفية (مثلاً SwissQR).

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
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | إنشاء نسخة من ComplexBarcodeGenerator. |
## الدوال

| دالة | الوصف |
| --- | --- |
| [dispose()](#dispose--) | تنظيف أي موارد قيد الاستخدام. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | إنشاء صورة باركود معقدة وفقًا للإعدادات الحالية. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | معلمات الإنشاء. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | إنشاء وحفظ صورة باركود معقدة وفقًا للإعدادات الحالية. |
| [save(String filename)](#save-java.lang.String-) | إنشاء وحفظ صورة باركود معقدة وفقًا للإعدادات الحالية. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | إنشاء وحفظ صورة باركود معقدة وفقًا للإعدادات الحالية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


إنشاء نسخة من ComplexBarcodeGenerator.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | نص الترميز المعقد |

### dispose() {#dispose--}
```
public void dispose()
```


تنظيف أي موارد قيد الاستخدام.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


إنشاء صورة باركود معقدة وفقًا للإعدادات الحالية.

**Returns:**
java.awt.image.BufferedImage - صورة الباركود. انظر Bitmap.
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


معلمات الإنشاء.

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


إنشاء وحفظ صورة باركود معقدة وفقًا للإعدادات الحالية.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| دفق | java.io.OutputStream | الإخراج System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | تحديد تنسيق ملف الصورة الناتجة. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


إنشاء وحفظ صورة باركود معقدة وفقًا للإعدادات الحالية.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| اسم الملف | java.lang.String | المسار للحفظ فيه. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


إنشاء وحفظ صورة باركود معقدة وفقًا للإعدادات الحالية.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| اسم الملف | java.lang.String | المسار للحفظ فيه. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | تحديد تنسيق ملف الصورة الناتجة. |

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
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

