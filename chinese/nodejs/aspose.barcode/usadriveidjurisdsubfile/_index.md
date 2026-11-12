---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于美国驾驶执照特定司法辖区字段的类"
type: docs
weight: 950
url: /zh/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

用于美国驾驶执照特定司法辖区字段的类

```js
new USADriveIdJurisdSubfile()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | 添加一个具有指定标识符和值的新 DataElement，或在已有条目具有相同标识符时替换现有元素。 |
| [addOrReplaceNode(node)](#addorreplacenode) | 添加新的 DataElement，或在 ElementID 已存在时替换它。 |
| [clear()](#clear) | 清除所有数据元素 |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | 按 3 字母 ID 搜索数据元素 |
| [get(indexOrId)](#get) | 通过其索引或 3 字母 ID 获取数据元素。 |
| [insert(index, node)](#insert) | 在给定索引处插入指定的 DataElement。如果具有相同 ElementID 的 DataElement 已存在，它将被替换。 |
| [remove(indexOrId)](#remove) | 尝试通过其索引或 3 字母 ID 移除元素。 |
| [set(indexOrId, value)](#set) | 通过其索引或 3 字母 ID 设置数据元素。 |
| [size()](#size) | 返回数据元素的数量 |

### addOrReplace(id, value) {#addorreplace}

添加一个具有指定标识符和值的新 DataElement，或在已有具有相同 ElementID 的条目时替换现有元素。

| 参数 | 描述 |
| --- | --- |
| id | 一个唯一指定司法相关数据元素的 3 字母标识符。 |
| 值 | 分配给数据元素的文本值；如果元素已存在，此值将覆盖已有值。 |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

添加新的 DataElement，或在 ElementID 已存在时替换它。

| 参数 | 描述 |
| --- | --- |
| 节点 | 要添加的 DataElement |

**Returns:** Added/replaced data element

### clear() {#clear}

清除所有数据元素

### findDataElement(id, isOpenOrCreate) {#finddataelement}

按 3 字母 ID 搜索数据元素

| 参数 | 描述 |
| --- | --- |
| id | 3 字母 id |
| isOpenOrCreate | 如果为 true，则在未找到时创建它。 |

**Returns:** Found data element

### get(indexOrId) {#get}

通过其索引或 3 字母 ID 获取数据元素。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| indexOrId | number\ | string | 整数索引或 3 字母元素 ID。 |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

在给定索引处插入指定的 DataElement。如果具有相同 ElementID 的 DataElement 已存在，它将被替换。

| 参数 | 描述 |
| --- | --- |
| 索引 | 元素应插入的零基索引。 |
| 节点 | 要在目标位置插入或替换的 DataElement 实例。 |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

尝试通过其索引或 3 字母 ID 移除元素。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| indexOrId | number\ | string | 整数索引或 3 字母元素 ID。 |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

通过其索引或 3 字母 ID 设置数据元素。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| indexOrId | number\ | string | 整数索引或 3 字母元素 ID。 |
| 值 | DataElement | 要设置的数据元素。 |

### size() {#size}

返回数据元素的数量
