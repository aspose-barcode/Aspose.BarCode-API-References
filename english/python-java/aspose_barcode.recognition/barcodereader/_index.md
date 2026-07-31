---
title: "BarCodeReader Class"
linktitle: "BarCodeReader"
articleTitle: "BarCodeReader"
second_title: "Aspose.BarCode for Python via Java"
description: "BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. This sample shows "
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition.barcode_reader/barcodereader/
---

## BarCodeReader class

**Module:** `aspose_barcode.recognition.barcode_reader`


BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. This sample shows how to detect Code39 and Code128 barcodes.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](./barcodereader/) | Initializes a new instance of the BarCodeReader. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [abort](./abort/) | `None` | No |  |
| [barcode_image](./barcode_image/) | `None` | No | Sets bitmap image and areas for Recognition. Must be called before ReadBarCodes() method. This sample shows how to detect Code39 and Code128 barcodes. |
| [barcode_settings](./barcode_settings/) | `Optional[BarcodeSettings]` | No |  |
| [contains_any](./contains_any/) | `bool` | No |  |
| [export_to_xml](./export_to_xml/) | `bool` | No |  |
| [found_barcodes](./found_barcodes/) | `Optional[List[BarCodeResult]]` | No |  |
| [found_count](./found_count/) | `int` | No |  |
| [from_image_with_areas](./from_image_with_areas/) | `def` | No | Initializes a new instance of the BarCodeReader. |
| [import_from_xml](./import_from_xml/) | `BarCodeReader` | No | Imports BarCode properties from the specified XML file. |
| [read_barcodes](./read_barcodes/) | `Optional[List[BarCodeResult]]` | No |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [barcode_read_type](./barcode_read_type/) | `Union[List[DecodeType], DecodeType]` | Sets SingleDecodeType type array for Recognition. Must be called before readBarCodes() method. This sample shows how to detect Code39 and Code128 barcodes. |
| [quality_settings](./quality_settings/) | `Optional[QualitySettings]` |  |
| [timeout](./timeout/) | `int` |  |
