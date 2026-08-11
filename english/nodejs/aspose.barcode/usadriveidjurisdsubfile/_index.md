---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Class for Jurisdiction specific fields for USA DL"
type: docs
weight: 950
url: /nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

Class for Jurisdiction specific fields for USA DL

```js
new USADriveIdJurisdSubfile()
```

## Methods

| Name | Description |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | Adds a new DataElement with the specified identifier and value, or replaces the existing element if an entry with the sa |
| [addOrReplaceNode(node)](#addorreplacenode) | Adds new DataElement or replaces it if ElementID already exists. |
| [clear()](#clear) | Clears all data elements |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | Searches for data element by 3-letter id |
| [get(indexOrId)](#get) | Gets a data element by its index or 3-letter ID. |
| [insert(index, node)](#insert) | Inserts the specified DataElement at the given index. If a DataElement with the same ElementID already exists, it will b |
| [remove(indexOrId)](#remove) | Tries to remove an element by its index or 3-letter ID. |
| [set(indexOrId, value)](#set) | Sets a data element by its index or 3-letter ID. |
| [size()](#size) | Returns number of data elements |

### addOrReplace(id, value) {#addorreplace}

Adds a new DataElement with the specified identifier and value, or replaces the existing element if an entry with the same ElementID is already present.

| Parameter | Description |
| --- | --- |
| id | A 3-letter identifier that uniquely specifies the jurisdiction-related data element. |
| value | The text value assigned to the data element; this value will overwrite the existing one if the element already exists. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

Adds new DataElement or replaces it if ElementID already exists.

| Parameter | Description |
| --- | --- |
| node | DataElement to add |

**Returns:** Added/replaced data element

### clear() {#clear}

Clears all data elements

### findDataElement(id, isOpenOrCreate) {#finddataelement}

Searches for data element by 3-letter id

| Parameter | Description |
| --- | --- |
| id | 3-letter id |
| isOpenOrCreate | If true, it will be created if not found |

**Returns:** Found data element

### get(indexOrId) {#get}

Gets a data element by its index or 3-letter ID.

| Parameter | Type | Description |
| --- | --- | --- |
| indexOrId | number\|string | Integer index or 3-letter element ID. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

Inserts the specified DataElement at the given index. If a DataElement with the same ElementID already exists, it will be replaced.

| Parameter | Description |
| --- | --- |
| index | The zero-based index at which the element should be inserted. |
| node | The DataElement instance to insert or replace at the target position. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

Tries to remove an element by its index or 3-letter ID.

| Parameter | Type | Description |
| --- | --- | --- |
| indexOrId | number\|string | Integer index or 3-letter element ID. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

Sets a data element by its index or 3-letter ID.

| Parameter | Type | Description |
| --- | --- | --- |
| indexOrId | number\|string | Integer index or 3-letter element ID. |
| value | DataElement | Data element to set. |

### size() {#size}

Returns number of data elements
