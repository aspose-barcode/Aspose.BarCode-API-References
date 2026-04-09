---
title: BarCodeReader
second_title: Справочник API Aspose.BarCode для Android через Java
description: BarCodeReader инкапсулирует изображение, которое может содержать один или несколько штрихкодов, после чего может выполнить операцию ReadBarCodes для обнаружения штрихкодов.
type: docs
weight: 15
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/barcodereader/
---
**Inheritance:**
java.lang.Object
```
public class BarCodeReader
```

BarCodeReader инкапсулирует изображение, которое может содержать один или несколько штрихкодов, после чего может выполнить операцию ReadBarCodes для обнаружения штрихкодов.

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BarCodeReader()](#BarCodeReader--) | Инициализирует новый экземпляр класса  BarCodeReader  со значениями по умолчанию. |
| [BarCodeReader(Bitmap image)](#BarCodeReader-android.graphics.Bitmap-) | Инициализирует новый экземпляр класса  BarCodeReader  из изображения. |
| [BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes)](#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(Bitmap image, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type)](#BarCodeReader-java.lang.String-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(InputStream stream, Rect area, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(String imagePath, Rect area, BaseDecodeType type)](#BarCodeReader-java.lang.String-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(Bitmap image, Rect area, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) |  |
| [BarCodeReader(String filename)](#BarCodeReader-java.lang.String-) | Инициализирует новый экземпляр класса  BarCodeReader  из файла. |
| [BarCodeReader(String filename, BaseDecodeType type)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(String filename, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(InputStream stream)](#BarCodeReader-java.io.InputStream-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(InputStream stream, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Инициализирует новый экземпляр класса  BarCodeReader . |
| [BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Инициализирует новый экземпляр класса  BarCodeReader . |
## Методы

| Метод | Описание |
| --- | --- |
| [abort()](#abort--) | Функция запрашивает завершение текущей сессии распознавания из другого потока. |
| [dispose()](#dispose--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xmlStream)](#exportToXml-java.io.OutputStream-) | Экспортирует свойства BarCode в указанный xml-поток |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Экспортирует свойства BarCode в указанный xml-файл |
| [getBarCodeReadType()](#getBarCodeReadType--) | Получает тип декодирования входного штрихкода |
| [getBarcodeSettings()](#getBarcodeSettings--) | Основные параметры декодирования BarCode. |
| [getClass()](#getClass--) |  |
| [getFoundBarCodes()](#getFoundBarCodes--) | Получает массив распознанных  BarCodeResult s |
| [getFoundCount()](#getFoundCount--) | Получает количество распознанных штрихкодов |
| [getProcessorSettings()](#getProcessorSettings--) | Получает настройки использования ядер процессора. |
| [getQualitySettings()](#getQualitySettings--) | QualitySettings позволяет вручную настраивать качество и скорость распознавания. |
| [getTimeout()](#getTimeout--) | Получает таймаут процесса распознавания в миллисекундах. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xmlStream)](#importFromXml-java.io.InputStream-) | Импортирует свойства BarCode из указанного xml-потока и применяет их к текущему экземпляру BarCodeReader. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Импортирует свойства BarCode из указанного XML‑файла и применяет их к текущему экземпляру BarCodeReader. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBarCodes()](#readBarCodes--) | Считывает BarCodeResult из изображения. |
| [setBarCodeImage(Bitmap value)](#setBarCodeImage-android.graphics.Bitmap-) | Устанавливает bitmap‑изображение для распознавания. |
| [setBarCodeImage(Bitmap value, Rect area)](#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect-) | Устанавливает bitmap‑изображение и область для распознавания. |
| [setBarCodeImage(Bitmap value, Rect[] areas)](#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect---) | Устанавливает bitmap‑изображение и области для распознавания. |
| [setBarCodeImage(InputStream stream)](#setBarCodeImage-java.io.InputStream-) | Устанавливает поток изображения для распознавания. |
| [setBarCodeImage(String filename)](#setBarCodeImage-java.lang.String-) | Устанавливает файл изображения для распознавания. |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Устанавливает тип декодирования для распознавания. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Устанавливает массив типа SingleDecodeType для распознавания. |
| [setQualitySettings(QualitySettings value)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings позволяет вручную настраивать качество и скорость распознавания. |
| [setTimeout(int value)](#setTimeout-int-) | Устанавливает таймаут процесса распознавания в миллисекундах. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeReader() {#BarCodeReader--}
```
public BarCodeReader()
```


Инициализирует новый экземпляр класса BarCodeReader со значениями по умолчанию. Требуется установить изображение (SetBitmapImage()) перед вызовом метода ReadBarCodes().

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


Инициализирует новый экземпляр класса  BarCodeReader  из изображения.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | android.graphics.Bitmap | Экземпляр Bitmap, содержащий изображение |

### BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes) {#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | android.graphics.Bitmap | Изображение. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Типы декодирования. |

### BarCodeReader(Bitmap image, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, BaseDecodeType type)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | android.graphics.Bitmap | Изображение. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Тип декодирования. Может быть одинарным или множественным |

### BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | android.graphics.Bitmap | Изображение. |
| область | android.graphics.Rect | Область для распознавания. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Типы декодирования. |

### BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type) {#BarCodeReader-java.lang.String-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| imagePath | java.lang.String | Путь к изображению. |
| areas | android.graphics.Rect[] | Область для распознавания. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Тип декодирования. |

### BarCodeReader(InputStream stream, Rect area, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rect area, BaseDecodeType type)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток изображения. |
| область | android.graphics.Rect | Область для распознавания. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Тип декодирования. |

### BarCodeReader(String imagePath, Rect area, BaseDecodeType type) {#BarCodeReader-java.lang.String-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rect area, BaseDecodeType type)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| imagePath | java.lang.String | Путь к изображению. |
| область | android.graphics.Rect | Область для распознавания. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Тип декодирования. |

### BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток изображения. |
| areas | android.graphics.Rect[] | Область для распознавания. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Тип декодирования. |

### BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | android.graphics.Bitmap | Изображение. |
| areas | android.graphics.Rect[] | Области для распознавания. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Тип декодирования. |

### BarCodeReader(Bitmap image, Rect area, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, Rect area, BaseDecodeType type)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | android.graphics.Bitmap |  |
| область | android.graphics.Rect |  |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### BarCodeReader(String filename) {#BarCodeReader-java.lang.String-}
```
public BarCodeReader(String filename)
```


Инициализирует новый экземпляр класса  BarCodeReader  из файла.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Имя файла. |

### BarCodeReader(String filename, BaseDecodeType type) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String filename, BaseDecodeType type)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Имя файла. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Тип декодирования. |

### BarCodeReader(String filename, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(String filename, BaseDecodeType[] decodeTypes)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Имя файла. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Типы декодирования. |

### BarCodeReader(InputStream stream) {#BarCodeReader-java.io.InputStream-}
```
public BarCodeReader(InputStream stream)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |

### BarCodeReader(InputStream stream, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, BaseDecodeType type)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Тип декодирования. |

### BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)
```


Инициализирует новый экземпляр класса  BarCodeReader .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Типы декодирования. |

### abort() {#abort--}
```
public void abort()
```


Функция запрашивает завершение текущего сеанса распознавания из другого потока. Abort — метод, который нельзя прервать, и он возвращает управление сразу после вызова. Этот метод следует использовать, когда процесс распознавания слишком длительный.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xmlStream) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xmlStream)
```


Экспортирует свойства BarCode в указанный xml-поток

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlStream | java.io.OutputStream | XML-поток для сохранения |

**Returns:**
boolean — успешно ли завершён экспорт.

Возвращает  **True**  в случае успеха;  **False**  в противном случае.
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Экспортирует свойства BarCode в указанный xml-файл

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFile | java.lang.String | Имя файла |

**Returns:**
boolean — успешно ли завершён экспорт.

Возвращает  **True**  в случае успеха;  **False**  в противном случае.
### getBarCodeReadType() {#getBarCodeReadType--}
```
public BaseDecodeType getBarCodeReadType()
```


Получает тип декодирования входного штрихкода

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


Основные параметры декодирования BarCode. Содержит параметры, влияющие на распознанные данные.

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


Получает массив распознанных  BarCodeResult s

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

Значение: массив распознанных BarCodeResult s

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[]
### getFoundCount() {#getFoundCount--}
```
public int getFoundCount()
```


Получает количество распознанных штрихкодов

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

Значение: количество распознанных штрихкодов

**Returns:**
int
### getProcessorSettings() {#getProcessorSettings--}
```
public static ProcessorSettings getProcessorSettings()
```


Получает настройки использования ядер процессора.

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


QualitySettings позволяет вручную настраивать качество и скорость распознавания. Вы можете быстро установить QualitySettings с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, либо вручную настроить отдельные параметры. Значение по умолчанию для QualitySettings — NormalQuality.

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

Значение: QualitySettings для настройки качества и скорости распознавания.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


Получает таймаут процесса распознавания в миллисекундах.

```
BarCodeReader reader = new BarCodeReader("test.png");
     reader.setTimeout(5000);
     for(BarCodeResult result : reader.readBarCodes())
         System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Returns:**
int — тайм-аут.
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


Импортирует свойства BarCode из указанного xml-потока и применяет их к текущему экземпляру BarCodeReader.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlStream | java.io.InputStream | XML-поток для загрузки |

**Returns:**
[BarCodeReader](../../com.aspose.barcode.barcoderecognition/barcodereader) - Returns  **True**  in case of success;

 **False**  Otherwise
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarCodeReader importFromXml(String xmlFile)
```


Импортирует свойства BarCode из указанного XML‑файла и применяет их к текущему экземпляру BarCodeReader.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFile | java.lang.String | Имя файла |

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


Считывает BarCodeResult из изображения.

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
com.aspose.barcode.barcoderecognition.BarCodeResult[] — возвращает массив распознанных BarCodeResult s на изображении. Если ничего не распознано, возвращается пустой массив.
### setBarCodeImage(Bitmap value) {#setBarCodeImage-android.graphics.Bitmap-}
```
public void setBarCodeImage(Bitmap value)
```


Устанавливает растровое изображение для распознавания. Должен вызываться до метода ReadBarCodes().

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | android.graphics.Bitmap | Растровое изображение для распознавания. |

### setBarCodeImage(Bitmap value, Rect area) {#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect-}
```
public final void setBarCodeImage(Bitmap value, Rect area)
```


Устанавливает растровое изображение и область для распознавания. Должен вызываться до метода ReadBarCodes().

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | android.graphics.Bitmap | Растровое изображение для распознавания. |
| область | android.graphics.Rect | область для распознавания |

### setBarCodeImage(Bitmap value, Rect[] areas) {#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect---}
```
public final void setBarCodeImage(Bitmap value, Rect[] areas)
```


Устанавливает растровое изображение и области для распознавания. Должен вызываться до метода ReadBarCodes().

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | android.graphics.Bitmap | Растровое изображение для распознавания. |
| areas | android.graphics.Rect[] | список областей для распознавания |

### setBarCodeImage(InputStream stream) {#setBarCodeImage-java.io.InputStream-}
```
public final void setBarCodeImage(InputStream stream)
```


Устанавливает поток изображения для распознавания. Должен вызываться до метода ReadBarCodes().

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток изображения для распознавания. |

### setBarCodeImage(String filename) {#setBarCodeImage-java.lang.String-}
```
public void setBarCodeImage(String filename)
```


Устанавливает файл изображения для распознавания. Должен вызываться до метода ReadBarCodes().

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Файл изображения для распознавания. |

### setBarCodeReadType(BaseDecodeType type) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public void setBarCodeReadType(BaseDecodeType type)
```


Устанавливает тип декодирования для распознавания. Должно быть вызвано до метода ReadBarCodes().

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Тип штрихкода для чтения. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


Устанавливает массив типа SingleDecodeType для распознавания. Должен вызываться до метода ReadBarCodes().

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Массив типа SingleDecodeType для чтения. |

### setQualitySettings(QualitySettings value) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public final void setQualitySettings(QualitySettings value)
```


QualitySettings позволяет вручную настраивать качество и скорость распознавания. Вы можете быстро установить QualitySettings с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, либо вручную настроить отдельные параметры. Значение по умолчанию для QualitySettings — NormalQuality.

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

Значение: QualitySettings для настройки качества и скорости распознавания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) |  |

### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


Устанавливает таймаут процесса распознавания в миллисекундах.

```
BarCodeReader reader = new BarCodeReader("test.png");
 reader.setTimeout(5000);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Тайм-аут. |

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

