---
title: com.aspose.barcode.barcoderecognition
second_title: Aspose.BarCode per Android via Java API Reference
description: Questo pacchetto contiene strumenti per il riconoscimento di codici a barre 1D/2D.
type: docs
weight: 11
url: /it/androidjava/com.aspose.barcode.barcoderecognition/
---

Questo pacchetto contiene strumenti per il riconoscimento di codici a barre 1D/2D.


## Classi

| Classe | Descrizione |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Parametri di decodifica AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Memorizza dati speciali del codice a barre Aztec riconosciuto |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Contiene il livello di fiducia del riconoscimento |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Memorizza i parametri estesi del codice a barre riconosciuto |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader incapsula un'immagine che può contenere uno o più codici a barre; può quindi eseguire l'operazione ReadBarCodes per rilevare i codici a barre. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Eccezione generale lanciata da BarCodeReader, ereditata da BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Rappresenta la regione del codice a barre riconosciuto e l'angolo del codice a barre |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Memorizza i dati del codice a barre riconosciuto come tipo SingleDecodeType, string codetext, BarCodeRegionParameters region e altri parametri |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | I principali parametri di decodifica del BarCode. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Impostazioni del rilevatore di codici a barre. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Classe base per MultiDecodeType e SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Classe di base per la memorizzazione dei parametri estesi del codice a barre riconosciuto |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Memorizza informazioni aggiuntive Codabar del codice a barre riconosciuto |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Contiene i dati del sottotipo per il codice a barre di tipo Code128 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Memorizza dati speciali del codice a barre Code128 riconosciuto |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Contiene i tipi del sottoinsieme Code128 |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Memorizza informazioni aggiuntive DataBar del codice a barre riconosciuto BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Memorizza dati speciali del codice a barre DataMatrix riconosciuto |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Specifica il tipo di codice a barre da leggere. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Memorizza dati speciali del codice a barre DotCode riconosciuto |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Memorizza dati speciali del codice a barre **GS1 Composite Bar** riconosciuto |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Memorizza informazioni aggiuntive MaxiCode del codice a barre riconosciuto |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Tipo di decodifica composita. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | Tipo di decodifica composita. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Memorizza dati speciali del codice a barre 1D riconosciuto, come testo del codice separato e checksum |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Memorizza informazioni di metadati MacroPdf417 del codice a barre riconosciuto |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings consente di riconoscere i codici a barre con aumento delle prestazioni tramite multithreading |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Memorizza informazioni QR Structured Append del codice a barre riconosciuto |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Memorizza un insieme di quattro Point che rappresentano una regione Quadrangle. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Rappresenta l'eccezione di interruzione del riconoscimento che viene lanciata al superamento del timeout durante il riconoscimento con BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Tipo di decodifica singola. |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Interfaccia pubblica per la decodifica del Customer Information Field utilizzata nella simbologia AustraliaPost. |

## Enumerazioni

| Enum | Descrizione |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Definisce il tipo di interpretazione (C\_TABLE o N\_TABLE) delle informazioni cliente per il BarCode AustralianPost. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Specifica la dimensione dell'immagine scalata |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
