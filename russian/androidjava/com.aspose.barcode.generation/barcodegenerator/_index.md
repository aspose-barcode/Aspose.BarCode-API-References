---
title: BarcodeGenerator
second_title: Справочник API Aspose.BarCode для Android через Java
description: BarcodeGenerator для генерации изображений штрихкодов на сервере.
type: docs
weight: 13
url: /ru/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator для генерации изображений штрихкодов на сервере.

поддерживаемые символьные наборы: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | Создает экземпляр BarcodeGenerator. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | Создает экземпляр BarcodeGenerator. |
## Методы

| Метод | Описание |
| --- | --- |
| [dispose()](#dispose--) | Clean up any resources being used. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | Экспортирует свойства BarCode в указанный xml-поток |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Экспортирует свойства BarCode в указанный xml-файл |
| [generateBarCodeImage()](#generateBarCodeImage--) | Создайте изображение штрихкода с текущими настройками. |
| [getBarcodeType()](#getBarcodeType--) | Тип символьного набора штрихкода. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Текст для кодирования. |
| [getParameters()](#getParameters--) | Generation parameters. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Импортирует свойства BarCode из указанного xml‑потока и создает экземпляр BarcodeGenerator. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Импортирует свойства BarCode из указанного xml‑файла и создает экземпляр BarcodeGenerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Сохранить BarCodeImage в поток в указанном формате. |
| [save(String filename)](#save-java.lang.String-) | Сохранить изображение штрихкода в указанный файл. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Сохранить изображение штрихкода в указанный файл в указанном формате. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Тип символьного набора штрихкода. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | Установить codetext как последовательность байтов. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Текст для кодирования. |
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


Создает экземпляр BarcodeGenerator.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Тип символьного набора штрихкода. Используйте класс  EncodeTypes  для настройки символьного набора. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


Создает экземпляр BarcodeGenerator.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Тип символьного набора штрихкода. Используйте класс  EncodeTypes  для настройки символьного набора. |
| codeText | java.lang.String | Текст для кодирования. |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


Экспортирует свойства BarCode в указанный xml-поток

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xml | java.io.OutputStream | XML‑поток |

**Returns:**
boolean — Успешно ли завершился экспорт. Возвращает **True** в случае успеха; **False** в противном случае
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
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Создайте изображение штрихкода с текущими настройками.

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
android.graphics.Bitmap - Barcode image. See  Bitmap .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Тип символьного набора штрихкода.

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


Текст для кодирования.

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


Импортирует свойства BarCode из указанного xml‑потока и создает экземпляр BarcodeGenerator.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xml | java.io.InputStream | XML‑поток |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Импортирует свойства BarCode из указанного xml‑файла и создает экземпляр BarcodeGenerator.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFile | java.lang.String | Имя файла |

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


Сохранить BarCodeImage в поток в указанном формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Сохранить изображение штрихкода в указанный файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Path to save to. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Сохранить изображение штрихкода в указанный файл в указанном формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Path to save to. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specifies the file format of the output image. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Тип символьного набора штрихкода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


Установить codetext как последовательность байтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| codeBytes | byte[] | Байты текста кода |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Текст для кодирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Кодирует Unicode **codeText** в последовательность байтов, используя указанную **encoding**. UTF-8 является наиболее часто используемой кодировкой. Если кодировка поддерживает это, функция автоматически вставляет  [byte order mark (BOM)][byte order mark _BOM].

Эта функция предназначена только для работы с 2D‑штрихкодами (например, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR и т.д.). Она позволяет вручную кодировать Unicode‑текст с использованием национальных или специальных кодировок; однако этот метод считается устаревшим в современных приложениях. Для современных сценариев рекомендуется кодировка  [ECI][]  для Unicode‑данных.

Использование этой функции с 1D‑штрихкодами, штрихкодами, соответствующими GS1 (включая 2D), или штрихкодами HIBC (включая 2D) не поддерживается соответствующими стандартами штрихкодов и может привести к непредсказуемым результатам.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| codeText | java.lang.String | Строка CodeText |
| encoding | java.nio.charset.Charset | Применённая кодировка |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Кодирует Unicode **codeText** в последовательность байтов, используя указанную **encoding**. UTF-8 является наиболее часто используемой кодировкой. Если кодировка поддерживает это и **insertBOM** установлен в  true , функция включает  [byte order mark (BOM)][byte order mark _BOM].

Эта функция предназначена только для работы с 2D‑штрихкодами (например, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR и т.д.). Она позволяет вручную кодировать Unicode‑текст с использованием национальных или специальных кодировок; однако этот метод считается устаревшим в современных приложениях. Для современных сценариев рекомендуется кодировка  [ECI][]  для Unicode‑данных.

Использование этой функции с 1D‑штрихкодами, штрихкодами, соответствующими GS1 (включая 2D), или штрихкодами HIBC (включая 2D) не поддерживается соответствующими стандартами штрихкодов и может привести к непредсказуемым результатам.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| codeText | java.lang.String | Строка CodeText |
| encoding | java.nio.charset.Charset | Применённая кодировка |
| insertBOM | boolean | Указывает, следует ли вставлять маркер порядка байтов (BOM), когда указанная кодировка его поддерживает (например, UTF-8, UTF-16, UTF-32). Если установлено в  true , BOM добавляется; если в  false , BOM опускается, даже если кодировка обычно использует его. |

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

