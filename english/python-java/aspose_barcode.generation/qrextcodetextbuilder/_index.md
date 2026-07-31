---
title: "QrExtCodetextBuilder Class"
linktitle: "QrExtCodetextBuilder"
articleTitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for Python via Java"
description: "Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QREncodeMode Use Display2DText property of BarCodeBuilder to set visible text to rem"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation.qr_ext_codetext_builder/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

**Module:** `aspose_barcode.generation.qr_ext_codetext_builder`

**Inherits:** `ExtCodetextBuilder`


Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QREncodeMode Use Display2DText property of BarCodeBuilder to set visible text to removing managing characters. Example how to generate FNC1 first position for Extended Mode Example how to generate FNC1 second position for Extended Mode Example how to generate multi ECI mode for Extended Mode


## Constructors

| Name | Description |
| --- | --- |
| [__init__](/python-java/aspose_barcode.generation.qr_ext_codetext_builder/qrextcodetextbuilder/qrextcodetextbuilder/) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [add_codetext_with_compaction_mode](/python-java/aspose_barcode.generation.qr_ext_codetext_builder/qrextcodetextbuilder/add_codetext_with_compaction_mode/) | `None` | No |  |
| [add_fnc1_first_position](/python-java/aspose_barcode.generation.qr_ext_codetext_builder/qrextcodetextbuilder/add_fnc1_first_position/) | `None` | No | Adds FNC1 in first position to the extended codetext items. |
| [add_fnc1_group_separator](/python-java/aspose_barcode.generation.qr_ext_codetext_builder/qrextcodetextbuilder/add_fnc1_group_separator/) | `None` | No | Adds Group Separator (GS - '\u001D') to the extended codetext items. |
| [add_fnc1_second_position](/python-java/aspose_barcode.generation.qr_ext_codetext_builder/qrextcodetextbuilder/add_fnc1_second_position/) | `None` | No | Adds FNC1 in second position to the extended codetext items. Args: codetext (str): Value of the FNC1 in the second position. |
| [clear](/python-java/aspose_barcode.generation.qr_ext_codetext_builder/qrextcodetextbuilder/clear/) | `def` | No | Clears extended codetext items. Reimplemented from ExtCodetextBuilder. |
| [extended_codetext](/python-java/aspose_barcode.generation.qr_ext_codetext_builder/qrextcodetextbuilder/extended_codetext/) | `Optional[str]` | No | Generates extended codetext from the extended codetext list. Returns: Optional[str]: Extended codetext as a string, or None if not set. Reimplemented from ExtCodetextBuilder. |
