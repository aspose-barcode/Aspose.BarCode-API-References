---
title: MultyDecodeType
second_title: Справочник API Aspose.BarCode для Android через Java
description: Составной тип декодирования.
type: docs
weight: 38
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/multydecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype), com.aspose.barcode.barcoderecognition.MultiDecodeType
```
public class MultyDecodeType extends MultiDecodeType
```

Составной тип декодирования.

--------------------

> ```
> CreateThis sample shows how to create compound MultyDecode types that combine SingleDecodeType and MultiDecode types.
>  
>  MultyDecodeType types1 = new MultyDecodeType(DecodeType.QR, DecodeType.DATA_MATRIX);
>  MultyDecodeType types2 = new MultyDecodeType(types1, DecodeType.CODE_128, DecodeType.CODE_39);
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MultyDecodeType(SingleDecodeType[] barcodeTypes)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Инициализирует новый экземпляр класса [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype). |
| [MultyDecodeType(BaseDecodeType[] barcodeTypes)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Инициализирует новый экземпляр класса [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype). |
## Методы

| Метод | Описание |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Добавляет еще один [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) к MultiDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Проверьте, содержит ли это все типы штрихкодов. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Содержит ли любой из типов |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению MultiDecodeType. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Возвращает значение, указывающее, содержит ли эта коллекция типов декодирования только указанное значение [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype). |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению MultiDecodeType. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Исключает [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) из MultiDecodeType и возвращает новый экземпляр MultiDecodeType. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Представляет список одиночных типов. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Возвращает количество одиночных типов. |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Переопределенный метод, представляющий MultiDecodeType в виде строки. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Преобразует строковое представление BaseDecodeType в его экземпляр, определив конкретный тип. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Преобразует строковое представление MultiDecodeType в его экземпляр. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Преобразует строковое представление SingleDecodeType в его экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultyDecodeType(SingleDecodeType[] barcodeTypes) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultyDecodeType(SingleDecodeType[] barcodeTypes)
```


Инициализирует новый экземпляр класса [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Массив одиночных типов декодирования |

### MultyDecodeType(BaseDecodeType[] barcodeTypes) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultyDecodeType(BaseDecodeType[] barcodeTypes)
```


Инициализирует новый экземпляр класса [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Массив мульти и одиночных типов декодирования |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


Добавляет еще один [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) к MultiDecodeType.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Один тип Single DecodeType для добавления в список. |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Проверьте, содержит ли это все типы штрихкодов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Ввод одиночных или мульти-типов штрихкодов |

**Returns:**
boolean — значение истинно, если все типы включены в
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Содержит ли любой из типов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Типы декодирования |

**Returns:**
boolean — Значение истинно, если какие-либо типы включены в
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению MultiDecodeType.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | com.aspose.barcode.barcoderecognition.MultiDecodeType | Значение MultiDecodeType для сравнения с этим экземпляром. |

**Returns:**
boolean —  **true**  если obj имеет то же значение, что и этот экземпляр; в противном случае  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Возвращает значение, указывающее, содержит ли эта коллекция типов декодирования только указанное значение [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Значение [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) для сравнения с этой коллекцией типов декодирования. |

**Returns:**
boolean -  **true**  если эта коллекция содержит только указанный тип декодирования; в противном случае,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению MultiDecodeType.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение System.Object для сравнения с этим экземпляром. |

**Returns:**
boolean —  **true**  если obj имеет то же значение, что и этот экземпляр; в противном случае  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


Исключает [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) из MultiDecodeType и возвращает новый экземпляр MultiDecodeType.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Один тип DecodeType, который следует исключить. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Новый экземпляр MultiDecodeType с исключённым SingleDecodeType.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


Представляет список одиночных типов.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - Список одиночных типов
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


Возвращает количество одиночных типов.

**Returns:**
int
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


Переопределенный метод, представляющий MultiDecodeType в виде строки.

**Returns:**
java.lang.String - Строка, представляющая экземпляр MultiDecodeType в виде "singleDecodeType1, singleDecodeType2, ..."

 **"AllSupportedTypes"**  returns when all types are included.
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

