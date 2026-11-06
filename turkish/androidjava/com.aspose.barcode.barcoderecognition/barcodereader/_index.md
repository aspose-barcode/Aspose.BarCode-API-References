---
title: "BarCodeReader"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "BarCodeReader, bir veya birkaç barkod içerebilecek bir görüntüyü kapsar ve ardından barkodları tespit etmek için ReadBarCodes işlemini gerçekleştirebilir."
type: docs
weight: 14
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/barcodereader/
---
**Inheritance:**
java.lang.Object
```
public class BarCodeReader
```

BarCodeReader, bir veya birden fazla barkod içerebilecek bir görüntüyü kapsüller, ardından barkodları tespit etmek için ReadBarCodes işlemini gerçekleştirebilir.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BarCodeReader()](#BarCodeReader--) | BarCodeReader sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [BarCodeReader(Bitmap image)](#BarCodeReader-android.graphics.Bitmap-) | BarCodeReader sınıfının yeni bir örneğini bir görüntüden başlatır. |
| [BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes)](#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(Bitmap image, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type)](#BarCodeReader-java.lang.String-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(InputStream stream, Rect area, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(String imagePath, Rect area, BaseDecodeType type)](#BarCodeReader-java.lang.String-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(Bitmap image, Rect area, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) |  |
| [BarCodeReader(String filename)](#BarCodeReader-java.lang.String-) | BarCodeReader sınıfının yeni bir örneğini dosyadan başlatır. |
| [BarCodeReader(String filename, BaseDecodeType type)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(String filename, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(InputStream stream)](#BarCodeReader-java.io.InputStream-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(InputStream stream, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [abort()](#abort--) | Fonksiyon, başka bir iş parçacığından mevcut tanıma oturumunun sonlandırılmasını talep eder. |
| [dispose()](#dispose--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xmlStream)](#exportToXml-java.io.OutputStream-) | BarCode özelliklerini belirtilen xml akışına dışa aktarır |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | BarCode özelliklerini belirtilen xml dosyasına dışa aktarır |
| [getBarCodeReadType()](#getBarCodeReadType--) | Giriş barkodunun kod çözme türünü alır |
| [getBarcodeSettings()](#getBarcodeSettings--) | Ana BarCode kod çözme parametreleri. |
| [getClass()](#getClass--) |  |
| [getFoundBarCodes()](#getFoundBarCodes--) | Tanımlanan BarCodeResult dizisini alır |
| [getFoundCount()](#getFoundCount--) | Tanımlanan barkodların sayısını alır |
| [getProcessorSettings()](#getProcessorSettings--) | İşlemci çekirdeklerinin kullanım ayarlarını alır. |
| [getQualitySettings()](#getQualitySettings--) | QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmaya izin verir. |
| [getTimeout()](#getTimeout--) | Tanıma işleminin zaman aşımını milisaniye cinsinden alır. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xmlStream)](#importFromXml-java.io.InputStream-) | Belirtilen xml akışından BarCode özelliklerini içe aktarır ve mevcut BarCodeReader örneğine uygular. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Belirtilen xml dosyasından BarCode özelliklerini içe aktarır ve mevcut BarCodeReader örneğine uygular. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBarCodes()](#readBarCodes--) | Görüntüden BarCodeResult'ları okur. |
| [setBarCodeImage(Bitmap value)](#setBarCodeImage-android.graphics.Bitmap-) | Tanıma için bitmap görüntüsünü ayarlar. |
| [setBarCodeImage(Bitmap value, Rect area)](#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect-) | Tanıma için bitmap görüntüsünü ve alanı ayarlar. |
| [setBarCodeImage(Bitmap value, Rect[] areas)](#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect---) | Tanıma için bitmap görüntüsünü ve alanları ayarlar. |
| [setBarCodeImage(InputStream stream)](#setBarCodeImage-java.io.InputStream-) | Tanıma için görüntü akışını ayarlar. |
| [setBarCodeImage(String filename)](#setBarCodeImage-java.lang.String-) | Tanıma için görüntü dosyasını ayarlar. |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Tanıma için kod çözme türünü ayarlar. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Tanıma için  SingleDecodeType  tipinde dizi ayarlar. |
| [setQualitySettings(QualitySettings value)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmaya izin verir. |
| [setTimeout(int value)](#setTimeout-int-) | Tanıma işleminin zaman aşımını milisaniye cinsinden ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeReader() {#BarCodeReader--}
```
public BarCodeReader()
```


Varsayılan değerlerle BarCodeReader sınıfının yeni bir örneğini başlatır. ReadBarCodes() metodunu çağırmadan önce görüntüyü (SetBitmapImage()) ayarlamanız gerekir.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage("test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

### BarCodeReader(Bitmap image) {#BarCodeReader-android.graphics.Bitmap-}
```
public BarCodeReader(Bitmap image)
```


BarCodeReader sınıfının yeni bir örneğini bir görüntüden başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
>  BarCodeReader reader = new BarCodeReader(bmp);
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | android.graphics.Bitmap | Görüntüyü içeren bir Bitmap örneği |

### BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes) {#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
>  BarCodeReader reader = new BarCodeReader(bmp, DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | android.graphics.Bitmap | Görüntü. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türleri. |

### BarCodeReader(Bitmap image, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, BaseDecodeType type)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
>  BarCodeReader reader = new BarCodeReader(bmp, new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | android.graphics.Bitmap | Görüntü. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme tür1. Tek veya çok olabilir. |

### BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | android.graphics.Bitmap | Görüntü. |
| alan | android.graphics.Rect | Tanıma için alan. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türleri. |

### BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type) {#BarCodeReader-java.lang.String-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imagePath | java.lang.String | Görüntü yolu. |
| alanlar | android.graphics.Rect[] | Tanıma için alan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türü. |

### BarCodeReader(InputStream stream, Rect area, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rect area, BaseDecodeType type)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntü akışı. |
| alan | android.graphics.Rect | Tanıma için alan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türü. |

### BarCodeReader(String imagePath, Rect area, BaseDecodeType type) {#BarCodeReader-java.lang.String-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rect area, BaseDecodeType type)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imagePath | java.lang.String | Görüntü yolu. |
| alan | android.graphics.Rect | Tanıma için alan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türü. |

### BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntü akışı. |
| alanlar | android.graphics.Rect[] | Tanıma için alan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türü. |

### BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | android.graphics.Bitmap | Görüntü. |
| alanlar | android.graphics.Rect[] | Tanıma için alanlar. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türü. |

### BarCodeReader(Bitmap image, Rect area, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, Rect area, BaseDecodeType type)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | android.graphics.Bitmap |  |
| alan | android.graphics.Rect |  |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### BarCodeReader(String filename) {#BarCodeReader-java.lang.String-}
```
public BarCodeReader(String filename)
```


BarCodeReader sınıfının yeni bir örneğini dosyadan başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("test.png");
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | java.lang.String | Dosya adı. |

### BarCodeReader(String filename, BaseDecodeType type) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String filename, BaseDecodeType type)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("test.png", new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | java.lang.String | Dosya adı. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türü. |

### BarCodeReader(String filename, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(String filename, BaseDecodeType[] decodeTypes)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | java.lang.String | Dosya adı. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türleri. |

### BarCodeReader(InputStream stream) {#BarCodeReader-java.io.InputStream-}
```
public BarCodeReader(InputStream stream)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream(new File("test.png"));
>  BarCodeReader reader = new BarCodeReader(fstr);
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |

### BarCodeReader(InputStream stream, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, BaseDecodeType type)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream("test.png");
>  BarCodeReader reader = new BarCodeReader(fstr, new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türü. |

### BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)
```


BarCodeReader sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream("test.png"));
>  BarCodeReader reader = new BarCodeReader(fstr, DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Kod çözme türleri. |

### abort() {#abort--}
```
public void abort()
```


Fonksiyon, başka bir iş parçacığından mevcut tanıma oturumunun sonlandırılmasını talep eder. Abort, engellenemeyen bir yöntemdir ve çağrıldıktan hemen sonra kontrolü geri verir. Tanıma işlemi çok uzun sürdüğünde bu yöntem kullanılmalıdır.

--------------------

> ```
> This sample shows how to call Abort function from other thread
>  
>   final BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>   Thread thread1 = new Thread(new Runnable()
>   {
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xmlStream) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xmlStream)
```


BarCode özelliklerini belirtilen xml akışına dışa aktarır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlStream | java.io.OutputStream | Kaydetme için xml-stream |

**Returns:**
boolean - Dışa aktarma başarılı bir şekilde tamamlanıp tamamlanmadığı.

Başarı durumunda  **True**  döner;  **False**  aksi takdirde
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
### getBarCodeReadType() {#getBarCodeReadType--}
```
public BaseDecodeType getBarCodeReadType()
```


Giriş barkodunun kod çözme türünü alır

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


Ana BarCode kod çözme parametreleri. Tanınan veriler üzerinde etkisi olan parametreleri içerir.

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


Tanımlanan BarCodeResult dizisini alır

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  {
>      reader.readBarCodes();
>      for(int i = 0; reader.getFoundCount() > i; ++i)
>          System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
>  }
> ```

Değer: Tanınan  BarCodeResult s dizisi

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[]
### getFoundCount() {#getFoundCount--}
```
public int getFoundCount()
```


Tanımlanan barkodların sayısını alır

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

Değer: Tanınan barkod sayısı

**Returns:**
int
### getProcessorSettings() {#getProcessorSettings--}
```
public static ProcessorSettings getProcessorSettings()
```


İşlemci çekirdeklerinin kullanım ayarlarını alır.

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


QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i yerleşik ön ayarlarla hızlıca ayarlayabilirsiniz: HighPerformance, NormalQuality, HighQuality, MaxBarCodes veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettings'in varsayılan değeri NormalQuality'dir.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //normal quality mode is set by default
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  //set separate options
>  reader.getQualitySettings().setAllowMedianSmoothing(true);
>  reader.getQualitySettings().setMedianSmoothingWindowSize(5);
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

Değer: Tanıma kalitesi ve hızını yapılandırmak için QualitySettings.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


Tanıma işleminin zaman aşımını milisaniye cinsinden alır.

```
BarCodeReader reader = new BarCodeReader("test.png");
     reader.setTimeout(5000);
     for(BarCodeResult result : reader.readBarCodes())
         System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Returns:**
int - Zaman aşımı.
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


Belirtilen xml akışından BarCode özelliklerini içe aktarır ve mevcut BarCodeReader örneğine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlStream | java.io.InputStream | Yükleme için xml akışı |

**Returns:**
[BarCodeReader](../../com.aspose.barcode.barcoderecognition/barcodereader) - Returns  **True**  in case of success;

 **False**  Otherwise
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarCodeReader importFromXml(String xmlFile)
```


Belirtilen xml dosyasından BarCode özelliklerini içe aktarır ve mevcut BarCodeReader örneğine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlFile | java.lang.String | Dosyanın adı |

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


Görüntüden BarCodeResult'ları okur.

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[] - Görüntüde tanınan  BarCodeResult s dizisini döndürür. Hiçbir şey tanınmazsa, sıfır uzunlukta bir dizi döndürülür.
### setBarCodeImage(Bitmap value) {#setBarCodeImage-android.graphics.Bitmap-}
```
public void setBarCodeImage(Bitmap value)
```


Tanıma için bitmap görüntüsü ayarlar. ReadBarCodes() metodundan önce çağrılmalıdır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | android.graphics.Bitmap | Tanıma için bitmap görüntüsü. |

### setBarCodeImage(Bitmap value, Rect area) {#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect-}
```
public final void setBarCodeImage(Bitmap value, Rect area)
```


Tanıma için bitmap görüntüsü ve alanını ayarlar. ReadBarCodes() metodundan önce çağrılmalıdır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | android.graphics.Bitmap | Tanıma için bitmap görüntüsü. |
| alan | android.graphics.Rect | tanıma alanı |

### setBarCodeImage(Bitmap value, Rect[] areas) {#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect---}
```
public final void setBarCodeImage(Bitmap value, Rect[] areas)
```


Tanıma için bitmap görüntüsü ve alanlarını ayarlar. ReadBarCodes() metodundan önce çağrılmalıdır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | android.graphics.Bitmap | Tanıma için bitmap görüntüsü. |
| alanlar | android.graphics.Rect[] | tanıma için alan listesi |

### setBarCodeImage(InputStream stream) {#setBarCodeImage-java.io.InputStream-}
```
public final void setBarCodeImage(InputStream stream)
```


Tanıma için görüntü akışını ayarlar. ReadBarCodes() metodundan önce çağrılmalıdır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream(new File("test.png"));
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Tanıma için görüntü akışı. |

### setBarCodeImage(String filename) {#setBarCodeImage-java.lang.String-}
```
public void setBarCodeImage(String filename)
```


Tanıma için görüntü dosyasını ayarlar. ReadBarCodes() metodundan önce çağrılmalıdır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader())
>  {
>      reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>      reader.setBarCodeImage("test.png");
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>      }
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | java.lang.String | Tanıma için görüntü dosyası. |

### setBarCodeReadType(BaseDecodeType type) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public void setBarCodeReadType(BaseDecodeType type)
```


Tanıma için kod çözme türünü ayarlar. ReadBarCodes() metodundan önce çağrılmalıdır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage("test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
>  System.out.println("BarCodeReadType: " + reader.getBarCodeReadType().toString());
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Okunacak barkodun türü. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


Tanıma için  SingleDecodeType  tipinde dizi ayarlar. ReadBarCodes() metodundan önce çağrılmalıdır.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage("test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Okunacak  SingleDecodeType  tipindeki dizi. |

### setQualitySettings(QualitySettings value) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public final void setQualitySettings(QualitySettings value)
```


QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i yerleşik ön ayarlarla hızlıca ayarlayabilirsiniz: HighPerformance, NormalQuality, HighQuality, MaxBarCodes veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettings'in varsayılan değeri NormalQuality'dir.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //normal quality mode is set by default
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  //set separate options
>  reader.getQualitySettings().setAllowMedianSmoothing(true);
>  reader.getQualitySettings().setMedianSmoothingWindowSize(5);
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

Değer: Tanıma kalitesi ve hızını yapılandırmak için QualitySettings.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) |  |

### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


Tanıma işleminin zaman aşımını milisaniye cinsinden ayarlar.

```
BarCodeReader reader = new BarCodeReader("test.png");
 reader.setTimeout(5000);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Zaman aşımı. |

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

