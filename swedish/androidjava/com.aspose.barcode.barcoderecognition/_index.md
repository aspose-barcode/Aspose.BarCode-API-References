---
title: com.aspose.barcode.barcoderecognition
second_title: Aspose.BarCode for Android via Java API-referens
description: Detta paket innehåller verktyg för 1D/2D-streckkodigenkänning.
type: docs
weight: 11
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/
---

Detta paket innehåller verktyg för 1D/2D-streckkodigenkänning.


## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Avkodningsparametrar för AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Lagrar speciella data för Aztec‑igenkänd streckkod |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Innehåller igenkänningskonfidensnivå |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Lagrar utökade parametrar för igenkänd streckkod |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader kapslar in en bild som kan innehålla en eller flera streckkoder, och kan sedan utföra ReadBarCodes‑operationen för att upptäcka streckkoder. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Allmän undantag som kastas av BarCodeReader, ärvt från BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Representerar den igenkända streckkodens region och streckkodsvinkel |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Lagrar data för igenkänd streckkod såsom typ SingleDecodeType, sträng codetext, BarCodeRegionParameters region och andra parametrar |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | De huvudsakliga BarCode‑avkodningsparametrarna. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Inställningar för streckkoddetektor. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Basklass för MultiDecodeType och SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Grundklass för lagring av utökade parametrar för igenkänd streckkod |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Lagrar ytterligare information för Codabar för den igenkända streckkoden |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Innehåller data för undertyp för Code128‑streckkod |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Lagrar speciella data för Code128 igenkänd streckkod |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Innehåller typer av Code128 delmängd |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Lagrar ytterligare DataBar-information för en igenkänd streckkod BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Lagrar speciella data för DataMatrix igenkänd streckkod |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Ange typen av streckkod som ska läsas. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Lagrar speciella data för DotCode igenkänd streckkod |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Lagrar speciella data för  **GS1 Composite Bar**  igenkänd streckkod |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Lagrar ytterligare MaxiCode-information för en igenkänd streckkod |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Sammansatt avkodningstyp. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | Sammansatt avkodningstyp. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Lagrar speciella data för 1D igenkänd streckkod, såsom separat kodtext och kontrollsumma |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Lagrar metadatainformation för MacroPdf417 för en igenkänd streckkod |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings möjliggör att känna igen streckkoder med flerkärnig prestandaförbättring |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Lagrar QR Structured Append-information för en igenkänd streckkod |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Lagrar en uppsättning av fyra  Point s som representerar ett  Quadrangle  område. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings tillåter att konfigurera igenkänningskvalitet och hastighet manuellt. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Representerar avbrytningsexception för igenkänning som kastas vid tidsgränsöverskridning under igenkänning med BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Enkel avkodningstyp. |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Publikt gränssnitt för avkodning av Customer Information Field som används i AustraliaPost-symbologi. |

## Enumerationer

| Enum | Beskrivning |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Definierar tolknings typen (C\_TABLE eller N\_TABLE) för kundinformation för AustralianPost BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Ange storleken på den skalade bilden |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
