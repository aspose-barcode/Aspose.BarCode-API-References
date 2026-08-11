---
title: "aspose_barcode.recognition"
linktitle: "aspose_barcode.recognition"
second_title: "Aspose.BarCode for Python via Java"
description: "The aspose_barcode.recognition namespace offers classes and enums for configuring, reading, and interpreting various barcode types in Aspose.BarCode for Python via Java."
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition/
---

## aspose_barcode.recognition module

This reference details the barcode recognition API, covering settings objects such as AustraliaPostSettings and AztecExtendedParameters, as well as core classes like BarCodeReader and BarCodeResult. Use these types to customize scanning parameters, define regions, and retrieve decoded barcode information.

## Classes

| Class | Description |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost decoding parameters. Contains parameters which influence recognized data of AustraliaPost symbology. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Stores special data of Aztec recognized barcode. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) |  |
| [BarCodeReader](./barcodereader/) | BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operatio |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Represents the recognized barcode's region and barcode angle. This sample shows how to get barcode Angle and bounding qu |
| [BarCodeResult](./barcoderesult/) | Stores recognized barcode data like SingleDecodeType type,. codetext, BarCodeRegionParameters region and other parameter |
| [BarcodeSettings](./barcodesettings/) | Contains settings for barcode recognition. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Stores a Codabar additional information of recognized barcode. |
| [Code128DataPortion](./code128dataportion/) | Contains the data of subtype for Code128 type barcode. |
| [Code128ExtendedParameters](./code128extendedparameters/) | Stores special data of Code128 recognized barcode. Represents the recognized barcode's region and barcode angle This sam |
| [DataBarExtendedParameters](./databarextendedparameters/) | Stores a DataBar additional information of recognized barcode. |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Stores special data of DataMatrix recognized barcode This sample shows how to get DataMatrix raw values. |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) |  |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Stores additional information for GS1 Composite Bar recognized barcodes. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Stores a MaxiCode additional information of recognized barcode. |
| [OneDExtendedParameters](./onedextendedparameters/) | Stores special data of 1D recognized barcode like separate codetext and checksum. This sample shows how to get 1D barcod |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Stores a MacroPdf417 metadata information of recognized barcode. This sample shows how to get Macro Pdf417 metadata |
| [QRExtendedParameters](./qrextendedparameters/) | Stores a QR Structured Append information of recognized barcode. This sample shows how to get QR Structured Append data |
| [Quadrangle](./quadrangle/) | Stores a set of four Points that represent a Quadrangle region. |
| [QualitySettings](./qualitysettings/) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by em |
| [RecognitionAbortedException](./recognitionabortedexception/) | Exception raised when barcode recognition is aborted. |

## Enums

| Enum | Description |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | Contains recognition confidence level. This sample shows how BarCodeConfidence changed, depending on barcode type |
| [BarcodeQualityMode](./barcodequalitymode/) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality r |
| [ChecksumValidation](./checksumvalidation/) | Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must cont |
| [Code128SubType](./code128subtype/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [CustomerInformationInterpretingType](./customerinformationinterpretingtype/) | Defines the interpreting type(C_TABLE or N_TABLE) of customer information for AustralianPost BarCode. |
| [DecodeType](./decodetype/) | Specify the type of barcode to read. This sample shows how to detect Code39 and Code128 barcodes. |
| [DeconvolutionMode](./deconvolutionmode/) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function |
| [InverseImageMode](./inverseimagemode/) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [XDimensionMode](./xdimensionmode/) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. This sample shows  |

