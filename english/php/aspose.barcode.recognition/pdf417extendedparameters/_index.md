---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "Stores a MacroPdf417 metadata information of recognized barcode This sample shows how to get Macro Pdf417 metadata"
type: docs
weight: 10
url: /php/aspose.barcode.recognition/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

**Namespace:** `Aspose.Barcode.Recognition`


Stores a MacroPdf417 metadata information of recognized barcode This sample shows how to get Macro Pdf417 metadata


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [isCode128Emulation](#iscode128emulation) | No | Flag that indicates that the MicroPdf417 barcode encoded with 908, 909, 910 or 911 Code 128 emulation codewords. |
| [isLinked](#islinked) | No | Flag that indicates that the barcode must be linked to 1D barcode. Value: Linkage flag |
| [isReaderInitialization](#isreaderinitialization) | No | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Value: Reader initialization flag |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [MacroPdf417Addressee](#macropdf417addressee) | Read-only | Macro PDF417 addressee name (optional). |
| [MacroPdf417Checksum](#macropdf417checksum) | Read-only | Macro PDF417 checksum (optional). |
| [MacroPdf417FileID](#macropdf417fileid) | Read-only | Gets the file ID of the barcode, only available with MacroPdf417.Value: The file ID for MacroPdf417 |
| [MacroPdf417FileName](#macropdf417filename) | Read-only | Macro PDF417 file name (optional). |
| [MacroPdf417FileSize](#macropdf417filesize) | Read-only | Macro PDF417 file size (optional). |
| [MacroPdf417SegmentID](#macropdf417segmentid) | Read-only | Gets the segment ID of the barcode,only available with MacroPdf417.Value: The segment ID of the barcode. |
| [MacroPdf417SegmentsCount](#macropdf417segmentscount) | Read-only | Gets macro pdf417 barcode segments count. Default value is -1.Value: Segments count. |
| [MacroPdf417Sender](#macropdf417sender) | Read-only | Macro PDF417 sender name (optional). |
| [MacroPdf417Terminator](#macropdf417terminator) | Read-only | Indicates whether the segment is the last segment of a Macro PDF417 file. |
| [MacroPdf417TimeStamp](#macropdf417timestamp) | Read-only | Macro PDF417 time stamp (optional). |

### Pdf417ExtendedParameters__construct(Pdf417ExtendedParametersDTO $pdf417ExtendedParametersDTO) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$pdf417ExtendedParametersDTO` | `Pdf417ExtendedParametersDTO` |  |

### isCode128EmulationisCode128Emulation() {#iscode128emulation}

Flag that indicates that the MicroPdf417 barcode encoded with 908, 909, 910 or 911 Code 128 emulation codewords.

**Returns:** bool 128 emulation flag

### isLinkedisLinked() {#islinked}

Flag that indicates that the barcode must be linked to 1D barcode. Value: Linkage flag

### isReaderInitializationisReaderInitialization() {#isreaderinitialization}

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Value: Reader initialization flag

### MacroPdf417Addressee {#macropdf417addressee}

**Access:** Read-only

**Returns:** string Addressee name.

Macro PDF417 addressee name (optional).

### MacroPdf417Checksum {#macropdf417checksum}

**Access:** Read-only

**Returns:** int Checksum.

Macro PDF417 checksum (optional).

### MacroPdf417FileID {#macropdf417fileid}

**Access:** Read-only

Gets the file ID of the barcode, only available with MacroPdf417.Value: The file ID for MacroPdf417

### MacroPdf417FileName {#macropdf417filename}

**Access:** Read-only

**Returns:** string File name.

Macro PDF417 file name (optional).

### MacroPdf417FileSize {#macropdf417filesize}

**Access:** Read-only

**Returns:** int File size.

Macro PDF417 file size (optional).

### MacroPdf417SegmentID {#macropdf417segmentid}

**Access:** Read-only

Gets the segment ID of the barcode,only available with MacroPdf417.Value: The segment ID of the barcode.

### MacroPdf417SegmentsCount {#macropdf417segmentscount}

**Access:** Read-only

Gets macro pdf417 barcode segments count. Default value is -1.Value: Segments count.

### MacroPdf417Sender {#macropdf417sender}

**Access:** Read-only

**Returns:** string Sender name

Macro PDF417 sender name (optional).

### MacroPdf417Terminator {#macropdf417terminator}

**Access:** Read-only

Indicates whether the segment is the last segment of a Macro PDF417 file.

### MacroPdf417TimeStamp {#macropdf417timestamp}

**Access:** Read-only

**Returns:** DateTime Time stamp.

Macro PDF417 time stamp (optional).

