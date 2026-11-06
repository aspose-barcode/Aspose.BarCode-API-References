---
title: "BarCodeResult"
second_title: "Справочник API Aspose.BarCode для Android через Java"
description: "Сохраняет распознанные данные штрихкода, такие как тип SingleDecodeType, строка codetext, параметры BarCodeRegionParameters region и другие параметры"
type: docs
weight: 17
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Сохраняет данные распознанного штрихкода, такие как тип SingleDecodeType, строка codetext, BarCodeRegionParameters region и другие параметры

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Создает копию класса  BarCodeResult . |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создает копию класса  BarCodeResult . |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению  BarCodeResult . |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Получает закодированные байты кода |
| [getCodeText()](#getCodeText--) | Получает текст кода |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | Получает текст кода с кодировкой. |
| [getCodeType()](#getCodeType--) | Получает тип штрихкода |
| [getCodeTypeName()](#getCodeTypeName--) | Получает имя типа штрихкода |
| [getConfidence()](#getConfidence--) | Получает уровень уверенности распознавания распознанного штрихкода |
| [getExtended()](#getExtended--) | Получает расширенные параметры распознанного штрихкода |
| [getReadingQuality()](#getReadingQuality--) | Получает качество чтения. |
| [getRegion()](#getRegion--) | Получает область штрихкода |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого  BarCodeResult . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Создает копию класса  BarCodeResult .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Копия экземпляра  BarCodeResult . |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создает копию класса  BarCodeResult .

**Returns:**
java.lang.Object - Возвращает копию класса  BarCodeResult .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению  BarCodeResult .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение  BarCodeResult  для сравнения с этим экземпляром. |

**Returns:**
boolean -  **true**  если obj имеет то же значение, что и этот экземпляр; иначе,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


Получает закодированные байты кода

Значение: Байты кода штрихкода

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Получает текст кода

Значение: Текст кода штрихкода

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
```


Получает текст кода с кодировкой.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| charset | java.nio.charset.Charset | Кодировка для текста кода. |

**Returns:**
java.lang.String - Строка, содержащая распознанный текст кода.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Получает тип штрихкода

Значение: Информация о типе распознанного штрихкода

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Получает имя типа штрихкода

Значение: Имя типа распознанного штрихкода

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


Получает уровень уверенности распознавания распознанного штрихкода

Значение:  BarCodeConfidence.Strong  не имеет подделок или ошибок распознавания,  BarCodeConfidence.Moderate  может иногда иметь подделки или некорректный текст кода, потому что этот уровень уверенности для штрихкодов с слабой контрольной суммой или даже без неё,  BarCodeConfidence.None  всегда имеет некорректный текст кода и может быть поддельными распознаваниями

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Получает расширенные параметры распознанного штрихкода

Значение: Расширенные параметры распознанного штрихкода

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Получает качество чтения. Работает для 1D и почтовых штрихкодов.

Значение: Процент качества чтения

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Получает область штрихкода

Значение: Область распознанного штрихкода

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - 32-битный знаковый целочисленный хеш-код.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого  BarCodeResult .

**Returns:**
java.lang.String - Строка, представляющая этот  BarCodeResult .
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

