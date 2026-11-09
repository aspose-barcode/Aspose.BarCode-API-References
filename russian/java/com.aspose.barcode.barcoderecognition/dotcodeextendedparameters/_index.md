---
title: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "Сохраняет специальные данные распознанного штрихкода DotCode"
type: docs
weight: 31
url: /ru/java/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

Сохраняет специальные данные распознанного штрихкода DotCode

Этот пример показывает, как получить необработанные значения DotCode

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");
 
 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [getClass()](#getClass--) |  |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Получает идентификатор штрихкода DotCode в режиме структурированного добавления. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Получает количество штрихкодов DotCode в режиме структурированного добавления. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [isEmpty()](#isEmpty--) | Проверяет, имеют ли все параметры только значения по умолчанию. |
| [isReaderInitialization()](#isReaderInitialization--) | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение System.Object для сравнения с этим экземпляром. |

**Returns:**
логический -  **true**  если obj имеет то же значение, что и этот экземпляр; иначе,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Получает идентификатор штрихкода DotCode в режиме структурированного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. Значение по умолчанию — -1.

Значение: Идентификатор штрихкода DotCode в режиме структурированного добавления.

**Returns:**
int - идентификатор штрихкода DotCode в режиме структурированного добавления.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Получает количество штрихкодов DotCode в режиме структурированного добавления. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35.

Значение: количество штрихкода режима структурного добавления DotCode.

**Returns:**
int - количество штрихкодов режима структурного добавления DotCode.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - 32-битный знаковый целочисленный хеш-код.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Проверяет, имеют ли все параметры только значения по умолчанию.

Значение: Возвращает **true**, если все параметры имеют только значения по умолчанию; иначе **false**.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. Значение по умолчанию — false.

**Returns:**
boolean
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


Возвращает человекочитаемое строковое представление этого [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - Строка, представляющая этот [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).
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

