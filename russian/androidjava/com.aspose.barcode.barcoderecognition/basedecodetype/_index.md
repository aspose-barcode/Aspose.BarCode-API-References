---
title: BaseDecodeType
second_title: Справочник API Aspose.BarCode для Android через Java
description: Базовый класс для MultiDecodeType и SingleDecodeType.
type: docs
weight: 23
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Базовый класс для MultiDecodeType и SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Определяет, включён ли любой из заданных типов декодирования в |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [equals(Object other)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Преобразует строковое представление BaseDecodeType в его экземпляр, определив конкретный тип. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Преобразует строковое представление MultiDecodeType в его экземпляр. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Преобразует строковое представление SingleDecodeType в его экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Определяет, включён ли любой из заданных типов декодирования в

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Типы для проверки. |

**Returns:**
boolean - Значение истинно, если любые типы включены в.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | com.aspose.barcode.barcoderecognition.MultiDecodeType | Значение java.lang.Object для сравнения с этим экземпляром. |

**Returns:**
boolean — Истина, если obj имеет то же значение, что и этот экземпляр; иначе — ложь.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Значение java.lang.Object для сравнения с этим экземпляром. |

**Returns:**
boolean — Истина, если obj имеет то же значение, что и этот экземпляр; иначе — ложь.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | java.lang.Object | Значение java.lang.Object для сравнения с этим экземпляром. |

**Returns:**
boolean — Истина, если obj имеет то же значение, что и этот экземпляр; иначе — ложь.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Преобразует строковое представление BaseDecodeType в его экземпляр, определив конкретный тип. Возвращаемое значение указывает, удалось ли преобразование или нет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parsingType | java.lang.String | Строка, содержащая представление MultiDecodeType для преобразования. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

в противном случае возвращает неопределённый тип. или MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Преобразует строковое представление MultiDecodeType в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование или нет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parsingType | java.lang.String | Строка, содержащая представление MultiDecodeType для преобразования. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Фактический MultiDecodeType возвращается, когда преобразование завершилось успешно;

в противном случае возвращает неопределённый тип. или MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Преобразует строковое представление SingleDecodeType в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование или нет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parsingType | java.lang.String | Строка, содержащая SingleDecodeType в формате "EAN8" или "EAN13" или "CodaBar"... для преобразования. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

в противном случае возвращает неопределённый тип. или SingleDecodeType (-1, "None").
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

