---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for Python via Java"
description: "Base class for encoding and decoding the text embedded in the HIBC LIC code. This sample shows how to decode raw HIBC LIC codetext to HIBCLICComplexCodetext ins"
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

**Module:** `aspose_barcode.complex_barcode.hibc_lic_complex_codetext`

**Inherits:** `IComplexCodetext`


Base class for encoding and decoding the text embedded in the HIBC LIC code. This sample shows how to decode raw HIBC LIC codetext to HIBCLICComplexCodetext instance.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | Reimplemented from IComplexCodetext. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [constructed_codetext](#constructed_codetext) | `Optional[str]` | No | Reimplemented from IComplexCodetext. Reimplemented in HIBCLICPrimaryDataCodetext, and HIBCLICCombinedCodetext. |
| [init_from_string](#init_from_string) | `None` | No | Reimplemented from IComplexCodetext. Reimplemented in HIBCLICSecondaryAndAdditionalDataCodetext, HIBCLICPrimaryDataCodetext, and HIBCLICCombinedCodetext. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [barcode_type](#barcode_type) | `EncodeTypes` | Gets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC. |

### HIBCLICComplexCodetext Constructor {#constructor}

```python
__init__(self, _java_class)
```

Reimplemented from IComplexCodetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### HIBCLICComplexCodetext.constructed_codetext {#constructed_codetext}

```python
constructed_codetext(self) -> Optional[str]
```

Reimplemented from IComplexCodetext. Reimplemented in HIBCLICPrimaryDataCodetext, and HIBCLICCombinedCodetext.

**Return Type:** `Optional[str]`

### HIBCLICComplexCodetext.init_from_string {#init_from_string}

```python
init_from_string(self, str constructed_codetext)
```

Reimplemented from IComplexCodetext. Reimplemented in HIBCLICSecondaryAndAdditionalDataCodetext, HIBCLICPrimaryDataCodetext, and HIBCLICCombinedCodetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `constructed_codetext` | `str` |  |

### HIBCLICComplexCodetext.barcode_type {#barcode_type}

**Type:** `EncodeTypes`

Gets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC.

**Returns:** Barcode type.

Sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `EncodeTypes` |  |

