---
title: com.aspose.barcode.barcoderecognition
second_title: Aspose.BarCode for Java API Reference
description: This package contains tools for 1D/2D barcode recognition.
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition/
---

This package contains tools for 1D/2D barcode recognition.


## Classes

| Class | Description |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost decoding parameters. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Stores special data of Aztec recognized barcode |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Contains recognition confidence level |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Stores extended parameters of recognized barcode |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | General exception thrown by BarCodeReader, inherited from BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Represents the recognized barcode's region and barcode angle |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Stores recognized barcode data like  SingleDecodeType  type,  string  codetext,  BarCodeRegionParameters  region and other parameters |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | The main BarCode decoding parameters. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Barcode detector settings. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Base class for MultyDecodeType and SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Basic class for extended parameters of recognized barcode storing |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Stores a Codabar additional information of recognized barcode |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Contains the data of subtype for Code128 type barcode |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Stores special data of Code128 recognized barcode |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Contains types of Code128 subset |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Stores a DataBar additional information of recognized barcode BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Stores special data of DataMatrix recognized barcode |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Specify the type of barcode to read. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Stores special data of DotCode recognized barcode |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Stores special data of  **GS1 Composite Bar**  recognized barcode |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Stores a MaxiCode additional information of recognized barcode |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | Composite decode type. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Stores special data of 1D recognized barcode like separate codetext and checksum |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Stores a MacroPdf417 metadata information of recognized barcode |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings allow to recognize barcodes with multi-threaded increasing of performance |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Stores a QR Structured Append information of recognized barcode |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Stores a set of four  Point s that represent a  Quadrangle  region. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings allows to configure recognition quality and speed manually. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Represents recognition abort exception which is thrown in timeout exceeding during recognition with BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Single decode type. |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## Interfaces

| Interface | Description |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. |

## Enumerations

| Enum | Description |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Defines the interpreting type(C\_TABLE or N\_TABLE) of customer information for AustralianPost BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
