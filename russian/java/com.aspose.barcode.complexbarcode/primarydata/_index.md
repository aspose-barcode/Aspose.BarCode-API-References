---
title: "PrimaryData"
second_title: "Aspose.BarCode for Java API Reference"
description: "Класс для хранения первичных данных HIBC LIC."
type: docs
weight: 33
url: /ru/java/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

Класс для хранения первичных данных HIBC LIC.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению  PrimaryData  . |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Определяет дату кода идентификации маркировщика. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Определяет номер продукта или каталога. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Определяет идентификатор единицы измерения. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | Создаёт первичные данные из строкового формата в соответствии со спецификацией HIBC LIC. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Определяет дату кода идентификации маркировщика. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Определяет номер продукта или каталога. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Определяет идентификатор единицы измерения. |
| [toString()](#toString--) | Преобразует данные в строковый формат в соответствии со спецификацией HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению  PrimaryData  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение  PrimaryData  для сравнения с этим экземпляром. |

**Returns:**
логический -  **true**  если obj имеет то же значение, что и этот экземпляр; иначе,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


Определяет дату кода идентификации маркировщика. Код идентификации маркировщика должен быть 4‑символьной буквенно‑цифровой строкой, при этом первый символ всегда должен быть буквой.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Определяет номер продукта или каталога. Номер продукта или каталога должен быть буквенно‑цифровой строкой длиной до 18 символов.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


Определяет идентификатор единицы измерения. Идентификатор единицы измерения должен быть целым числом от 0 до 9.

**Returns:**
int
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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


Создаёт первичные данные из строкового формата в соответствии со спецификацией HIBC LIC.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | Отформатированная строка. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Определяет дату кода идентификации маркировщика. Код идентификации маркировщика должен быть 4‑символьной буквенно‑цифровой строкой, при этом первый символ всегда должен быть буквой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Определяет номер продукта или каталога. Номер продукта или каталога должен быть буквенно‑цифровой строкой длиной до 18 символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Определяет идентификатор единицы измерения. Идентификатор единицы измерения должен быть целым числом от 0 до 9.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toString() {#toString--}
```
public String toString()
```


Преобразует данные в строковый формат в соответствии со спецификацией HIBC LIC.

**Returns:**
java.lang.String - Отформатированная строка.
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

