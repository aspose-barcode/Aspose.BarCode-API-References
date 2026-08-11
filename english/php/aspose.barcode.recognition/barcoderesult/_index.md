---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for PHP via Java"
description: "Stores recognized barcode data like SingleDecodeType type, {string} codetext, BarCodeRegionParameters region and other parameters This sample shows how to obtain BarCodeResult."
type: docs
weight: 10
url: /php/aspose.barcode.recognition/barcoderesult/
---

## BarCodeResult class

**Namespace:** `Aspose.Barcode.Recognition`


Stores recognized barcode data like SingleDecodeType type, {string} codetext, BarCodeRegionParameters region and other parameters This sample shows how to obtain BarCodeResult.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [getCodeText](#getcodetext) | No | Gets the code text with encoding. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [CodeBytes](#codebytes) | Read-only |  |
| [CodeType](#codetype) | Read-only |  |
| [CodeTypeName](#codetypename) | Read-only |  |
| [Confidence](#confidence) | Read-only |  |
| [Extended](#extended) | Read-only |  |
| [ReadingQuality](#readingquality) | Read-only |  |
| [Region](#region) | Read-only |  |

### BarCodeResult__construct(BarCodeResultDTO $barCodeResultDTO) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$barCodeResultDTO` | `BarCodeResultDTO` |  |

### getCodeTextgetCodeText(?string $encoding) {#getcodetext}

Gets the code text with encoding.

| Parameter | Type | Description |
| --- | --- | --- |
| `$encoding` | `?string` | The encoding for codetext. |

**Returns:** codeText string containing recognized code text.

### CodeBytes {#codebytes}

**Access:** Read-only

### CodeType {#codetype}

**Access:** Read-only

### CodeTypeName {#codetypename}

**Access:** Read-only

### Confidence {#confidence}

**Access:** Read-only

### Extended {#extended}

**Access:** Read-only

### ReadingQuality {#readingquality}

**Access:** Read-only

**Returns:** float Gets the reading quality. Works for 1D and postal barcodes. Value: The reading quality percent

### Region {#region}

**Access:** Read-only

