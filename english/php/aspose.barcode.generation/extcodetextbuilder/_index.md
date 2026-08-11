---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Aspose.BarCode for PHP via Java"
description: "Helper class for automatic codetext generation of the Extended Codetext Mode"
type: docs
weight: 10
url: /php/aspose.barcode.generation/extcodetextbuilder/
---

## ExtCodetextBuilder class

**Namespace:** `Aspose.Barcode.Generation`


Helper class for automatic codetext generation of the Extended Codetext Mode


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) | Reimplemented in Aspose\Barcode\Generation\QrExtCodetextBuilder, Aspose\Barcode\Generation\MaxiCodeExtCodetextBuilder, Aspose\Barcode\Generation\DotCodeExtCodetextBuilder, and Aspose\Barcode\Generation\DataMatrixExtCodetextBuilder. |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [addECICodetext](#addecicodetext) | No | Adds codetext with Extended Channel Identifier |
| [addPlainCodetext](#addplaincodetext) | No | Adds plain codetext to the extended codetext items |
| [clear](#clear) | No | Clears extended codetext items |
| [init](#init) | No | Reimplemented in Aspose\Barcode\Generation\QrExtCodetextBuilder, Aspose\Barcode\Generation\MaxiCodeExtCodetextBuilder, Aspose\Barcode\Generation\DotCodeExtCodetextBuilder, and Aspose\Barcode\Generation\DataMatrixExtCodetextBuilder. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [ExtCodetextBuilderType](#extcodetextbuildertype) | Read-only | Reimplemented in Aspose\Barcode\Generation\QrExtCodetextBuilder, Aspose\Barcode\Generation\MaxiCodeExtCodetextBuilder, Aspose\Barcode\Generation\DotCodeExtCodetextBuilder, and Aspose\Barcode\Generation\DataMatrixExtCodetextBuilder. |
| [ExtendedCodetext](#extendedcodetext) | Read-only | Generate extended codetext from generation items list |

### ExtCodetextBuilder__construct() {#constructor}

Reimplemented in Aspose\Barcode\Generation\QrExtCodetextBuilder, Aspose\Barcode\Generation\MaxiCodeExtCodetextBuilder, Aspose\Barcode\Generation\DotCodeExtCodetextBuilder, and Aspose\Barcode\Generation\DataMatrixExtCodetextBuilder.

### addECICodetextaddECICodetext(int $ECIEncoding, string $codetext) {#addecicodetext}

Adds codetext with Extended Channel Identifier

| Parameter | Type | Description |
| --- | --- | --- |
| `$ECIEncoding` | `int` |  |
| `$codetext` | `string` |  |

### addPlainCodetextaddPlainCodetext(string $codetext) {#addplaincodetext}

Adds plain codetext to the extended codetext items

| Parameter | Type | Description |
| --- | --- | --- |
| `$codetext` | `string` |  |

### clearclear() {#clear}

Clears extended codetext items

### initinit() {#init}

Reimplemented in Aspose\Barcode\Generation\QrExtCodetextBuilder, Aspose\Barcode\Generation\MaxiCodeExtCodetextBuilder, Aspose\Barcode\Generation\DotCodeExtCodetextBuilder, and Aspose\Barcode\Generation\DataMatrixExtCodetextBuilder.

### ExtCodetextBuilderType {#extcodetextbuildertype}

**Access:** Read-only

Reimplemented in Aspose\Barcode\Generation\QrExtCodetextBuilder, Aspose\Barcode\Generation\MaxiCodeExtCodetextBuilder, Aspose\Barcode\Generation\DotCodeExtCodetextBuilder, and Aspose\Barcode\Generation\DataMatrixExtCodetextBuilder.

### ExtendedCodetext {#extendedcodetext}

**Access:** Read-only

**Returns:** string Return string of extended codetext

Generate extended codetext from generation items list

