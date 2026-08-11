---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for PHP via Java"
description: "Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [construct](#construct) | Yes |  |
| [initFromString](#initfromstring) | No | Initializes instance from constructed codetext. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [ConstructedCodetext](#constructedcodetext) | Read-only | Constructs codetext |
| [Message](#message) | Read/Write | Gets message. |
| [Mode](#mode) | Read/Write | Gets MaxiCode mode. |

### MaxiCodeStandardCodetext__construct() {#constructor}

### constructconstruct($maxiCodeStandardCodetextDto) (static) {#construct}

| Parameter | Type | Description |
| --- | --- | --- |
| `$maxiCodeStandardCodetextDto` | `` |  |

### initFromStringinitFromString(string $constructedCodetext) {#initfromstring}

Initializes instance from constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$constructedCodetext` | `string` |  |

### ConstructedCodetext {#constructedcodetext}

**Access:** Read-only

**Returns:** string Constructed codetext

Constructs codetext

### Message {#message}

**Access:** Read/Write

Gets message.

Sets message.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### Mode {#mode}

**Access:** Read/Write

**Returns:** int MaxiCode mode

Gets MaxiCode mode.

Sets MaxiCode mode. Standart codetext can be used only with modes 4, 5 and 6.

| Parameter | Type | Description |
| --- | --- | --- |
| `$mode` | `int` |  |

