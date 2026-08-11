---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Aspose.BarCode for PHP via Java"
description: "USA DL subfile properties, offset and length are set automatically."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/subfileproperties/
---

## SubfileProperties class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


USA DL subfile properties, offset and length are set automatically.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [Length](#length) | Read/Write | 4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator must be included in calculating the length of the subfile.A segment terminator = 1. Each subfile must begin with the two-character Subfile Type and these two characters must also be included in the length. |
| [Offset](#offset) | Read/Write | 4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data related to the particular sub-file is located.The first byte in the file is located at offset 0. |
| [Type](#type) | Read/Write | 2 byte type of subfile, like "DL" |

### SubfileProperties__construct($type) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$type` | `` |  |

### Length {#length}

**Access:** Read/Write

4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator must be included in calculating the length of the subfile.A segment terminator = 1. Each subfile must begin with the two-character Subfile Type and these two characters must also be included in the length.

4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator must be included in calculating the length of the subfile.A segment terminator = 1. Each subfile must begin with the two-character Subfile Type and these two characters must also be included in the length.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### Offset {#offset}

**Access:** Read/Write

4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data related to the particular sub-file is located.The first byte in the file is located at offset 0.

4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data related to the particular sub-file is located.The first byte in the file is located at offset 0.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### Type {#type}

**Access:** Read/Write

2 byte type of subfile, like "DL"

2 byte type of subfile, like "DL"

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

