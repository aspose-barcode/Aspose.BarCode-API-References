---
title: "Aspose.Barcode.Recognition"
linktitle: "Aspose.Barcode.Recognition"
articleTitle: "Aspose.Barcode.Recognition"
second_title: "Aspose.BarCode for PHP via Java"
description: "The Aspose.Barcode.Recognition namespace offers classes and enums for configuring, reading, and interpreting various barcode types in PHP via Java."
type: docs
weight: 10
url: /php/aspose/barcode/recognition/
---

## Aspose.Barcode.Recognition namespace

Use these types to customize barcode decoding settings such as regional parameters, extended options for specific symbologies, and to retrieve detailed results from scanned images. The namespace serves as the core API for barcode recognition functionality within the Aspose.BarCode for PHP via Java library.


## Classes

| Class | Description |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost decoding parameters. Contains parameters which make influence on recognized data of AustraliaPost symbolog |
| [AztecExtendedParameters](./aztecextendedparameters/) | Stores special data of Aztec recognized barcode * This sample shows how to get Aztec raw values |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Stores extended parameters of recognized barcode |
| [BarCodeReader](./barcodereader/) | BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operatio |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Represents the recognized barcode's region and barcode angle This sample shows how to get barcode Angle and bounding qua |
| [BarCodeResult](./barcoderesult/) | Stores recognized barcode data like SingleDecodeType type, {string} codetext, BarCodeRegionParameters region and other p |
| [BarcodeSettings](./barcodesettings/) | The main BarCode decoding parameters. Contains parameters which make influence on recognized data. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Stores a Codabar additional information of recognized barcode |
| [Code128DataPortion](./code128dataportion/) | Contains the data of subtype for Code128 type barcode |
| [Code128ExtendedParameters](./code128extendedparameters/) | Stores special data of Code128 recognized barcode Represents the recognized barcode's region and barcode angle This samp |
| [DataBarExtendedParameters](./databarextendedparameters/) | Stores a DataBar additional information of recognized barcode |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Stores special data of DataMatrix recognized barcode |
| [DecodeType](./decodetype/) | Specify the type of barcode to read. This sample shows how to detect Code39 and Code128 barcodes. |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Stores special data of DotCode recognized barcode |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Stores special data of recognized barcode |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Stores a MaxiCode additional information of recognized barcode |
| [OneDExtendedParameters](./onedextendedparameters/) | Stores special data of 1D recognized barcode like separate codetext and checksum This sample shows how to get 1D barcode |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Stores a MacroPdf417 metadata information of recognized barcode This sample shows how to get Macro Pdf417 metadata |
| [QRExtendedParameters](./qrextendedparameters/) | Stores a QR Structured Append information of recognized barcode This sample shows how to get QR Structured Append data |
| [Quadrangle](./quadrangle/) | Stores a set of four Points that represent a Quadrangle region. |
| [QualitySettings](./qualitysettings/) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by em |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |

## Enums

| Enum | Description |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | Contains recognition confidence level This sample shows how BarCodeConfidence changed, depending on barcode type Moderat |
| [BarcodeQualityMode](./barcodequalitymode/) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality r |
| [ChecksumValidation](./checksumvalidation/) | Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must cont |
| [Code128SubType](./code128subtype/) | Contains types of Code128 subset |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [CustomerInformationInterpretingType](./customerinformationinterpretingtype/) | Defines the interpreting type(C_TABLE or N_TABLE) of customer information for AustralianPost BarCode. |
| [DeconvolutionMode](./deconvolutionmode/) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function |
| [InverseImageMode](./inverseimagemode/) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [XDimensionMode](./xdimensionmode/) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |

