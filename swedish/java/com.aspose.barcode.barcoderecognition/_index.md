---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode för Java API-referens"
description: "Detta paket innehåller verktyg för 1D/2D-streckkodigenkänning."
type: docs
weight: 12
url: /sv/java/com.aspose.barcode.barcoderecognition/
---

Detta paket innehåller verktyg för 1D/2D-streckkodigenkänning.


## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost-avkodningsparametrar. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Lagrar speciella data för Aztec‑erkänd streckkod |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Lagrar utökade parametrar för erkänd streckkod |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader kapslar in en bild som kan innehålla en eller flera streckkoder, och kan sedan utföra ReadBarCodes‑operationen för att upptäcka streckkoder. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Allmänt undantag kastat av BarCodeReader, ärvt från BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Representerar den erkända streckkodens region och streckkodsvinkel |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Lagrar erkända streckkodsdata som  SingleDecodeType  typ,  string  kodtext,  BarCodeRegionParameters  region och andra parametrar |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | De viktigaste streckkodavkodningsparametrarna. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Inställningar för streckkoddetektor. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Bas‑klass för MultiDecodeType och SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Grundläggande klass för lagring av utökade parametrar för erkända streckkoder |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Lagrar en Codabar‑tilläggsinformation för igenkänd streckkod |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Innehåller data för undertyp för Code128‑typen streckkod |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Lagrar speciella data för Code128‑igenkänd streckkod |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Lagrar en DataBar‑tilläggsinformation för igenkänd streckkod BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Lagrar speciella data för DataMatrix‑igenkänd streckkod |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Ange typen av streckkod som ska läsas. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Lagrar speciella data för DotCode‑igenkänd streckkod |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Lagrar speciella data för  **GS1 Composite Bar**  igenkänd streckkod |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Lagrar en MaxiCode‑tilläggsinformation för igenkänd streckkod |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Sammansatt avkodningstyp. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Lagrar speciella data för 1D‑igenkänd streckkod, såsom separat kodtext och kontrollsumma |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Lagrar en MacroPdf417‑metadatainformation för igenkänd streckkod |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings möjliggör att flertrådad prestandaökning vid igenkänning av streckkoder |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Lagrar en QR Structured Append‑information för igenkänd streckkod |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Lagrar en uppsättning av fyra  Point  som representerar ett  Quadrangle ‑område. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings möjliggör att manuellt konfigurera igenkänningskvalitet och hastighet. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Representerar ett avbrottsundantag för igenkänning som kastas vid tidsgränsen överskrids under igenkänning med BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Enkel avkodningstyp. |

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Publikt gränssnitt för avkodning av Customer Information Field som används i AustraliaPost‑symbologi. |

## Enumerationer

| Enum | Beskrivning |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Innehåller igenkänningskonfidensnivå |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Innehåller typer av Code128‑delmängd. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Definierar tolkningstypen (C\_TABLE eller N\_TABLE) av kundinformation för AustralianPost BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
