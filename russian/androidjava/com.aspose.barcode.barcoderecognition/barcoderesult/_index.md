---
title: BarCodeResult
second_title: Справочник API Aspose.BarCode для Android через Java
description: Сохраняет распознанные данные штрих‑кода, такие как тип SingleDecodeType, строка codetext, параметры BarCodeRegionParameters region и другие параметры.
type: docs
weight: 18
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
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
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
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Создаёт копию класса BarCodeResult. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт копию класса BarCodeResult. |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению BarCodeResult. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Получает закодированные байты кода |
| [getCodeText()](#getCodeText--) | Получает текст кода |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | Получает текст кода с кодировкой. |
| [getCodeType()](#getCodeType--) | Получает тип штрих‑кода |
| [getCodeTypeName()](#getCodeTypeName--) | Получает название типа штрих‑кода |
| [getConfidence()](#getConfidence--) | Получает уровень уверенности распознавания распознанного штрих‑кода |
| [getExtended()](#getExtended--) | Получает расширенные параметры распознанного штрих‑кода |
| [getReadingQuality()](#getReadingQuality--) | Получает качество чтения. |
| [getRegion()](#getRegion--) | Получает область штрих‑кода |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого BarCodeResult. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Создаёт копию класса BarCodeResult.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Копия экземпляра BarCodeResult. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт копию класса BarCodeResult.

**Returns:**
java.lang.Object — Возвращает копию класса BarCodeResult.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли данный экземпляр указанному значению BarCodeResult.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение BarCodeResult для сравнения с этим экземпляром. |

**Returns:**
boolean —  **true**  если obj имеет то же значение, что и этот экземпляр; в противном случае  **false** .
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

Значение: байты кода штрих‑кода

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Получает текст кода

Value: The code text of the barcode

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
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
| encoding | java.nio.charset.Charset | The encoding for codetext. |

**Returns:**
java.lang.String - A string containing recognized code text.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Получает тип штрих‑кода

Value: The type information of the recognized barcode

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Получает название типа штрих‑кода

Value: The type name of the recognized barcode

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


Получает уровень уверенности распознавания распознанного штрих‑кода

Value:  BarCodeConfidence.Strong  does not have fakes or misrecognitions,  BarCodeConfidence.Moderate  could sometimes have fakes or incorrect codetext because this confidence level for barcodews with weak cheksum or even without it,  BarCodeConfidence.None  always has incorrect codetext and could be fake recognitions

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Получает расширенные параметры распознанного штрих‑кода

Value: The extended parameters of recognized barcode

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Gets the reading quality. Works for 1D and postal barcodes.

Value: The reading quality percent

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Получает область штрих‑кода

Value: The region of the recognized barcode

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этого экземпляра.

**Returns:**
int — 32‑битный знаковый целочисленный хеш‑код.
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


Возвращает человекочитаемое строковое представление этого BarCodeResult.

**Returns:**
java.lang.String - A string that represents this  BarCodeResult .
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

