---
title: "aspose_barcode.recognition"
linktitle: "aspose_barcode.recognition"
articleTitle: "aspose_barcode.recognition"
second_title: "Aspose.BarCode for Python via Java"
description: "The aspose_barcode.recognition namespace offers classes and enums for configuring, reading, and interpreting various barcode symbologies in Aspose.BarCode for Python via Java."
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition/
---

## aspose_barcode.recognition module

Use these types to customize barcode detection parameters, access detailed recognition results, and handle region-specific scanning. The namespace serves as the core API for barcode recognition tasks within the Aspose.BarCode library.


## Classes

| Class | Description |
| --- | --- |
| [AustraliaPostSettings](/python-java/aspose_barcode.recognition/australiapostsettings/) | AustraliaPost decoding parameters. Contains parameters which influence recognized data of AustraliaPost symbology. |
| [AztecExtendedParameters](/python-java/aspose_barcode.recognition/aztecextendedparameters/) | Stores special data of Aztec recognized barcode. |
| [BarCodeExtendedParameters](/python-java/aspose_barcode.recognition/barcodeextendedparameters/) |  |
| [BarCodeReader](/python-java/aspose_barcode.recognition/barcodereader/) | BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operatio |
| [BarCodeRegionParameters](/python-java/aspose_barcode.recognition/barcoderegionparameters/) | Represents the recognized barcode's region and barcode angle. This sample shows how to get barcode Angle and bounding qu |
| [BarCodeResult](/python-java/aspose_barcode.recognition/barcoderesult/) | Stores recognized barcode data like SingleDecodeType type,. codetext, BarCodeRegionParameters region and other parameter |
| [BarcodeSettings](/python-java/aspose_barcode.recognition/barcodesettings/) | Contains settings for barcode recognition. |
| [CodabarExtendedParameters](/python-java/aspose_barcode.recognition/codabarextendedparameters/) | Stores a Codabar additional information of recognized barcode. |
| [Code128DataPortion](/python-java/aspose_barcode.recognition/code128dataportion/) | Contains the data of subtype for Code128 type barcode. |
| [Code128ExtendedParameters](/python-java/aspose_barcode.recognition/code128extendedparameters/) | Stores special data of Code128 recognized barcode. Represents the recognized barcode's region and barcode angle This sam |
| [DataBarExtendedParameters](/python-java/aspose_barcode.recognition/databarextendedparameters/) | Stores a DataBar additional information of recognized barcode. |
| [DataMatrixExtendedParameters](/python-java/aspose_barcode.recognition/datamatrixextendedparameters/) | Stores special data of DataMatrix recognized barcode This sample shows how to get DataMatrix raw values. |
| [DotCodeExtendedParameters](/python-java/aspose_barcode.recognition/dotcodeextendedparameters/) |  |
| [GS1CompositeBarExtendedParameters](/python-java/aspose_barcode.recognition/gs1compositebarextendedparameters/) | Stores additional information for GS1 Composite Bar recognized barcodes. |
| [MaxiCodeExtendedParameters](/python-java/aspose_barcode.recognition/maxicodeextendedparameters/) | Stores a MaxiCode additional information of recognized barcode. |
| [OneDExtendedParameters](/python-java/aspose_barcode.recognition/onedextendedparameters/) | Stores special data of 1D recognized barcode like separate codetext and checksum. This sample shows how to get 1D barcod |
| [Pdf417ExtendedParameters](/python-java/aspose_barcode.recognition/pdf417extendedparameters/) | Stores a MacroPdf417 metadata information of recognized barcode. This sample shows how to get Macro Pdf417 metadata |
| [QRExtendedParameters](/python-java/aspose_barcode.recognition/qrextendedparameters/) | Stores a QR Structured Append information of recognized barcode. This sample shows how to get QR Structured Append data |
| [Quadrangle](/python-java/aspose_barcode.recognition/quadrangle/) | Stores a set of four Points that represent a Quadrangle region. |
| [QualitySettings](/python-java/aspose_barcode.recognition/qualitysettings/) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by em |
| [RecognitionAbortedException](/python-java/aspose_barcode.recognition/recognitionabortedexception/) | Exception raised when barcode recognition is aborted. |

## Enums

| Enum | Description |
| --- | --- |
| [BarCodeConfidence](/python-java/aspose_barcode.recognition/barcodeconfidence/) | Contains recognition confidence level. This sample shows how BarCodeConfidence changed, depending on barcode type |
| [BarcodeQualityMode](/python-java/aspose_barcode.recognition/barcodequalitymode/) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality r |
| [ChecksumValidation](/python-java/aspose_barcode.recognition/checksumvalidation/) | Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must cont |
| [Code128SubType](/python-java/aspose_barcode.recognition/code128subtype/) |  |
| [ComplexBackgroundMode](/python-java/aspose_barcode.recognition/complexbackgroundmode/) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [CustomerInformationInterpretingType](/python-java/aspose_barcode.recognition/customerinformationinterpretingtype/) | Defines the interpreting type(C_TABLE or N_TABLE) of customer information for AustralianPost BarCode. |
| [DecodeType](/python-java/aspose_barcode.recognition/decodetype/) | Specify the type of barcode to read. This sample shows how to detect Code39 and Code128 barcodes. |
| [DeconvolutionMode](/python-java/aspose_barcode.recognition/deconvolutionmode/) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function |
| [InverseImageMode](/python-java/aspose_barcode.recognition/inverseimagemode/) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [XDimensionMode](/python-java/aspose_barcode.recognition/xdimensionmode/) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. This sample shows  |

