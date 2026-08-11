---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode for PHP via Java"
description: "Class for Jurisdiction specific fields for USA DL"
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Class for Jurisdiction specific fields for USA DL


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [addOrReplaceDataElement](#addorreplacedataelement) | No | Adds a new DataElement or replaces it if ElementID already exists. |
| [clear](#clear) | No | Clears all data elements |
| [findDataElement](#finddataelement) | No | Searches for a data element by 3-letter id. |
| [get_Item](#get_item) | No | Indexing by 3-letter element id |
| [insert](#insert) | No | Inserts a DataElement at the specified index, or replaces an existing element if an entry with the same ElementID is already present. |
| [remove](#remove) | No | Tries to remove element at index |
| [size](#size) | No | Returns number of data elements |
| [set_Item](#set_item) | No | Indexing by 3-letter element id |

### USADriveIdJurisdSubfile__construct() {#constructor}

### addOrReplaceDataElementaddOrReplaceDataElement(DataElement $node) {#addorreplacedataelement}

Adds a new DataElement or replaces it if ElementID already exists.

| Parameter | Type | Description |
| --- | --- | --- |
| `$node` | `DataElement` |  |

**Returns:** DataElement Added/replaced data element

### clearclear() {#clear}

Clears all data elements

### findDataElementfindDataElement(string $id, bool $is_open_or_create) {#finddataelement}

Searches for a data element by 3-letter id.

| Parameter | Type | Description |
| --- | --- | --- |
| `$id` | `string` |  |
| `$is_open_or_create` | `bool` |  |

**Returns:** DataElement|null Found data element (or null if not found and not created)

### get_Itemget_Item($key) {#get_item}

Indexing by 3-letter element id

| Parameter | Type | Description |
| --- | --- | --- |
| `$key` | `` |  |

**Returns:** DataElement DataElement

### insertinsert(int $index, DataElement $node) {#insert}

Inserts a DataElement at the specified index, or replaces an existing element if an entry with the same ElementID is already present.

| Parameter | Type | Description |
| --- | --- | --- |
| `$index` | `int` |  |
| `$node` | `DataElement` |  |

**Returns:** DataElement

### removeremove($index) {#remove}

Tries to remove element at index

| Parameter | Type | Description |
| --- | --- | --- |
| `$index` | `` |  |

**Returns:** bool true if successful, false if out of range

### sizesize() {#size}

Returns number of data elements

### set_Itemset_Item($key, DataElement $value) {#set_item}

Indexing by 3-letter element id

| Parameter | Type | Description |
| --- | --- | --- |
| `$key` | `` |  |
| `$value` | `DataElement` |  |

