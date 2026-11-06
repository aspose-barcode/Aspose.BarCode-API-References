---
title: "BarCodeReader"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "BarCodeReader एक छवि को समाहित करता है जिसमें एक या कई बारकोड हो सकते हैं, फिर यह बारकोड का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है।"
type: docs
weight: 14
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/barcodereader/
---
**Inheritance:**
java.lang.Object
```
public class BarCodeReader
```

BarCodeReader एक छवि को संलग्न करता है जिसमें एक या कई बारकोड हो सकते हैं, फिर वह बारकोड का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है।

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

| Constructor | विवरण |
| --- | --- |
| [BarCodeReader()](#BarCodeReader--) | डिफ़ॉल्ट मानों के साथ BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(Bitmap image)](#BarCodeReader-android.graphics.Bitmap-) | एक छवि से BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes)](#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(Bitmap image, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type)](#BarCodeReader-java.lang.String-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(InputStream stream, Rect area, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(String imagePath, Rect area, BaseDecodeType type)](#BarCodeReader-java.lang.String-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(Bitmap image, Rect area, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) |  |
| [BarCodeReader(String filename)](#BarCodeReader-java.lang.String-) | फ़ाइल से BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(String filename, BaseDecodeType type)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(String filename, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(InputStream stream)](#BarCodeReader-java.io.InputStream-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(InputStream stream, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
| [BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [abort()](#abort--) | फ़ंक्शन अन्य थ्रेड से वर्तमान पहचान सत्र को समाप्त करने का अनुरोध करता है। |
| [dispose()](#dispose--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xmlStream)](#exportToXml-java.io.OutputStream-) | निर्दिष्ट xml-stream में BarCode गुण निर्यात करता है |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | निर्दिष्ट xml-file में BarCode गुण निर्यात करता है |
| [getBarCodeReadType()](#getBarCodeReadType--) | इनपुट बारकोड डिकोडिंग का डिकोड प्रकार प्राप्त करता है |
| [getBarcodeSettings()](#getBarcodeSettings--) | मुख्य BarCode डिकोडिंग पैरामीटर। |
| [getClass()](#getClass--) |  |
| [getFoundBarCodes()](#getFoundBarCodes--) | पहचाने गए BarCodeResult एरे प्राप्त करता है |
| [getFoundCount()](#getFoundCount--) | पहचाने गए बारकोड की संख्या प्राप्त करता है |
| [getProcessorSettings()](#getProcessorSettings--) | प्रोसेसर कोर के उपयोग की सेटिंग प्राप्त करता है। |
| [getQualitySettings()](#getQualitySettings--) | QualitySettings मैन्युअल रूप से पहचान गुणवत्ता और गति को कॉन्फ़िगर करने की अनुमति देता है। |
| [getTimeout()](#getTimeout--) | मिलीसेकंड में पहचान प्रक्रिया का टाइमआउट प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xmlStream)](#importFromXml-java.io.InputStream-) | निर्दिष्ट xml-स्ट्रीम से BarCode गुण आयात करता है और उन्हें वर्तमान BarCodeReader इंस्टेंस पर लागू करता है। |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | निर्दिष्ट xml-file से BarCode गुण आयात करता है और उन्हें वर्तमान BarCodeReader उदाहरण पर लागू करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBarCodes()](#readBarCodes--) | छवि से BarCodeResult पढ़ता है। |
| [setBarCodeImage(Bitmap value)](#setBarCodeImage-android.graphics.Bitmap-) | पहचान के लिए bitmap छवि सेट करता है। |
| [setBarCodeImage(Bitmap value, Rect area)](#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect-) | पहचान के लिए bitmap छवि और क्षेत्र सेट करता है। |
| [setBarCodeImage(Bitmap value, Rect[] areas)](#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect---) | पहचान के लिए bitmap छवि और क्षेत्रों को सेट करता है। |
| [setBarCodeImage(InputStream stream)](#setBarCodeImage-java.io.InputStream-) | पहचान के लिए इमेज स्ट्रीम सेट करता है। |
| [setBarCodeImage(String filename)](#setBarCodeImage-java.lang.String-) | पहचान के लिए इमेज फ़ाइल सेट करता है। |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | पहचान के लिए डिकोड प्रकार सेट करता है। |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | पहचान के लिए  SingleDecodeType  प्रकार की एरे सेट करता है। |
| [setQualitySettings(QualitySettings value)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings मैन्युअल रूप से पहचान गुणवत्ता और गति को कॉन्फ़िगर करने की अनुमति देता है। |
| [setTimeout(int value)](#setTimeout-int-) | पहचान प्रक्रिया का टाइमआउट मिलीसेकंड में सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeReader() {#BarCodeReader--}
```
public BarCodeReader()
```


डिफ़ॉल्ट मानों के साथ BarCodeReader क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। ReadBarCodes() मेथड को कॉल करने से पहले इमेज (SetBitmapImage()) सेट करना आवश्यक है।

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


एक छवि से BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| इमेज | android.graphics.Bitmap | इमेज को समाहित करने वाला Bitmap इंस्टेंस |

### BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes) {#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| इमेज | android.graphics.Bitmap | इमेज। |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड प्रकार। |

### BarCodeReader(Bitmap image, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, BaseDecodeType type)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| इमेज | android.graphics.Bitmap | इमेज। |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड टाइप1। यह एकल या बहु हो सकता है। |

### BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| इमेज | android.graphics.Bitmap | इमेज। |
| क्षेत्र | android.graphics.Rect | पहचान के लिए क्षेत्र। |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड प्रकार। |

### BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type) {#BarCodeReader-java.lang.String-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| imagePath | java.lang.String | इमेज पाथ। |
| areas | android.graphics.Rect[] | पहचान के लिए क्षेत्र। |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड टाइप। |

### BarCodeReader(InputStream stream, Rect area, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rect area, BaseDecodeType type)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इमेज स्ट्रीम। |
| क्षेत्र | android.graphics.Rect | पहचान के लिए क्षेत्र। |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड टाइप। |

### BarCodeReader(String imagePath, Rect area, BaseDecodeType type) {#BarCodeReader-java.lang.String-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rect area, BaseDecodeType type)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| imagePath | java.lang.String | इमेज पाथ। |
| क्षेत्र | android.graphics.Rect | पहचान के लिए क्षेत्र। |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड टाइप। |

### BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इमेज स्ट्रीम। |
| areas | android.graphics.Rect[] | पहचान के लिए क्षेत्र। |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड टाइप। |

### BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| इमेज | android.graphics.Bitmap | इमेज। |
| areas | android.graphics.Rect[] | पहचान के लिए क्षेत्रों। |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड टाइप। |

### BarCodeReader(Bitmap image, Rect area, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, Rect area, BaseDecodeType type)
```


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| इमेज | android.graphics.Bitmap |  |
| क्षेत्र | android.graphics.Rect |  |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### BarCodeReader(String filename) {#BarCodeReader-java.lang.String-}
```
public BarCodeReader(String filename)
```


फ़ाइल से BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| filename | java.lang.String | फ़ाइलनाम। |

### BarCodeReader(String filename, BaseDecodeType type) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String filename, BaseDecodeType type)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| filename | java.lang.String | फ़ाइलनाम। |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड टाइप। |

### BarCodeReader(String filename, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(String filename, BaseDecodeType[] decodeTypes)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| filename | java.lang.String | फ़ाइलनाम। |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड प्रकार। |

### BarCodeReader(InputStream stream) {#BarCodeReader-java.io.InputStream-}
```
public BarCodeReader(InputStream stream)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | स्ट्रीम। |

### BarCodeReader(InputStream stream, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, BaseDecodeType type)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | स्ट्रीम। |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड टाइप। |

### BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)
```


BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | स्ट्रीम। |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड प्रकार। |

### abort() {#abort--}
```
public void abort()
```


फ़ंक्शन अन्य थ्रेड से वर्तमान पहचान सत्र को समाप्त करने का अनुरोध करता है। Abort एक अनब्लॉक करने योग्य मेथड है और कॉल करने के तुरंत बाद नियंत्रण लौटाता है। जब पहचान प्रक्रिया बहुत लंबी हो तो इस मेथड का उपयोग किया जाना चाहिए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xmlStream) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xmlStream)
```


निर्दिष्ट xml-stream में BarCode गुण निर्यात करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| xmlStream | java.io.OutputStream | सेव करने के लिए xml-स्ट्रीम। |

**Returns:**
boolean - क्या निर्यात सफलतापूर्वक पूरा हुआ या नहीं।

सफलता की स्थिति में  **True**  लौटाता है; अन्यथा  **False**
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


निर्दिष्ट xml-file में BarCode गुण निर्यात करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| xmlFile | java.lang.String | फ़ाइल का नाम |

**Returns:**
boolean - क्या निर्यात सफलतापूर्वक पूरा हुआ या नहीं।

सफलता की स्थिति में  **True**  लौटाता है; अन्यथा  **False**
### getBarCodeReadType() {#getBarCodeReadType--}
```
public BaseDecodeType getBarCodeReadType()
```


इनपुट बारकोड डिकोडिंग का डिकोड प्रकार प्राप्त करता है

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


मुख्य BarCode डिकोडिंग पैरामीटर। इसमें ऐसे पैरामीटर शामिल हैं जो पहचाने गए डेटा पर प्रभाव डालते हैं।

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


पहचाने गए BarCodeResult एरे प्राप्त करता है

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

मान: पहचाने गए  BarCodeResult s एरे

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[]
### getFoundCount() {#getFoundCount--}
```
public int getFoundCount()
```


पहचाने गए बारकोड की संख्या प्राप्त करता है

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

मान: पहचाने गए बारकोड की गिनती

**Returns:**
int
### getProcessorSettings() {#getProcessorSettings--}
```
public static ProcessorSettings getProcessorSettings()
```


प्रोसेसर कोर के उपयोग की सेटिंग प्राप्त करता है।

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


QualitySettings आपको पहचान की गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxBarCodes का उपयोग करके जल्दी से QualitySettings सेट कर सकते हैं या आप मैन्युअल रूप से अलग विकल्पों को कॉन्फ़िगर कर सकते हैं। QualitySettings का डिफ़ॉल्ट मान NormalQuality है।

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

मान: पहचान की गुणवत्ता और गति को कॉन्फ़िगर करने के लिए QualitySettings।

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


मिलीसेकंड में पहचान प्रक्रिया का टाइमआउट प्राप्त करता है।

```
BarCodeReader reader = new BarCodeReader("test.png");
     reader.setTimeout(5000);
     for(BarCodeResult result : reader.readBarCodes())
         System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Returns:**
int - टाइमआउट।
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


निर्दिष्ट xml-स्ट्रीम से BarCode गुण आयात करता है और उन्हें वर्तमान BarCodeReader इंस्टेंस पर लागू करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| xmlStream | java.io.InputStream | लोड करने के लिए xml-स्ट्रीम |

**Returns:**
[BarCodeReader](../../com.aspose.barcode.barcoderecognition/barcodereader) - Returns  **True**  in case of success;

 **False**  Otherwise
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarCodeReader importFromXml(String xmlFile)
```


निर्दिष्ट xml-file से BarCode गुण आयात करता है और उन्हें वर्तमान BarCodeReader उदाहरण पर लागू करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| xmlFile | java.lang.String | फ़ाइल का नाम |

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


छवि से BarCodeResult पढ़ता है।

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
com.aspose.barcode.barcoderecognition.BarCodeResult[] - छवि पर पहचाने गए  BarCodeResult s का एरे लौटाता है। यदि कुछ नहीं पहचाना जाता, तो शून्य एरे लौटाया जाता है।
### setBarCodeImage(Bitmap value) {#setBarCodeImage-android.graphics.Bitmap-}
```
public void setBarCodeImage(Bitmap value)
```


पहचान के लिए बिटमैप इमेज सेट करता है। इसे **ReadBarCodes()** मेथड से पहले कॉल किया जाना चाहिए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | android.graphics.Bitmap | पहचान के लिए बिटमैप इमेज। |

### setBarCodeImage(Bitmap value, Rect area) {#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect-}
```
public final void setBarCodeImage(Bitmap value, Rect area)
```


पहचान के लिए बिटमैप इमेज और क्षेत्र सेट करता है। इसे **ReadBarCodes()** मेथड से पहले कॉल किया जाना चाहिए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | android.graphics.Bitmap | पहचान के लिए बिटमैप इमेज। |
| क्षेत्र | android.graphics.Rect | पहचान के लिए क्षेत्र |

### setBarCodeImage(Bitmap value, Rect[] areas) {#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect---}
```
public final void setBarCodeImage(Bitmap value, Rect[] areas)
```


पहचान के लिए बिटमैप इमेज और क्षेत्रों को सेट करता है। इसे **ReadBarCodes()** मेथड से पहले कॉल किया जाना चाहिए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | android.graphics.Bitmap | पहचान के लिए बिटमैप इमेज। |
| areas | android.graphics.Rect[] | पहचान के लिए क्षेत्रों की सूची |

### setBarCodeImage(InputStream stream) {#setBarCodeImage-java.io.InputStream-}
```
public final void setBarCodeImage(InputStream stream)
```


पहचान के लिए इमेज स्ट्रीम सेट करता है। इसे **ReadBarCodes()** मेथड से पहले कॉल किया जाना चाहिए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | पहचान के लिए इमेज स्ट्रीम। |

### setBarCodeImage(String filename) {#setBarCodeImage-java.lang.String-}
```
public void setBarCodeImage(String filename)
```


पहचान के लिए इमेज फ़ाइल सेट करता है। इसे **ReadBarCodes()** मेथड से पहले कॉल किया जाना चाहिए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| filename | java.lang.String | पहचान के लिए इमेज फ़ाइल। |

### setBarCodeReadType(BaseDecodeType type) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public void setBarCodeReadType(BaseDecodeType type)
```


पहचान के लिए डिकोड प्रकार सेट करता है। इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | पढ़ने के लिए बारकोड का प्रकार। |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


पहचान के लिए  SingleDecodeType  प्रकार का एरे सेट करता है। इसे **ReadBarCodes()** मेथड से पहले कॉल किया जाना चाहिए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | पढ़ने के लिए  SingleDecodeType  प्रकार की एरे। |

### setQualitySettings(QualitySettings value) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public final void setQualitySettings(QualitySettings value)
```


QualitySettings आपको पहचान की गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxBarCodes का उपयोग करके जल्दी से QualitySettings सेट कर सकते हैं या आप मैन्युअल रूप से अलग विकल्पों को कॉन्फ़िगर कर सकते हैं। QualitySettings का डिफ़ॉल्ट मान NormalQuality है।

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

मान: पहचान की गुणवत्ता और गति को कॉन्फ़िगर करने के लिए QualitySettings।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) |  |

### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


पहचान प्रक्रिया का टाइमआउट मिलीसेकंड में सेट करता है।

```
BarCodeReader reader = new BarCodeReader("test.png");
 reader.setTimeout(5000);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | टाइमआउट। |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

