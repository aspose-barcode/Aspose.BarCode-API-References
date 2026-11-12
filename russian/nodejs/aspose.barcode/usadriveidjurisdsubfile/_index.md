---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Класс для полей, специфичных для юрисдикции, в водительском удостоверении США"
type: docs
weight: 950
url: /ru/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

Класс для полей, специфичных для юрисдикции, в водительском удостоверении США

```js
new USADriveIdJurisdSubfile()
```

## Методы

| Имя | Описание |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | Добавляет новый DataElement с указанным идентификатором и значением, или заменяет существующий элемент, если запись с sa |
| [addOrReplaceNode(node)](#addorreplacenode) | Добавляет новый DataElement или заменяет его, если ElementID уже существует. |
| [clear()](#clear) | Очищает все элементы данных |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | Ищет элемент данных по 3-буквенному идентификатору |
| [get(indexOrId)](#get) | Получает элемент данных по его индексу или 3-буквенному ID. |
| [insert(index, node)](#insert) | Вставляет указанный DataElement в заданный индекс. Если DataElement с тем же ElementID уже существует, он будет b |
| [remove(indexOrId)](#remove) | Пытается удалить элемент по его индексу или 3-буквенному ID. |
| [set(indexOrId, value)](#set) | Устанавливает элемент данных по его индексу или 3-буквенному ID. |
| [size()](#size) | Возвращает количество элементов данных |

### addOrReplace(id, value) {#addorreplace}

Добавляет новый DataElement с указанным идентификатором и значением, или заменяет существующий элемент, если запись с тем же ElementID уже присутствует.

| Параметр | Описание |
| --- | --- |
| id | 3-буквенный идентификатор, который однозначно определяет связанный с юрисдикцией элемент данных. |
| значение | Текстовое значение, присвоенное элементу данных; это значение перезапишет существующее, если элемент уже существует. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

Добавляет новый DataElement или заменяет его, если ElementID уже существует.

| Параметр | Описание |
| --- | --- |
| node | DataElement для добавления |

**Returns:** Added/replaced data element

### clear() {#clear}

Очищает все элементы данных

### findDataElement(id, isOpenOrCreate) {#finddataelement}

Ищет элемент данных по 3-буквенному идентификатору

| Параметр | Описание |
| --- | --- |
| id | 3-буквенный id |
| isOpenOrCreate | Если true, будет создано, если не найдено |

**Returns:** Found data element

### get(indexOrId) {#get}

Получает элемент данных по его индексу или 3-буквенному ID.

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexOrId | number\ | string | Целочисленный индекс или 3-буквенный элемент ID. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

Вставляет указанный DataElement в заданный индекс. Если DataElement с тем же ElementID уже существует, он будет заменён.

| Параметр | Описание |
| --- | --- |
| index | Индекс, начинающийся с нуля, по которому элемент должен быть вставлен. |
| node | Экземпляр DataElement для вставки или замены в целевой позиции. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

Пытается удалить элемент по его индексу или 3-буквенному ID.

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexOrId | number\ | string | Целочисленный индекс или 3-буквенный элемент ID. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

Устанавливает элемент данных по его индексу или 3-буквенному ID.

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexOrId | number\ | string | Целочисленный индекс или 3-буквенный элемент ID. |
| значение | DataElement | Элемент данных для установки. |

### size() {#size}

Возвращает количество элементов данных
