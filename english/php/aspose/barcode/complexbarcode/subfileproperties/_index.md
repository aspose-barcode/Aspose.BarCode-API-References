---
title: "SubfileProperties Class"
linktitle: "SubfileProperties"
articleTitle: "SubfileProperties"
second_title: "Aspose.BarCode for PHP via Java"
description: "USA DL subfile properties, offset and length are set automatically."
type: docs
weight: 10
url: /php/aspose/barcode/complexbarcode/subfileproperties/
---

## SubfileProperties class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


USA DL subfile properties, offset and length are set automatically.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](./subfileproperties/) |  |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [Length](./length/) | Read/Write | 4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator must be included in calculating the length of the subfile.A segment terminator = 1. Each subfile must begin with the two-character Subfile Type and these two characters must also be included in the length. |
| [Offset](./offset/) | Read/Write | 4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data related to the particular sub-file is located.The first byte in the file is located at offset 0. |
| [Type](./type/) | Read/Write | 2 byte type of subfile, like "DL" |
