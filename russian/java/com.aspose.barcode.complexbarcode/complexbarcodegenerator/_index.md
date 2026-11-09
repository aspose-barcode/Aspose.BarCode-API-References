---
title: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for Java API Reference"
description: "ComplexBarcodeGenerator для серверных сложных штрихкодов, например."
type: docs
weight: 12
url: /ru/java/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator для генерации изображений сложных штрихкодов на сервере (например, SwissQR).

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | Создает экземпляр ComplexBarcodeGenerator. |
## Методы

| Метод | Описание |
| --- | --- |
| [dispose()](#dispose--) | Очистите любые используемые ресурсы. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | Создает изображение сложного штрихкода с текущими настройками. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | Параметры генерации. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Создает и сохраняет изображение сложного штрихкода с текущими настройками. |
| [save(String filename)](#save-java.lang.String-) | Создает и сохраняет изображение сложного штрихкода с текущими настройками. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Создает и сохраняет изображение сложного штрихкода с текущими настройками. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


Создает экземпляр ComplexBarcodeGenerator.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | Сложный кодтекст |

### dispose() {#dispose--}
```
public void dispose()
```


Очистите любые используемые ресурсы.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


Создает изображение сложного штрихкода с текущими настройками.

**Returns:**
java.awt.image.BufferedImage - изображение штрихкода. См. Bitmap.
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


Параметры генерации.

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


Создает и сохраняет изображение сложного штрихкода с текущими настройками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | java.io.OutputStream | Вывод System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Указывает формат файла выходного изображения. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Создает и сохраняет изображение сложного штрихкода с текущими настройками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Путь для сохранения. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Создает и сохраняет изображение сложного штрихкода с текущими настройками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Путь для сохранения. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Указывает формат файла выходного изображения. |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

