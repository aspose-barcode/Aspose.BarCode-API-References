---
title: Aspose.BarCode.BarCodeRecognition
second_title: Aspose.BarCode for .NET API Reference
description: The  Aspose.BarCode.BarCodeRecognition contains tools for the 1D/2D barcodes recognition.
type: docs
weight: 20
url: /net/aspose.barcode.barcoderecognition/
---
The  **Aspose.BarCode.BarCodeRecognition** contains tools for the 1D/2D barcodes recognition.

## Classes

| Class | Description |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | The AustraliaPostSettings class is AustraliaPost decoding parameters that contains parameters which make influence on recognized data of AustraliaPost symbology. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | The BarCodeExtendedParameters class stores extended parameters of recognized barcode such as Code128, DataBar, MaxiCode and Pdf417. |
| [BarCodeReader](./barcodereader/) | The BarCodeReader class detects or reads one or multiple barcodes from an image. To read barcodes from an image or stream create an instance of this class and perform ReadBarCodes operation. |
| [BarCodeRecognitionException](./barcoderecognitionexception/) | General exception thrown by BarCodeReader, inherited from BarCodeException |
| [BarCodeRegionParameters](./barcoderegionparameters/) | The BarCodeRegionParameters class represents the recognized barcode's region and barcode angle.  |
| [BarCodeResult](./barcoderesult/) | The BarCodeResult class stores recognized barcode data like [`SingleDecodeType`](../aspose.barcode.barcoderecognition/singledecodetype/) type, String codetext, [`BarCodeRegionParameters`](../aspose.barcode.barcoderecognition/barcoderegionparameters/) region and other parameters |
| [BarcodeSettings](./barcodesettings/) | The BarcodeSettings class represents main BarCode decoding parameters that contain parameters which make an influence on recognized data such as AustraliaPost, ChecksumValidation, DetectEncoding and StripFNC. |
| [BarcodeSvmDetectorSettings](./barcodesvmdetectorsettings/) | The BarcodeSvmDetectorSettings class provides quality, performance, threshold for detected regions, windows size, and other configurations to detect barcodes. |
| [BaseDecodeType](./basedecodetype/) | The BaseDecodeType class is the base class for MultyDecodeType and SingleDecodeType. |
| [BaseExtendedParameters](./baseextendedparameters/) | The BaseExtendedParameters is the basic class for extended parameters of recognized barcode storing. |
| [Code128DataPortion](./code128dataportion/) | The Code128DataPortion class contains the data of subtype for Code128 type barcode. |
| [Code128ExtendedParameters](./code128extendedparameters/) | The Code128ExtendedParameters class stores special data of Code128 recognized barcode. |
| [DataBarExtendedParameters](./databarextendedparameters/) | The DataBarExtendedParameters class stores a DataBar additional information of recognized barcode. |
| [DecodeType](./decodetype/) | The DecodeType class represents the barcode symbologies of barcode to read such as Aztec, Code128 and ISBN. |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | The DotCodeExtendedParameters class stores special data of DotCode recognized barcode. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | The MaxiCodeExtendedParameters class stores a MaxiCode additional information of recognized barcode. |
| [MultyDecodeType](./multydecodetype/) | The MultyDecodeType class represents a composite decode type that combines SingleDecodeType and MultiDecode types. |
| [OneDExtendedParameters](./onedextendedparameters/) | The OneDExtendedParameters class stores special data of 1D recognized barcode like separate codetext and checksum. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | The Pdf417ExtendedParameters class stores a MacroPdf417 metadata information of recognized barcode. |
| [QRExtendedParameters](./qrextendedparameters/) | The QRExtendedParameters class stores a QR Structured Append information of recognized barcode. |
| [Quadrangle](./quadrangle/) | The Quadrangle class stores a set of four Points that represent a [`Quadrangle`](../aspose.barcode.barcoderecognition/quadrangle/) region. |
| [QualitySettings](./qualitysettings/) | The QualitySettings class allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality. |
| [RecognitionAbortedException](./recognitionabortedexception/) | The RecognitionAbortedException class represents recognition abort exception which is thrown in timeout exceeding during recognition with BarCodeReader. |
| [SingleDecodeType](./singledecodetype/) | The SingleDecodeType class represents single decode type. See decode type to get instance. |
## Interfaces

| Interface | Description |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. Implementation should be provided by user. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | Contains recognition confidence level |
| [ChecksumValidation](./checksumvalidation/) | Enable checksum validation during recognition for 1D and Postal barcodes. |
| [Code128SubType](./code128subtype/) | Contains types of Code128 subset |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
