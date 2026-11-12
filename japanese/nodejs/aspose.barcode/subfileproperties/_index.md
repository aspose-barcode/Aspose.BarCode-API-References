---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "USA DL サブファイルのプロパティ、オフセット、長さは自動的に設定されます。"
type: docs
weight: 890
url: /ja/nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

USA DL サブファイルのプロパティ、オフセット、長さは自動的に設定されます。

```js
new SubfileProperties()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getLength()](#getlength) | 4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する4桁の数値を含みます。セグメントターミネータ m |
| [getOffset()](#getoffset) | データが関連する位置まで、ファイルの先頭または開始点からのバイト数を指定する4桁の数値 |
| [getType()](#gettype) | 「DL」のような、サブファイルの2バイトタイプ |
| [setLength()](#setlength) | 4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する4桁の数値を含みます。セグメントターミネータ m |
| [setOffset()](#setoffset) | データが関連する位置まで、ファイルの先頭または開始点からのバイト数を指定する4桁の数値 |
| [setType()](#settype) | 「DL」のような、サブファイルの2バイトタイプ |

### getLength() {#getlength}

4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する4桁の数値を含みます。セグメントターミネータはサブファイルの長さ計算に含める必要があります。セグメントターミネータ = 1。各サブファイルは2文字のサブファイルタイプで開始し、これら2文字も長さに含める必要があります。

### getOffset() {#getoffset}

特定のサブファイルに関連するデータが位置するまで、ファイルの先頭または開始点からのバイト数を指定する4桁の数値。ファイル内の最初のバイトはオフセット0にあります。

### getType() {#gettype}

「DL」のような、サブファイルの2バイトタイプ

### setLength() {#setlength}

4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する4桁の数値を含みます。セグメントターミネータはサブファイルの長さ計算に含める必要があります。セグメントターミネータ = 1。各サブファイルは2文字のサブファイルタイプで開始し、これら2文字も長さに含める必要があります。

### setOffset() {#setoffset}

特定のサブファイルに関連するデータが位置するまで、ファイルの先頭または開始点からのバイト数を指定する4桁の数値。ファイル内の最初のバイトはオフセット0にあります。

### setType() {#settype}

「DL」のような、サブファイルの2バイトタイプ
