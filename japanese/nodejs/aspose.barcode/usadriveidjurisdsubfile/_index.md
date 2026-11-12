---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "USA DL の管轄固有フィールド用クラス"
type: docs
weight: 950
url: /ja/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

USA DL の管轄固有フィールド用クラス

```js
new USADriveIdJurisdSubfile()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | 指定された識別子と値で新しい DataElement を追加し、同じエントリがある場合は既存の要素を置き換えます。 |
| [addOrReplaceNode(node)](#addorreplacenode) | ElementID が既に存在する場合、新しい DataElement を追加するか、置き換えます。 |
| [clear()](#clear) | すべてのデータ要素をクリアします。 |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | 3文字の ID でデータ要素を検索します。 |
| [get(indexOrId)](#get) | インデックスまたは 3 文字の ID でデータ要素を取得します。 |
| [insert(index, node)](#insert) | 指定された DataElement を指定インデックスに挿入します。同じ ElementID を持つ DataElement が既に存在する場合は置き換えられます。 |
| [remove(indexOrId)](#remove) | インデックスまたは 3 文字の ID で要素の削除を試みます。 |
| [set(indexOrId, value)](#set) | インデックスまたは 3 文字の ID でデータ要素を設定します。 |
| [size()](#size) | データ要素の数を返します。 |

### addOrReplace(id, value) {#addorreplace}

指定された識別子と値で新しい DataElement を追加し、同じ ElementID のエントリが既に存在する場合は既存の要素を置き換えます。

| パラメータ | 説明 |
| --- | --- |
| id | 管轄関連データ要素を一意に指定する 3 文字の識別子です。 |
| 値 | データ要素に割り当てられたテキスト値です。要素が既に存在する場合、この値は既存のものを上書きします。 |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

ElementID が既に存在する場合、新しい DataElement を追加するか、置き換えます。

| パラメータ | 説明 |
| --- | --- |
| node | 追加する DataElement |

**Returns:** Added/replaced data element

### clear() {#clear}

すべてのデータ要素をクリアします。

### findDataElement(id, isOpenOrCreate) {#finddataelement}

3文字の ID でデータ要素を検索します。

| パラメータ | 説明 |
| --- | --- |
| id | 3 文字の ID |
| isOpenOrCreate | true の場合、見つからなければ作成されます。 |

**Returns:** Found data element

### get(indexOrId) {#get}

インデックスまたは 3 文字の ID でデータ要素を取得します。

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| indexOrId | number\ | 文字列 | 整数インデックスまたは 3 文字の要素 ID。 |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

指定された DataElement を指定インデックスに挿入します。同じ ElementID を持つ DataElement が既に存在する場合は置き換えられます。

| パラメータ | 説明 |
| --- | --- |
| index | 要素を挿入すべきゼロベースのインデックスです。 |
| node | 対象位置に挿入または置き換える DataElement インスタンスです。 |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

インデックスまたは 3 文字の ID で要素の削除を試みます。

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| indexOrId | number\ | 文字列 | 整数インデックスまたは 3 文字の要素 ID。 |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

インデックスまたは 3 文字の ID でデータ要素を設定します。

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| indexOrId | number\ | 文字列 | 整数インデックスまたは 3 文字の要素 ID。 |
| 値 | DataElement | 設定するデータ要素。 |

### size() {#size}

データ要素の数を返します。
