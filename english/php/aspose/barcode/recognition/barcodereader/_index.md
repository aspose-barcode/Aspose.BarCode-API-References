---
title: "BarCodeReader Class"
linktitle: "BarCodeReader"
articleTitle: "BarCodeReader"
second_title: "Aspose.BarCode for PHP via Java"
description: "BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. This sample shows how to detect Code39 and Code128 barcode"
type: docs
weight: 10
url: /php/aspose/barcode/recognition/barcodereader/
---

## BarCodeReader class

**Namespace:** `Aspose.Barcode.Recognition`


BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. This sample shows how to detect Code39 and Code128 barcodes.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](/php/aspose/barcode/recognition/barcodereader/barcodereader/) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [containsAny](/php/aspose/barcode/recognition/barcodereader/containsany/) | No | Determines whether any of the given decode types is included into |
| [exportToXml](/php/aspose/barcode/recognition/barcodereader/exporttoxml/) | No | Exports BarCode properties to the xml-file specified |
| [importFromXml](/php/aspose/barcode/recognition/barcodereader/importfromxml/) | Yes | Import BarCode properties from xml file |
| [init](/php/aspose/barcode/recognition/barcodereader/init/) | No |  |
| [setBarCodeImage](/php/aspose/barcode/recognition/barcodereader/setbarcodeimage/) | No | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality. |
| [setBarCodeReadType](/php/aspose/barcode/recognition/barcodereader/setbarcodereadtype/) | No | Sets SingleDecodeType type array for recognition. Must be called before readBarCodes() method. This sample shows how to detect Code39 and Code128 barcodes. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [BarCodeDecodeType](/php/aspose/barcode/recognition/barcodereader/barcodedecodetype/) | Read-only |  |
| [FoundBarCodes](/php/aspose/barcode/recognition/barcodereader/foundbarcodes/) | Read-only | Reads BarCodeResult from the image. Value: The recognized BarCodeResult array |
| [FoundCount](/php/aspose/barcode/recognition/barcodereader/foundcount/) | Read-only | Gets recognized barcodes count This sample shows how to read barcodes with BarCodeReader Value: The recognized barcodes count |
| [Timeout](/php/aspose/barcode/recognition/barcodereader/timeout/) | Read/Write | Gets the timeout of recognition process in milliseconds. |
