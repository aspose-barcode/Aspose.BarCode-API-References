---
title: Aspose.BarCode.BarCodeRecognition
second_title: Aspose.BarCode for .NET API Reference
description: The Aspose.BarCode.BarCodeRecognition contains tools for the 1D/2D barcodes recognition
type: docs
weight: 20
url: /net/aspose.barcode.barcoderecognition/
---
The **Aspose.BarCode.BarCodeRecognition** contains tools for the 1D/2D barcodes recognition.

## Classes

| Class | Description |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost decoding parameters. Contains parameters which make influence on recognized data of AustraliaPost symbology. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Stores special data of Aztec recognized barcode |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Stores extended parameters of recognized barcode |
| [BarCodeReader](./barcodereader/) | BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. |
| [BarCodeRecognitionException](./barcoderecognitionexception/) | General exception thrown by BarCodeReader, inherited from BarCodeException |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Represents the recognized barcode's region and barcode angle |
| [BarCodeResult](./barcoderesult/) | Stores recognized barcode data like [`SingleDecodeType`](../aspose.barcode.barcoderecognition/singledecodetype/) type, String codetext, [`BarCodeRegionParameters`](../aspose.barcode.barcoderecognition/barcoderegionparameters/) region and other parameters |
| [BarcodeSettings](./barcodesettings/) | The main BarCode decoding parameters. Contains parameters which make influence on recognized data. |
| [BaseDecodeType](./basedecodetype/) | Base class for MultiDecodeType and SingleDecodeType. |
| [BaseExtendedParameters](./baseextendedparameters/) | Basic class for extended parameters of recognized barcode storing |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Stores a Codabar additional information of recognized barcode |
| [Code128DataPortion](./code128dataportion/) | Contains the data of subtype for Code128 type barcode |
| [Code128ExtendedParameters](./code128extendedparameters/) | Stores special data of Code128 recognized barcode |
| [DataBarExtendedParameters](./databarextendedparameters/) | Stores a DataBar additional information of recognized barcode |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Stores special data of DataMatrix recognized barcode |
| [DecodeType](./decodetype/) | Specify the type of barcode to read. |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Stores special data of DotCode recognized barcode |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Stores special data of **GS1 Composite Bar** recognized barcode |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Stores a MaxiCode additional information of recognized barcode |
| [MultiDecodeType](./multidecodetype/) | Composite decode type. |
| [MultyDecodeType](./multydecodetype/) | Composite decode type. |
| [OneDExtendedParameters](./onedextendedparameters/) | Stores special data of 1D recognized barcode like separate codetext and checksum |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Stores a MacroPdf417 metadata information of recognized barcode |
| [QRExtendedParameters](./qrextendedparameters/) | Stores a QR Structured Append information of recognized barcode |
| [Quadrangle](./quadrangle/) | Stores a set of four Points that represent a [`Quadrangle`](../aspose.barcode.barcoderecognition/quadrangle/) region. |
| [QualitySettings](./qualitysettings/) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of QualitySettings is NormalQuality. |
| [RecognitionAbortedException](./recognitionabortedexception/) | Represents recognition abort exception which is thrown in timeout exceeding during recognition with BarCodeReader. |
| [SingleDecodeType](./singledecodetype/) | Single decode type. See decode type to get instance. |
## Interfaces

| Interface | Description |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. Implementation should be provided by user. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | Contains recognition confidence level |
| [BarcodeQualityMode](./barcodequalitymode/) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition. |
| [ChecksumValidation](./checksumvalidation/) | Enable checksum validation during recognition for 1D and Postal barcodes. |
| [Code128SubType](./code128subtype/) | Contains types of Code128 subset |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [DeconvolutionMode](./deconvolutionmode/) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology. |
| [InverseImageMode](./inverseimagemode/) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [XDimensionMode](./xdimensionmode/) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |


