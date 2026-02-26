---
title: SubfileProperties Class
linktitle: SubfileProperties
articleTitle: SubfileProperties
second_title: Aspose.BarCode for Node.js via Java
description: USA DL subfile properties, offset and length are set automatically.
type: docs
weight: 350
url: /nodejs/subfileproperties/
---
## SubfileProperties class

USA DL subfile properties, offset and length are set automatically.

```javascript
public class SubfileProperties : BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [SubfileProperties](./subfileproperties/#constructor)(*object*) | Initializes a new instance of the SubfileProperties class. |

## Methods

| Name | Description |
| --- | --- |
| [_internalCtor](./_internalctor/)(*object*) |  |
| [getLength](./getlength/) | 4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator must be included in calculating the length of the subfile.A segment terminator = 1. Each subfile must begin with the two-character Subfile Type and these two characters must also... |
| [getOffset](./getoffset/) | 4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data related to the particular sub-file is located.The first byte in the file is located at offset 0. |
| [getType](./gettype/) | 2 byte type of subfile, like "DL". |
| [init](./init/) |  |
| [setLength](./setlength/)(*object*) | 4 These bytes contain a 4 digit numeric value that specifies the length of the Subfile in bytes.The segment terminator must be included in calculating the length of the subfile.A segment terminator = 1. Each subfile must begin with the two-character Subfile Type and these two characters must also... |
| [setOffset](./setoffset/)(*object*) | 4 digit numeric value that specifies the number of bytes from the head or beginning of the file to where the data related to the particular sub-file is located.The first byte in the file is located at offset 0. |
| [setType](./settype/)(*object*) | 2 byte type of subfile, like "DL". |

## Fields

| Name | Description |
| --- | --- |
| [javaClassName](./javaclassname/) |  |

### See Also

* assembly [Aspose.BarCode](../)

