---
title: "AlternativeScheme"
second_title: "Aspose.BarCode for Java API Reference"
description: "Инструкции по альтернативной схеме оплаты"
type: docs
weight: 11
url: /ru/java/com.aspose.barcode.complexbarcode/alternativescheme/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class AlternativeScheme implements System.IEquatable<AlternativeScheme>
```

Инструкции по альтернативной схеме оплаты
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AlternativeScheme()](#AlternativeScheme--) |  |
| [AlternativeScheme(String instruction)](#AlternativeScheme-java.lang.String-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект текущему объекту. |
| [getClass()](#getClass--) |  |
| [getInstruction()](#getInstruction--) | Получает инструкцию по оплате для указанного счета. |
| [hashCode()](#hashCode--) | Получает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setInstruction(String value)](#setInstruction-java.lang.String-) | Получает инструкцию по оплате для указанного счета. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AlternativeScheme() {#AlternativeScheme--}
```
public AlternativeScheme()
```


### AlternativeScheme(String instruction) {#AlternativeScheme-java.lang.String-}
```
public AlternativeScheme(String instruction)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| инструкция | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный объект текущему объекту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с текущим объектом. |

**Returns:**
boolean -  true  если указанный объект равен текущему объекту; в противном случае,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstruction() {#getInstruction--}
```
public String getInstruction()
```


Получает инструкцию по оплате для указанного счета.

Инструкция состоит из двухбуквенного сокращения схемы, символов-разделителей и последовательности параметров (разделённых символом с индексом 2).

Значение: Инструкция платежа.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш-код для этого экземпляра.

**Returns:**
int - Хеш-код текущего объекта.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setInstruction(String value) {#setInstruction-java.lang.String-}
```
public void setInstruction(String value)
```


Получает инструкцию по оплате для указанного счета.

Инструкция состоит из двухбуквенного сокращения схемы, символов-разделителей и последовательности параметров (разделённых символом с индексом 2).

Значение: Инструкция платежа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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

