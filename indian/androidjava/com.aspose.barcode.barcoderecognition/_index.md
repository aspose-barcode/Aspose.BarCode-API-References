---
title: com.aspose.barcode.barcoderecognition
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: यह पैकेज 1D/2D बारकोड पहचान के लिए टूल्स शामिल करता है।
type: docs
weight: 11
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/
---

यह पैकेज 1D/2D बारकोड पहचान के लिए टूल्स शामिल करता है।


## क्लासेज़

| क्लास | विवरण |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost डिकोडिंग पैरामीटर। |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Aztec पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | पहचान विश्वास स्तर शामिल करता है |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | पहचाने गए बारकोड के विस्तारित पैरामीटर संग्रहीत करता है |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader एक छवि को संलग्न करता है जिसमें एक या कई बारकोड हो सकते हैं, फिर वह बारकोड का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है। |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | BarCodeReader द्वारा उत्पन्न सामान्य अपवाद, BarCodeException से विरासत में मिला हुआ |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | पहचाने गए बारकोड का क्षेत्र और बारकोड कोण दर्शाता है |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | पहचाने गए बारकोड डेटा संग्रहीत करता है जैसे SingleDecodeType प्रकार, string codetext, BarCodeRegionParameters क्षेत्र और अन्य पैरामीटर |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | मुख्य BarCode डिकोडिंग पैरामीटर। |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | बारकोड डिटेक्टर सेटिंग्स। |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | MultiDecodeType और SingleDecodeType के लिए बेस क्लास। |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | पहचाने गए बारकोड के संग्रह के विस्तारित पैरामीटर के लिए बेसिक क्लास |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | पहचाने गए बारकोड की Codabar अतिरिक्त जानकारी संग्रहीत करता है |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Code128 प्रकार के बारकोड के सबटाइप डेटा को शामिल करता है |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Stores special data of Code128 recognized barcode |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Contains types of Code128 subset |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Stores a DataBar additional information of recognized barcode BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Stores special data of DataMatrix recognized barcode |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Specify the type of barcode to read. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Stores special data of DotCode recognized barcode |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Stores special data of  **GS1 Composite Bar**  recognized barcode |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Stores a MaxiCode additional information of recognized barcode |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Composite decode type. |
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

## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. |

## एन्यूमरेशन

| एन्यूम | विवरण |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Defines the interpreting type(C\_TABLE or N\_TABLE) of customer information for AustralianPost BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Specify the size of scaled image |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
