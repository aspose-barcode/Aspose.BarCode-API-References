---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Arka uç barkod görüntüsü oluşturma için BarcodeGenerator."
type: docs
weight: 13
url: /tr/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

Arka uç barkod görüntüsü oluşturma için BarcodeGenerator.

desteklenen sembolojiler: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | BarcodeGenerator örneği oluşturur. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | BarcodeGenerator örneği oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [dispose()](#dispose--) | Kullanılan tüm kaynakları temizler. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | BarCode özelliklerini belirtilen xml akışına dışa aktarır |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | BarCode özelliklerini belirtilen xml dosyasına dışa aktarır |
| [generateBarCodeImage()](#generateBarCodeImage--) | Mevcut ayarlar altında barkod görüntüsünü oluştur. |
| [getBarcodeType()](#getBarcodeType--) | Barkod semboloji türü. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Kodlanacak metin. |
| [getParameters()](#getParameters--) | Oluşturma parametreleri. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Belirtilen xml-stream'den BarCode özelliklerini içe aktarır ve BarcodeGenerator örneği oluşturur. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Belirtilen xml-dosyasından BarCode özelliklerini içe aktarır ve BarcodeGenerator örneği oluşturur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | BarCodeImage'ı belirli bir formatta akışa kaydet. |
| [save(String filename)](#save-java.lang.String-) | Barkod görüntüsünü belirli bir dosyaya kaydet. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Barkod görüntüsünü belirli bir dosyaya belirli bir formatta kaydet. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Barkod semboloji türü. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | codetext'i bayt dizisi olarak ayarla. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Kodlanacak metin. |
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


BarcodeGenerator örneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Barkod semboloji türü. Bir semboloji ayarlamak için EncodeTypes sınıfını kullan. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


BarcodeGenerator örneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Barkod semboloji türü. Bir semboloji ayarlamak için EncodeTypes sınıfını kullan. |
| codeText | java.lang.String | Kodlanacak metin. |

### dispose() {#dispose--}
```
public void dispose()
```


Kullanılan tüm kaynakları temizler.

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
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


BarCode özelliklerini belirtilen xml akışına dışa aktarır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xml | java.io.OutputStream | XML akışı |

**Returns:**
boolean - Dışa aktarma başarılı bir şekilde tamamlandı mı. Başarılı olduğunda **True**, aksi takdirde **False** döndürür.
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


BarCode özelliklerini belirtilen xml dosyasına dışa aktarır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlFile | java.lang.String | Dosyanın adı |

**Returns:**
boolean - Dışa aktarma başarılı bir şekilde tamamlanıp tamamlanmadığı.

Başarı durumunda  **True**  döner;  **False**  aksi takdirde
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Mevcut ayarlar altında barkod görüntüsünü oluştur.

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
android.graphics.Bitmap - Barkod görüntüsü. Bkz. Bitmap.
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Barkod semboloji türü.

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


Kodlanacak metin.

**Returns:**
java.lang.String
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
### importFromXml(InputStream xml) {#importFromXml-java.io.InputStream-}
```
public static BarcodeGenerator importFromXml(InputStream xml)
```


Belirtilen xml-stream'den BarCode özelliklerini içe aktarır ve BarcodeGenerator örneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xml | java.io.InputStream | XML akışı |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Belirtilen xml-dosyasından BarCode özelliklerini içe aktarır ve BarcodeGenerator örneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlFile | java.lang.String | Dosyanın adı |

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


BarCodeImage'ı belirli bir formatta akışa kaydet.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Barkod görüntüsünü belirli bir dosyaya kaydet.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | java.lang.String | Kaydedilecek yol |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Barkod görüntüsünü belirli bir dosyaya belirli bir formatta kaydet.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | java.lang.String | Kaydedilecek yol |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Çıktı görüntünün dosya formatını belirtir. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Barkod semboloji türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


codetext'i bayt dizisi olarak ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codeBytes | byte[] | codetext baytları |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Kodlanacak metin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Belirtilen **encoding** kullanılarak Unicode **codeText**'i bir bayt dizisine kodlar. UTF-8 en yaygın kullanılan kodlamadır. Kodlama destekliyorsa, işlev otomatik olarak bir [byte order mark (BOM)][byte order mark _BOM] ekler.

Bu işlev yalnızca 2D barkodlarla (ör. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR vb.) kullanılmak üzere tasarlanmıştır. Ulusal veya özel kodlamalar kullanarak Unicode metnin manuel olarak kodlanmasını sağlar; ancak bu yöntem modern uygulamalarda eski kabul edilir. Modern kullanım durumları için Unicode verileri için [ECI][] kodlaması önerilir.

Bu işlevi 1D barkodlar, GS1 uyumlu barkodlar (2D dahil) veya HIBC barkodlar (2D dahil) ile kullanmak, ilgili barkod standartları tarafından desteklenmez ve öngörülemeyen sonuçlara yol açabilir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codeText | java.lang.String | CodeText dizesi |
| encoding | java.nio.charset.Charset | Uygulanan encoding |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Belirtilen **encoding** kullanılarak Unicode **codeText**'i bir bayt dizisine kodlar. UTF-8 en yaygın kullanılan kodlamadır. Kodlama destekliyor ve **insertBOM** true olarak ayarlanmışsa, işlev bir [byte order mark (BOM)][byte order mark _BOM] ekler.

Bu işlev yalnızca 2D barkodlarla (ör. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR vb.) kullanılmak üzere tasarlanmıştır. Ulusal veya özel kodlamalar kullanarak Unicode metnin manuel olarak kodlanmasını sağlar; ancak bu yöntem modern uygulamalarda eski kabul edilir. Modern kullanım durumları için Unicode verileri için [ECI][] kodlaması önerilir.

Bu işlevi 1D barkodlar, GS1 uyumlu barkodlar (2D dahil) veya HIBC barkodlar (2D dahil) ile kullanmak, ilgili barkod standartları tarafından desteklenmez ve öngörülemeyen sonuçlara yol açabilir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codeText | java.lang.String | CodeText dizesi |
| encoding | java.nio.charset.Charset | Uygulanan encoding |
| insertBOM | boolean | Belirtilen kodlama bunu desteklediğinde (ör. UTF-8, UTF-16, UTF-32) bir bayt sırası işareti (BOM) eklenip eklenmeyeceğini gösterir. true olarak ayarlanırsa BOM eklenir; false olarak ayarlanırsa, kodlama normalde bir BOM kullanıyorsa bile BOM atlanır. |

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

