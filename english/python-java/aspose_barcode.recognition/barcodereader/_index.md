---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for Python via Java"
description: "BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. This sample shows "
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition/barcodereader/
---

## BarCodeReader class

**Module:** `aspose_barcode.recognition.barcode_reader`


BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. This sample shows how to detect Code39 and Code128 barcodes.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | Initializes a new instance of the BarCodeReader. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [abort](#abort) | `None` | No |  |
| [barcode_image](#barcode_image) | `None` | No | Sets bitmap image and areas for Recognition. Must be called before ReadBarCodes() method. This sample shows how to detect Code39 and Code128 barcodes. |
| [barcode_settings](#barcode_settings) | `Optional[BarcodeSettings]` | No |  |
| [contains_any](#contains_any) | `bool` | No |  |
| [export_to_xml](#export_to_xml) | `bool` | No |  |
| [found_barcodes](#found_barcodes) | `Optional[List[BarCodeResult]]` | No |  |
| [found_count](#found_count) | `int` | No |  |
| [from_image_with_areas](#from_image_with_areas) | `def` | No | Initializes a new instance of the BarCodeReader. |
| [import_from_xml](#import_from_xml) | `BarCodeReader` | No | Imports BarCode properties from the specified XML file. |
| [read_barcodes](#read_barcodes) | `Optional[List[BarCodeResult]]` | No |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [barcode_read_type](#barcode_read_type) | `Union[List[DecodeType], DecodeType]` | Sets SingleDecodeType type array for Recognition. Must be called before readBarCodes() method. This sample shows how to detect Code39 and Code128 barcodes. |
| [quality_settings](#quality_settings) | `Optional[QualitySettings]` |  |
| [timeout](#timeout) | `int` |  |

### BarCodeReader Constructor {#constructor}

```python
__init__(self, Optional[Union[str, os.PathLike, bytes, BinaryIO, Image.Image, None]] image, Optional[Union[List[DecodeType], DecodeType, None]] decode_types) -> def
```

Initializes a new instance of the BarCodeReader.

| Parameter | Type | Description |
| --- | --- | --- |
| `image` | `Optional[Union[str, os.PathLike, bytes, BinaryIO, Image.Image, None]]` |  |
| `decode_types` | `Optional[Union[List[DecodeType], DecodeType, None]]` |  |

### BarCodeReader.abort {#abort}

```python
abort(self)
```

### BarCodeReader.barcode_image {#barcode_image}

```python
barcode_image(self, Optional[Union[str, "os.PathLike"], bytes, BinaryIO, Image.Image, None] image, Optional[Union[List[RectLike], RectLike]] areas)
```

Sets bitmap image and areas for Recognition. Must be called before ReadBarCodes() method. This sample shows how to detect Code39 and Code128 barcodes.

| Parameter | Type | Description |
| --- | --- | --- |
| `image` | `Optional[Union[str, "os.PathLike"], bytes, BinaryIO, Image.Image, None]` |  |
| `areas` | `Optional[Union[List[RectLike], RectLike]]` |  |

### BarCodeReader.barcode_settings {#barcode_settings}

```python
barcode_settings(self) -> Optional[BarcodeSettings]
```

**Return Type:** `Optional[BarcodeSettings]`

### BarCodeReader.contains_any {#contains_any}

```python
contains_any(self, Union[List[DecodeType], DecodeType] decode_types) -> bool
```

| Parameter | Type | Description |
| --- | --- | --- |
| `decode_types` | `Union[List[DecodeType], DecodeType]` |  |

**Return Type:** `bool`

### BarCodeReader.export_to_xml {#export_to_xml}

```python
export_to_xml(self, str xml_file) -> bool
```

| Parameter | Type | Description |
| --- | --- | --- |
| `xml_file` | `str` |  |

**Return Type:** `bool`

### BarCodeReader.found_barcodes {#found_barcodes}

```python
found_barcodes(self) -> Optional[List[BarCodeResult]]
```

**Return Type:** `Optional[List[BarCodeResult]]`

### BarCodeReader.found_count {#found_count}

```python
found_count(self) -> int
```

**Return Type:** `int`

### BarCodeReader.from_image_with_areas {#from_image_with_areas}

```python
from_image_with_areas(self, cls, Optional[Union[str, os.PathLike, bytes, BinaryIO, Image.Image]] image, Optional[Union[List[RectLike], RectLike]] areas, Optional[Union[List[DecodeType], DecodeType]] decode_types) -> def
```

Initializes a new instance of the BarCodeReader.

| Parameter | Type | Description |
| --- | --- | --- |
| `cls` | `` |  |
| `image` | `Optional[Union[str, os.PathLike, bytes, BinaryIO, Image.Image]]` |  |
| `areas` | `Optional[Union[List[RectLike], RectLike]]` |  |
| `decode_types` | `Optional[Union[List[DecodeType], DecodeType]]` |  |

**Return Type:** `def`

### BarCodeReader.import_from_xml {#import_from_xml}

```python
import_from_xml(self, cls, str xml_file) -> BarCodeReader
```

Imports BarCode properties from the specified XML file.

| Parameter | Type | Description |
| --- | --- | --- |
| `cls` | `` |  |
| `xml_file` | `str` |  |

**Return Type:** `BarCodeReader`

### BarCodeReader.read_barcodes {#read_barcodes}

```python
read_barcodes(self) -> Optional[List[BarCodeResult]]
```

**Return Type:** `Optional[List[BarCodeResult]]`

### BarCodeReader.barcode_read_type {#barcode_read_type}

**Type:** `Union[List[DecodeType], DecodeType]`

Sets SingleDecodeType type array for Recognition. Must be called before readBarCodes() method. This sample shows how to detect Code39 and Code128 barcodes.

| Parameter | Type | Description |
| --- | --- | --- |
| `types` | `Union[List[DecodeType], DecodeType]` |  |

### BarCodeReader.quality_settings {#quality_settings}

**Type:** `Optional[QualitySettings]`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `QualitySettings` |  |

### BarCodeReader.timeout {#timeout}

**Type:** `int`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

