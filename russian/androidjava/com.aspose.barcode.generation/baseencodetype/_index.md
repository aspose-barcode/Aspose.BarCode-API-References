---
title: BaseEncodeType
second_title: Справочник API Aspose.BarCode для Android через Java
description: Базовый класс для SymbologyEncodeType.
type: docs
weight: 16
url: /ru/androidjava/com.aspose.barcode.generation/baseencodetype/
---
**Inheritance:**
java.lang.Object
```
public class BaseEncodeType
```

Базовый класс для SymbologyEncodeType.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению  BaseEncodeType . |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Получает классификацию этого символьного набора. |
| [getString()](#getString--) | Преобразует экземпляр BaseEncodeType в его эквивалентное строковое представление. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Преобразует экземпляр BaseEncodeType в его эквивалентное строковое представление. |
| [getTypeIndex()](#getTypeIndex--) | Получает индекс типа кодирования. |
| [getTypeName()](#getTypeName--) | Получает название типа кодирования. |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Преобразует строковое представление имени BaseEncodeType в его экземпляр. |
| [toString()](#toString--) | Возвращает имя заданного BaseEncodeType в виде строки. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Преобразует строковое представление BaseEncodeType в его экземпляр. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Преобразует строковое представление BaseEncodeType в его экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению  BaseEncodeType .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | java.lang.Object | Значение  BaseEncodeType  для сравнения с этим экземпляром. |

**Returns:**
boolean —  **true**  если obj имеет то же значение, что и этот экземпляр; в противном случае  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


Получает классификацию этого символьного набора.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Преобразует экземпляр BaseEncodeType в его эквивалентное строковое представление. Формат строки: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - Строка, представляющая полное значение типа кодирования
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Преобразует экземпляр BaseEncodeType в его эквивалентное строковое представление. Формат строки: "Index:-1; Name:None".

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Экземпляр BaseEncodeType для преобразования |

**Returns:**
java.lang.String - Строка, представляющая полное значение заданного типа кодирования
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Получает индекс типа кодирования.

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Получает название типа кодирования.

**Returns:**
java.lang.String
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




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


Преобразует строковое представление имени BaseEncodeType в его экземпляр.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stringEncodeType | java.lang.String | Строка, содержащая имя BaseEncodeType для преобразования. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Возвращает имя заданного BaseEncodeType в виде строки.

**Returns:**
java.lang.String - Строка, представляющая имя типа кодирования
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Преобразует строковое представление BaseEncodeType в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parsingType | java.lang.String | Строка в формате "Index:-1; Name:None" для преобразования. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | Фактический SingleEncodeType возвращается, когда преобразование завершилось успешно; |

в противном случае возвращает null. |

**Returns:**
boolean -  **true**  если s был успешно преобразован; в противном случае,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Преобразует строковое представление BaseEncodeType в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parsingType | java.lang.String | Строка в формате "Index:-1; Name:None" для преобразования. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | Фактический SingleEncodeType возвращается, когда преобразование завершилось успешно; |

в противном случае возвращает null. |

**Returns:**
boolean -  **true**  если s был успешно преобразован; в противном случае,  **false** .
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

