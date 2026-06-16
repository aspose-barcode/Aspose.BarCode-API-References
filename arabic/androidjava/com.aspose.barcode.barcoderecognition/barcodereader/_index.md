---
title: BarCodeReader
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: BarCodeReader يضم صورة قد تحتوي على باركود واحد أو عدة باركودات، ثم يمكنه تنفيذ عملية ReadBarCodes لاكتشاف الباركودات.
type: docs
weight: 15
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/barcodereader/
---
**Inheritance:**
java.lang.Object
```
public class BarCodeReader
```

BarCodeReader يضم صورة قد تحتوي على باركود واحد أو عدة باركودات، ثم يمكنه تنفيذ عملية ReadBarCodes لاكتشاف الباركودات.

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
## Constructors

| Constructor | الوصف |
| --- | --- |
| [BarCodeReader()](#BarCodeReader--) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader  بالقيم الافتراضية. |
| [BarCodeReader(Bitmap image)](#BarCodeReader-android.graphics.Bitmap-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader  من صورة. |
| [BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes)](#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(Bitmap image, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type)](#BarCodeReader-java.lang.String-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(InputStream stream, Rect area, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(String imagePath, Rect area, BaseDecodeType type)](#BarCodeReader-java.lang.String-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(Bitmap image, Rect area, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) |  |
| [BarCodeReader(String filename)](#BarCodeReader-java.lang.String-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader  من ملف. |
| [BarCodeReader(String filename, BaseDecodeType type)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(String filename, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(InputStream stream)](#BarCodeReader-java.io.InputStream-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(InputStream stream, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
| [BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | ينشئ مثيلاً جديداً من الفئة  BarCodeReader . |
## Methods

| Method | الوصف |
| --- | --- |
| [abort()](#abort--) | الدالة تطلب إنهاء جلسة التعرف الحالية من خيط آخر. |
| [dispose()](#dispose--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xmlStream)](#exportToXml-java.io.OutputStream-) | يصدّر خصائص BarCode إلى xml-stream المحدد |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | يصدّر خصائص BarCode إلى xml-file المحدد |
| [getBarCodeReadType()](#getBarCodeReadType--) | يحصل على نوع فك الترميز للباركود المدخل |
| [getBarcodeSettings()](#getBarcodeSettings--) | معلمات فك ترميز BarCode الرئيسية. |
| [getClass()](#getClass--) |  |
| [getFoundBarCodes()](#getFoundBarCodes--) | يحصل على مصفوفة BarCodeResult المعترف بها |
| [getFoundCount()](#getFoundCount--) | يحصل على عدد الباركودات المعترف بها |
| [getProcessorSettings()](#getProcessorSettings--) | يحصل على إعدادات استخدام نوى المعالج. |
| [getQualitySettings()](#getQualitySettings--) | تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. |
| [getTimeout()](#getTimeout--) | يحصل على مهلة عملية التعرف بالمللي ثانية. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xmlStream)](#importFromXml-java.io.InputStream-) | يستورد خصائص BarCode من تدفق xml المحدد ويطبقها على نسخة BarCodeReader الحالية. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | يستورد خصائص BarCode من ملف XML المحدد ويطبقها على كائن BarCodeReader الحالي. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBarCodes()](#readBarCodes--) | يقرأ BarCodeResult s من الصورة. |
| [setBarCodeImage(Bitmap value)](#setBarCodeImage-android.graphics.Bitmap-) | يضبط صورة bitmap للتعرف. |
| [setBarCodeImage(Bitmap value, Rect area)](#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect-) | يضبط صورة bitmap والمنطقة للتعرف. |
| [setBarCodeImage(Bitmap value, Rect[] areas)](#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect---) | يضبط صورة bitmap والمناطق للتعرف. |
| [setBarCodeImage(InputStream stream)](#setBarCodeImage-java.io.InputStream-) | يضبط تدفق الصورة للتعرف. |
| [setBarCodeImage(String filename)](#setBarCodeImage-java.lang.String-) | يضبط ملف الصورة للتعرف. |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | يضبط نوع فك الترميز للتعرف. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | يضبط مصفوفة النوع SingleDecodeType للتعرف. |
| [setQualitySettings(QualitySettings value)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. |
| [setTimeout(int value)](#setTimeout-int-) | يضبط مهلة عملية التعرف بالمللي ثانية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeReader() {#BarCodeReader--}
```
public BarCodeReader()
```


ينشئ مثيلاً جديداً من فئة BarCodeReader بالقيم الافتراضية. يتطلب ضبط الصورة (SetBitmapImage()) قبل استدعاء طريقة ReadBarCodes().

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


ينشئ مثيلاً جديداً من الفئة  BarCodeReader  من صورة.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| صورة | android.graphics.Bitmap | كائن Bitmap يحتوي على الصورة |

### BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes) {#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| صورة | android.graphics.Bitmap | الصورة. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | أنواع فك الترميز. |

### BarCodeReader(Bitmap image, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, BaseDecodeType type)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| صورة | android.graphics.Bitmap | الصورة. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | نوع type1. يمكن أن يكون مفردًا أو متعددًا |

### BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| صورة | android.graphics.Bitmap | الصورة. |
| منطقة | android.graphics.Rect | المنطقة للتعرف. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | أنواع فك الترميز. |

### BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type) {#BarCodeReader-java.lang.String-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| imagePath | java.lang.String | مسار الصورة. |
| مناطق | android.graphics.Rect[] | المنطقة للتعرف. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | نوع فك الترميز. |

### BarCodeReader(InputStream stream, Rect area, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rect area, BaseDecodeType type)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | تدفق الصورة. |
| منطقة | android.graphics.Rect | المنطقة للتعرف. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | نوع فك الترميز. |

### BarCodeReader(String imagePath, Rect area, BaseDecodeType type) {#BarCodeReader-java.lang.String-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rect area, BaseDecodeType type)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| imagePath | java.lang.String | مسار الصورة. |
| منطقة | android.graphics.Rect | المنطقة للتعرف. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | نوع فك الترميز. |

### BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | تدفق الصورة. |
| مناطق | android.graphics.Rect[] | المنطقة للتعرف. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | نوع فك الترميز. |

### BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| صورة | android.graphics.Bitmap | الصورة. |
| مناطق | android.graphics.Rect[] | المناطق للتعرف. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | نوع فك الترميز. |

### BarCodeReader(Bitmap image, Rect area, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, Rect area, BaseDecodeType type)
```


**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| صورة | android.graphics.Bitmap |  |
| منطقة | android.graphics.Rect |  |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### BarCodeReader(String filename) {#BarCodeReader-java.lang.String-}
```
public BarCodeReader(String filename)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader  من ملف.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| filename | java.lang.String | The filename. |

### BarCodeReader(String filename, BaseDecodeType type) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String filename, BaseDecodeType type)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| filename | java.lang.String | The filename. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | نوع فك الترميز. |

### BarCodeReader(String filename, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(String filename, BaseDecodeType[] decodeTypes)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| filename | java.lang.String | The filename. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | أنواع فك الترميز. |

### BarCodeReader(InputStream stream) {#BarCodeReader-java.io.InputStream-}
```
public BarCodeReader(InputStream stream)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | The stream. |

### BarCodeReader(InputStream stream, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, BaseDecodeType type)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | The stream. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | نوع فك الترميز. |

### BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)
```


ينشئ مثيلاً جديداً من الفئة  BarCodeReader .

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | The stream. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | أنواع فك الترميز. |

### abort() {#abort--}
```
public void abort()
```


Function requests termination of current recognition session from other thread. Abort is unblockable method and returns control just after calling. The method should be used when recognition process is too long.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xmlStream) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xmlStream)
```


يصدّر خصائص BarCode إلى xml-stream المحدد

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| xmlStream | java.io.OutputStream | The xml-stream for saving |

**Returns:**
boolean - Whether or not export completed successfully.

Returns  **True**  in case of success;  **False**  Otherwise
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


يصدّر خصائص BarCode إلى xml-file المحدد

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| xmlFile | java.lang.String | The name of the file |

**Returns:**
boolean - Whether or not export completed successfully.

Returns  **True**  in case of success;  **False**  Otherwise
### getBarCodeReadType() {#getBarCodeReadType--}
```
public BaseDecodeType getBarCodeReadType()
```


يحصل على نوع فك الترميز للباركود المدخل

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


معلمات فك ترميز BarCode الرئيسية. تحتوي على معلمات تؤثر على البيانات المُعترف بها.

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


يحصل على مصفوفة BarCodeResult المعترف بها

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

Value: The recognized  BarCodeResult s array

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[]
### getFoundCount() {#getFoundCount--}
```
public int getFoundCount()
```


يحصل على عدد الباركودات المعترف بها

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

Value: The recognized barcodes count

**Returns:**
int
### getProcessorSettings() {#getProcessorSettings--}
```
public static ProcessorSettings getProcessorSettings()
```


يحصل على إعدادات استخدام نوى المعالج.

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


تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. يمكنك إعداد QualitySettings بسرعة باستخدام الإعدادات المدمجة: HighPerformance، NormalQuality، HighQuality، MaxBarCodes أو يمكنك تكوين الخيارات بشكل منفصل يدويًا. القيمة الافتراضية لـ QualitySettings هي NormalQuality.

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

Value: QualitySettings to configure recognition quality and speed.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


يحصل على مهلة عملية التعرف بالمللي ثانية.

```
BarCodeReader reader = new BarCodeReader("test.png");
     reader.setTimeout(5000);
     for(BarCodeResult result : reader.readBarCodes())
         System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Returns:**
int - The timeout.
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


يستورد خصائص BarCode من تدفق xml المحدد ويطبقها على نسخة BarCodeReader الحالية.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| xmlStream | java.io.InputStream | تدفق xml للتحميل |

**Returns:**
[BarCodeReader](../../com.aspose.barcode.barcoderecognition/barcodereader) - Returns  **True**  in case of success;

 **False**  Otherwise
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarCodeReader importFromXml(String xmlFile)
```


يستورد خصائص BarCode من ملف XML المحدد ويطبقها على كائن BarCodeReader الحالي.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| xmlFile | java.lang.String | The name of the file |

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


يقرأ BarCodeResult s من الصورة.

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
com.aspose.barcode.barcoderecognition.BarCodeResult[] - Returns array of recognized  BarCodeResult s on the image. If nothing is recognized, zero array is returned.
### setBarCodeImage(Bitmap value) {#setBarCodeImage-android.graphics.Bitmap-}
```
public void setBarCodeImage(Bitmap value)
```


Sets bitmap image for recognition. Must be called before ReadBarCodes() method.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | android.graphics.Bitmap | The bitmap image for recognition. |

### setBarCodeImage(Bitmap value, Rect area) {#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect-}
```
public final void setBarCodeImage(Bitmap value, Rect area)
```


Sets bitmap image and area for recognition. Must be called before ReadBarCodes() method.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | android.graphics.Bitmap | The bitmap image for recognition. |
| منطقة | android.graphics.Rect | area for recognition |

### setBarCodeImage(Bitmap value, Rect[] areas) {#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect---}
```
public final void setBarCodeImage(Bitmap value, Rect[] areas)
```


Sets bitmap image and areas for recognition. Must be called before ReadBarCodes() method.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | android.graphics.Bitmap | The bitmap image for recognition. |
| مناطق | android.graphics.Rect[] | areas list for recognition |

### setBarCodeImage(InputStream stream) {#setBarCodeImage-java.io.InputStream-}
```
public final void setBarCodeImage(InputStream stream)
```


Sets image stream for recognition. Must be called before ReadBarCodes() method.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | The image stream for recogniton. |

### setBarCodeImage(String filename) {#setBarCodeImage-java.lang.String-}
```
public void setBarCodeImage(String filename)
```


يضبط ملف الصورة للتعرف. يجب استدعاؤه قبل طريقة ReadBarCodes().

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| filename | java.lang.String | ملف الصورة للتعرف. |

### setBarCodeReadType(BaseDecodeType type) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public void setBarCodeReadType(BaseDecodeType type)
```


يضبط نوع فك الترميز للتعرف. يجب استدعاؤه قبل طريقة ReadBarCodes().

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | نوع الباركود الذي سيتم قراءته. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


يضبط مصفوفة النوع SingleDecodeType للتعرف. يجب استدعاؤه قبل طريقة ReadBarCodes().

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | مصفوفة النوع SingleDecodeType للقراءة. |

### setQualitySettings(QualitySettings value) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public final void setQualitySettings(QualitySettings value)
```


تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. يمكنك إعداد QualitySettings بسرعة باستخدام الإعدادات المدمجة: HighPerformance، NormalQuality، HighQuality، MaxBarCodes أو يمكنك تكوين الخيارات بشكل منفصل يدويًا. القيمة الافتراضية لـ QualitySettings هي NormalQuality.

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

Value: QualitySettings to configure recognition quality and speed.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) |  |

### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


يضبط مهلة عملية التعرف بالمللي ثانية.

```
BarCodeReader reader = new BarCodeReader("test.png");
 reader.setTimeout(5000);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int | مهلة الوقت. |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

