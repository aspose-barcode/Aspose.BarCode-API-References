---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "Detta paket innehåller verktyg för 1D/2D streckkodigenkänning."
type: docs
weight: 11
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/
---

Detta paket innehåller verktyg för 1D/2D streckkodigenkänning.


## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost‑avkodningsparametrar. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Lagrar specialdata för Aztec‑igenkänd streckkod |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Lagrar utökade parametrar för igenkänd streckkod |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader kapslar in en bild som kan innehålla en eller flera streckkoder, den kan sedan utföra ReadBarCodes‑operationen för att upptäcka streckkoder. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Allmän undantag som kastas av BarCodeReader, ärvd från BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Representerar den igenkända streckkodens region och streckkodsvinkel |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Lagrar igenkända streckkodsdata såsom  SingleDecodeType  typ,  string  kodtext,  BarCodeRegionParameters  region och andra parametrar |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | De huvudsakliga BarCode‑avkodningsparametrarna. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Inställningar för streckkoddetektor. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Bas‑klass för MultiDecodeType och SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Grundklass för lagring av utökade parametrar för igenkänd streckkod |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Lagrar ytterligare information för Codabar för igenkänd streckkod |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Innehåller data för undertyp för Code128‑streckkod |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Lagrar specialdata för Code128‑igenkänd streckkod |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Lagrar ytterligare information för DataBar för igenkänd streckkod BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Lagrar specialdata för igenkänd DataMatrix-streckkod |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Ange typen av streckkod som ska läsas. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Lagrar specialdata för igenkänd DotCode-streckkod |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Lagrar specialdata för igenkänd **GS1 Composite Bar** streckkod |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Lagrar ytterligare information för MaxiCode för igenkänd streckkod |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Sammansatt avkodningstyp. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) |  |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Lagrar specialdata för 1D igenkänd streckkod, såsom separat kodtext och kontrollsumma |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Lagrar metadatainformation för MacroPdf417 för igenkänd streckkod |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings möjliggör att känna igen streckkoder med flerkärnig prestandaökning. |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Lagrar QR Structured Append-information för igenkänd streckkod |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Lagrar en uppsättning av fyra  Point s som representerar ett  Quadrangle  område. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings möjliggör att manuellt konfigurera igenkänningskvalitet och hastighet. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Representerar avbrytningsundantag för igenkänning som kastas när tidsgränsen överskrids under igenkänning med BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Enkel avkodningstyp. |

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Offentligt gränssnitt för avkodning av Customer Information Field som används i AustraliaPost-symbologi. |

## Enumerationer

| Enum | Beskrivning |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Innehåller förtroendenivå för igenkänning |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Innehåller typer av Code128-undermängd. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Definierar tolkningstypen (C\\_TABLE eller N\\_TABLE) för kundinformation för AustralianPost BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Ange storleken på den skalade bilden |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
