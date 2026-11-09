---
title: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Arka uç karmaşık barkodları için ComplexBarcodeGenerator örn."
type: docs
weight: 12
url: /tr/java/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

Arka uç karmaşık barkod (örn. SwissQR) görüntü üretimi için ComplexBarcodeGenerator.

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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | ComplexBarcodeGenerator sınıfının bir örneğini oluşturur. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [dispose()](#dispose--) | Kullanılan tüm kaynakları temizleyin. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | Oluşturma parametreleri. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |
| [save(String filename)](#save-java.lang.String-) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


ComplexBarcodeGenerator sınıfının bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | Karmaşık kod metni |

### dispose() {#dispose--}
```
public void dispose()
```


Kullanılan tüm kaynakları temizleyin.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur.

**Returns:**
java.awt.image.BufferedImage - Barkod görüntüsü. Bakınız Bitmap.
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


Oluşturma parametreleri.

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


Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Çıktı System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Çıktı görüntüsünün dosya formatını belirtir. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | java.lang.String | Kaydedilecek yol. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | java.lang.String | Kaydedilecek yol. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Çıktı görüntüsünün dosya formatını belirtir. |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

