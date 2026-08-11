---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for PHP via Java"
description: "Base class for encoding and decoding the text embedded in the HIBC LIC code."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Base class for encoding and decoding the text embedded in the HIBC LIC code.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [initFromString](#initfromstring) | No | Initializes instance from constructed codetext. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [BarcodeType](#barcodetype) | Read/Write | Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC. |
| [ConstructedCodetext](#constructedcodetext) | Read-only | Constructs codetext |

### HIBCLICComplexCodetext__construct($HIBCLICComplexCodetextDto) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$HIBCLICComplexCodetextDto` | `` |  |

### initFromStringinitFromString(string $constructedCodetext) {#initfromstring}

Initializes instance from constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$constructedCodetext` | `string` |  |

### BarcodeType {#barcodetype}

**Access:** Read/Write

**Returns:** int Barcode type.

Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC.

Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### ConstructedCodetext {#constructedcodetext}

**Access:** Read-only

**Returns:** string Constructed codetext

Constructs codetext

