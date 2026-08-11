---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "USA DL subfile properties, offset and length are set automatically."
type: docs
weight: 890
url: /nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

USA DL subfile properties, offset and length are set automatically.

```js
new SubfileProperties()
```

## Methods

| Name | Description |
| --- | --- |
| [getLength()](#getlength) | 4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator m |
| [getOffset()](#getoffset) | 4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data relate |
| [getType()](#gettype) | 2 byte type of subfile, like "DL" |
| [setLength()](#setlength) | 4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator m |
| [setOffset()](#setoffset) | 4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data relate |
| [setType()](#settype) | 2 byte type of subfile, like "DL" |

### getLength() {#getlength}

4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator must be included in calculating the length of the subfile.A segment terminator = 1. Each subfile must begin with the two-character Subfile Type and these two characters must also be included in the length.

### getOffset() {#getoffset}

4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data related to the particular sub-file is located.The first byte in the file is located at offset 0.

### getType() {#gettype}

2 byte type of subfile, like "DL"

### setLength() {#setlength}

4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator must be included in calculating the length of the subfile.A segment terminator = 1. Each subfile must begin with the two-character Subfile Type and these two characters must also be included in the length.

### setOffset() {#setoffset}

4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data related to the particular sub-file is located.The first byte in the file is located at offset 0.

### setType() {#settype}

2 byte type of subfile, like "DL"
