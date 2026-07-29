---
title: "Aspose.Barcode.Recognition"
linktitle: "Aspose.Barcode.Recognition"
articleTitle: "Aspose.Barcode.Recognition"
second_title: "Aspose.BarCode for PHP via Java"
description: "Provides classes and enums for reading and interpreting barcodes, including settings, parameters, and result handling."
type: docs
weight: 10
url: /php/aspose/barcode/recognition/
---

## Aspose.Barcode.Recognition namespace

The Aspose.Barcode.Recognition namespace groups all functionality needed to decode barcodes across a wide range of symbologies. It includes reader classes, configuration objects such as AustraliaPostSettings and AztecExtendedParameters, and result types for extracting decoded data in PHP via Java.


## Classes

| Class | Description |
| --- | --- |
| [AustraliaPostSettings](/php/aspose/barcode/recognition/australiapostsettings/) | AustraliaPost decoding parameters. Contains parameters which make influence on recognized data of AustraliaPost symbolog |
| [AztecExtendedParameters](/php/aspose/barcode/recognition/aztecextendedparameters/) | Stores special data of Aztec recognized barcode * This sample shows how to get Aztec raw values |
| [BarCodeExtendedParameters](/php/aspose/barcode/recognition/barcodeextendedparameters/) | Stores extended parameters of recognized barcode |
| [BarCodeReader](/php/aspose/barcode/recognition/barcodereader/) | BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operatio |
| [BarCodeRegionParameters](/php/aspose/barcode/recognition/barcoderegionparameters/) | Represents the recognized barcode's region and barcode angle This sample shows how to get barcode Angle and bounding qua |
| [BarCodeResult](/php/aspose/barcode/recognition/barcoderesult/) | Stores recognized barcode data like SingleDecodeType type, {string} codetext, BarCodeRegionParameters region and other p |
| [BarcodeSettings](/php/aspose/barcode/recognition/barcodesettings/) | The main BarCode decoding parameters. Contains parameters which make influence on recognized data. |
| [CodabarExtendedParameters](/php/aspose/barcode/recognition/codabarextendedparameters/) | Stores a Codabar additional information of recognized barcode |
| [Code128DataPortion](/php/aspose/barcode/recognition/code128dataportion/) | Contains the data of subtype for Code128 type barcode |
| [Code128ExtendedParameters](/php/aspose/barcode/recognition/code128extendedparameters/) | Stores special data of Code128 recognized barcode Represents the recognized barcode's region and barcode angle This samp |
| [DataBarExtendedParameters](/php/aspose/barcode/recognition/databarextendedparameters/) | Stores a DataBar additional information of recognized barcode |
| [DataMatrixExtendedParameters](/php/aspose/barcode/recognition/datamatrixextendedparameters/) | Stores special data of DataMatrix recognized barcode |
| [DecodeType](/php/aspose/barcode/recognition/decodetype/) | Specify the type of barcode to read. This sample shows how to detect Code39 and Code128 barcodes. |
| [DotCodeExtendedParameters](/php/aspose/barcode/recognition/dotcodeextendedparameters/) | Stores special data of DotCode recognized barcode |
| [GS1CompositeBarExtendedParameters](/php/aspose/barcode/recognition/gs1compositebarextendedparameters/) | Stores special data of recognized barcode |
| [MaxiCodeExtendedParameters](/php/aspose/barcode/recognition/maxicodeextendedparameters/) | Stores a MaxiCode additional information of recognized barcode |
| [OneDExtendedParameters](/php/aspose/barcode/recognition/onedextendedparameters/) | Stores special data of 1D recognized barcode like separate codetext and checksum This sample shows how to get 1D barcode |
| [Pdf417ExtendedParameters](/php/aspose/barcode/recognition/pdf417extendedparameters/) | Stores a MacroPdf417 metadata information of recognized barcode This sample shows how to get Macro Pdf417 metadata |
| [QRExtendedParameters](/php/aspose/barcode/recognition/qrextendedparameters/) | Stores a QR Structured Append information of recognized barcode This sample shows how to get QR Structured Append data |
| [Quadrangle](/php/aspose/barcode/recognition/quadrangle/) | Stores a set of four Points that represent a Quadrangle region. |
| [QualitySettings](/php/aspose/barcode/recognition/qualitysettings/) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by em |
| [RecognitionAbortedException](/php/aspose/barcode/recognition/recognitionabortedexception/) |  |

## Enums

| Enum | Description |
| --- | --- |
| [BarCodeConfidence](/php/aspose/barcode/recognition/barcodeconfidence/) | Contains recognition confidence level This sample shows how BarCodeConfidence changed, depending on barcode type Moderat |
| [BarcodeQualityMode](/php/aspose/barcode/recognition/barcodequalitymode/) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality r |
| [ChecksumValidation](/php/aspose/barcode/recognition/checksumvalidation/) | Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must cont |
| [Code128SubType](/php/aspose/barcode/recognition/code128subtype/) | Contains types of Code128 subset |
| [ComplexBackgroundMode](/php/aspose/barcode/recognition/complexbackgroundmode/) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [CustomerInformationInterpretingType](/php/aspose/barcode/recognition/customerinformationinterpretingtype/) | Defines the interpreting type(C_TABLE or N_TABLE) of customer information for AustralianPost BarCode. |
| [DeconvolutionMode](/php/aspose/barcode/recognition/deconvolutionmode/) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function |
| [InverseImageMode](/php/aspose/barcode/recognition/inverseimagemode/) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [XDimensionMode](/php/aspose/barcode/recognition/xdimensionmode/) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |

