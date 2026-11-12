---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "USA DL 子文件属性、偏移量和长度会自动设置。"
type: docs
weight: 890
url: /zh/nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

USA DL 子文件属性、偏移量和长度会自动设置。

```js
new SubfileProperties()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getLength()](#getlength) | 4 这些字节包含一个4位数字值，指定 Subfile 的字节长度。段结束符 m |
| [getOffset()](#getoffset) | 4 位数字值，指定从文件头或开始位置到数据所在位置的字节数 |
| [getType()](#gettype) | 2 字节的子文件类型，例如 "DL" |
| [setLength()](#setlength) | 4 这些字节包含一个4位数字值，指定 Subfile 的字节长度。段结束符 m |
| [setOffset()](#setoffset) | 4 位数字值，指定从文件头或开始位置到数据所在位置的字节数 |
| [setType()](#settype) | 2 字节的子文件类型，例如 "DL" |

### getLength() {#getlength}

4 这些字节包含一个4位数字值，指定 Subfile 的字节长度。段结束符必须计入子文件长度的计算。段结束符 = 1。每个子文件必须以两个字符的 Subfile Type 开头，这两个字符也必须计入长度。

### getOffset() {#getoffset}

4 位数字值，指定从文件头或开始位置到特定子文件相关数据所在位置的字节数。文件中的第一个字节位于偏移量 0。

### getType() {#gettype}

2 字节的子文件类型，例如 "DL"

### setLength() {#setlength}

4 这些字节包含一个4位数字值，指定 Subfile 的字节长度。段结束符必须计入子文件长度的计算。段结束符 = 1。每个子文件必须以两个字符的 Subfile Type 开头，这两个字符也必须计入长度。

### setOffset() {#setoffset}

4 位数字值，指定从文件头或开始位置到特定子文件相关数据所在位置的字节数。文件中的第一个字节位于偏移量 0。

### setType() {#settype}

2 字节的子文件类型，例如 "DL"
