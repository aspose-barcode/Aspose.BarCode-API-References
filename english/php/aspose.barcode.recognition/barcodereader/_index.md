---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for PHP via Java"
description: "BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. This sample shows how to detect Code39 and Code128 barcode"
type: docs
weight: 10
url: /php/aspose.barcode.recognition/barcodereader/
---

## BarCodeReader class

**Namespace:** `Aspose.Barcode.Recognition`


BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. This sample shows how to detect Code39 and Code128 barcodes.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [containsAny](#containsany) | No | Determines whether any of the given decode types is included into |
| [exportToXml](#exporttoxml) | No | Exports BarCode properties to the xml-file specified |
| [importFromXml](#importfromxml) | Yes | Import BarCode properties from xml file |
| [init](#init) | No |  |
| [setBarCodeImage](#setbarcodeimage) | No | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality. |
| [setBarCodeReadType](#setbarcodereadtype) | No | Sets SingleDecodeType type array for recognition. Must be called before readBarCodes() method. This sample shows how to detect Code39 and Code128 barcodes. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [BarCodeDecodeType](#barcodedecodetype) | Read-only |  |
| [FoundBarCodes](#foundbarcodes) | Read-only | Reads BarCodeResult from the image. Value: The recognized BarCodeResult array |
| [FoundCount](#foundcount) | Read-only | Gets recognized barcodes count This sample shows how to read barcodes with BarCodeReader Value: The recognized barcodes count |
| [Timeout](#timeout) | Read/Write | Gets the timeout of recognition process in milliseconds. |

### BarCodeReader__construct($imageResource, $areas, $decodeTypes) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$imageResource` | `` |  |
| `$areas` | `` |  |
| `$decodeTypes` | `` |  |

### containsAnycontainsAny($decodeTypes) {#containsany}

Determines whether any of the given decode types is included into

| Parameter | Type | Description |
| --- | --- | --- |
| `$decodeTypes` | `` |  |

**Returns:** bool Value is a true if any types are included into.

### exportToXmlexportToXml(string $xmlFile) {#exporttoxml}

Exports BarCode properties to the xml-file specified

| Parameter | Type | Description |
| --- | --- | --- |
| `$xmlFile` | `string` |  |

**Returns:** bool Whether or not export completed successfully. Returns True in case of success; False Otherwise

### importFromXmlimportFromXml(string $resource) (static) {#importfromxml}

Import BarCode properties from xml file

| Parameter | Type | Description |
| --- | --- | --- |
| `$resource` | `string` |  |

**Returns:** BarCodeReader

### initinit() {#init}

### setBarCodeImagesetBarCodeImage($imageResource, ?Rectangle ... $areas) {#setbarcodeimage}

QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality.

| Parameter | Type | Description |
| --- | --- | --- |
| `$imageResource` | `` |  |
| `$areas` | `?Rectangle ...` |  |

### setBarCodeReadTypesetBarCodeReadType(int ... $types) {#setbarcodereadtype}

Sets SingleDecodeType type array for recognition. Must be called before readBarCodes() method. This sample shows how to detect Code39 and Code128 barcodes.

| Parameter | Type | Description |
| --- | --- | --- |
| `$types` | `int ...` |  |

### BarCodeDecodeType {#barcodedecodetype}

**Access:** Read-only

### FoundBarCodes {#foundbarcodes}

**Access:** Read-only

Reads BarCodeResult from the image. Value: The recognized BarCodeResult array

### FoundCount {#foundcount}

**Access:** Read-only

Gets recognized barcodes count This sample shows how to read barcodes with BarCodeReader Value: The recognized barcodes count

### Timeout {#timeout}

**Access:** Read/Write

**Returns:** int timeout.

Gets the timeout of recognition process in milliseconds.

Sets the timeout of recognition process in milliseconds.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

