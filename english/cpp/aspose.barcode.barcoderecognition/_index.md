---
title: Aspose::BarCode::BarCodeRecognition namespace
linktitle: Aspose::BarCode::BarCodeRecognition
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use Aspose::BarCode::BarCodeRecognition namespace in C++.'
type: docs
weight: 200
url: /cpp/aspose.barcode.barcoderecognition/
---



## Classes

| Class | Description |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. Implementation should be provided by user. |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost decoding parameters. Contains parameters which make influence on recognized data of AustraliaPost symbology. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Stores special data of Aztec recognized barcode |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Stores extended parameters of recognized barcode |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Represents the recognized barcode's region and barcode angle |
| [BarCodeResult](./barcoderesult/) | Stores recognized barcode data like [SingleDecodeType](./singledecodetype/) type, **System::String** codetext, [BarCodeRegionParameters](./barcoderegionparameters/) region and other parameters |
| [BarcodeSettings](./barcodesettings/) | The main [BarCode](../aspose.barcode/) decoding parameters. Contains parameters which make influence on recognized data. |
| [BaseDecodeType](./basedecodetype/) | Base class for [MultiDecodeType](./multidecodetype/) and [SingleDecodeType](./singledecodetype/). |
| [BaseExtendedParameters](./baseextendedparameters/) | Basic class for extended parameters of recognized barcode storing |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Stores a Codabar additional information of recognized barcode |
| [Code128DataPortion](./code128dataportion/) | Contains the data of subtype for Code128 type barcode |
| [Code128ExtendedParameters](./code128extendedparameters/) | Stores special data of Code128 recognized barcode |
| [DataBarExtendedParameters](./databarextendedparameters/) | Stores a DataBar additional information of recognized barcode |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Stores special data of DataMatrix recognized barcode |
| [DecodeType](./decodetype/) | Specify the type of barcode to read. |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | General exception thrown by [BarCodeReader](./barcodereader/), inherited from BarCodeException |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | Represents recognition abort exception which is thrown in timeout exceeding during recognition with [BarCodeReader](./barcodereader/). |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Stores special data of DotCode recognized barcode |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Stores special data of **GS1 Composite Bar** recognized barcode |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Stores a MaxiCode additional information of recognized barcode |
| [MultiDecodeType](./multidecodetype/) | Composite decode type. |
| [MultyDecodeType](./multydecodetype/) | Composite decode type. |
| [OneDExtendedParameters](./onedextendedparameters/) | Stores special data of 1D recognized barcode like separate codetext and checksum |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Stores a MacroPdf417 metadata information of recognized barcode |
| [QRExtendedParameters](./qrextendedparameters/) | Stores a QR Structured Append information of recognized barcode |
| [Quadrangle](./quadrangle/) | Stores a set of four [Point](../)s that represent a [Quadrangle](./quadrangle/) region. |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./qualitysettings/) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./qualitysettings/) is NormalQuality. |
| [SingleDecodeType](./singledecodetype/) | Single decode type. See decode type to get instance. |
## Enums

| Enum | Description |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | Contains types of Code128 subset |
| [BarCodeConfidence](./barcodeconfidence/) | Contains recognition confidence level |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |
