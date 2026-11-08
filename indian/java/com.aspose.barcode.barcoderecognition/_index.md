---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "यह पैकेज 1D/2D बारकोड पहचान के लिए उपकरण शामिल करता है।"
type: docs
weight: 12
url: /hi/java/com.aspose.barcode.barcoderecognition/
---

यह पैकेज 1D/2D बारकोड पहचान के लिए उपकरण शामिल करता है।


## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost डिकोडिंग पैरामीटर। |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Aztec पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है। |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | पहचाने गए बारकोड के विस्तारित पैरामीटर संग्रहीत करता है। |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader एक छवि को संलग्न करता है जिसमें एक या कई बारकोड हो सकते हैं, फिर यह बारकोड का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है। |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | BarCodeReader द्वारा फेंकी गई सामान्य अपवाद, BarCodeException से विरासत में मिली। |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | पहचाने गए बारकोड के क्षेत्र और बारकोड कोण को दर्शाता है। |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | पहचाने गए बारकोड डेटा जैसे SingleDecodeType प्रकार, string codetext, BarCodeRegionParameters क्षेत्र और अन्य पैरामीटर संग्रहीत करता है। |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | मुख्य BarCode डिकोडिंग पैरामीटर। |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | बारकोड डिटेक्टर सेटिंग्स। |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | MultiDecodeType और SingleDecodeType के लिए बेस क्लास। |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | पहचाने गए बारकोड संग्रहीत करने के विस्तारित पैरामीटर के लिए बेसिक क्लास। |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | पहचाने गए बारकोड की Codabar अतिरिक्त जानकारी संग्रहीत करता है |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Code128 प्रकार के बारकोड के उपप्रकार का डेटा शामिल करता है |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Code128 पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | पहचाने गए बारकोड की DataBar अतिरिक्त जानकारी संग्रहीत करता है BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | DataMatrix पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | पढ़ने के लिए बारकोड का प्रकार निर्दिष्ट करें। |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | DotCode पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | पहचाने गए बारकोड की **GS1 Composite Bar** का विशेष डेटा संग्रहीत करता है |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | पहचाने गए बारकोड की MaxiCode अतिरिक्त जानकारी संग्रहीत करता है |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | संयोजन डिकोड प्रकार। |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | 1D पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है जैसे अलग कोडटेक्स्ट और चेकसम |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | पहचाने गए बारकोड की MacroPdf417 मेटाडाटा जानकारी संग्रहीत करता है |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings मल्टी-थ्रेडेड प्रदर्शन वृद्धि के साथ बारकोड को पहचानने की अनुमति देते हैं |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | पहचाने गए बारकोड की QR Structured Append जानकारी संग्रहीत करता है |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | चार बिंदुओं का एक सेट संग्रहीत करता है जो एक Quadrangle क्षेत्र का प्रतिनिधित्व करता है। |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings मैन्युअल रूप से पहचान की गुणवत्ता और गति को कॉन्फ़िगर करने की अनुमति देता है। |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | BarCodeReader के साथ पहचान के दौरान टाइमआउट अधिक होने पर फेंकी जाने वाली पहचान समाप्ति अपवाद को दर्शाता है। |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | एकल डिकोड प्रकार। |

## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | AustraliaPost प्रतीक विज्ञान में उपयोग किए जाने वाले Customer Information Field डिकोडिंग के लिए सार्वजनिक इंटरफ़ेस। |

## एन्यूमरेशन

| एन्यूम | विवरण |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | पहचान विश्वास स्तर शामिल करता है |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Code128 उपसमुच्चय के प्रकार शामिल करता है। |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | ऑस्ट्रेलियनपोस्ट बारकोड के लिए ग्राहक जानकारी के व्याख्या प्रकार (C\_TABLE या N\_TABLE) को परिभाषित करता है। |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
