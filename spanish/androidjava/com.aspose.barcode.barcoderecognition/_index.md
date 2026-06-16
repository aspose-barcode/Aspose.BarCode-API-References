---
title: com.aspose.barcode.barcoderecognition
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Este paquete contiene herramientas para el reconocimiento de códigos de barras 1D/2D.
type: docs
weight: 11
url: /es/androidjava/com.aspose.barcode.barcoderecognition/
---

Este paquete contiene herramientas para el reconocimiento de códigos de barras 1D/2D.


## Clases

| Clase | Descripción |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Parámetros de decodificación de AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Almacena datos especiales del código de barras Aztec reconocido |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Contiene el nivel de confianza del reconocimiento |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Almacena parámetros extendidos del código de barras reconocido |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras, y luego puede ejecutar la operación ReadBarCodes para detectar códigos de barras. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Excepción general lanzada por BarCodeReader, heredada de BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Representa la región del código de barras reconocido y el ángulo del código de barras |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Almacena datos del código de barras reconocido como tipo SingleDecodeType, cadena codetext, BarCodeRegionParameters region y otros parámetros |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Los principales parámetros de decodificación de BarCode. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Configuración del detector de códigos de barras. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Clase base para MultiDecodeType y SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Clase básica para almacenar parámetros extendidos del código de barras reconocido |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Almacena información adicional de Codabar del código de barras reconocido |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Contiene los datos del subtipo para el código de barras tipo Code128 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Almacena datos especiales del código de barras Code128 reconocido |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Contiene tipos del subconjunto Code128 |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Almacena información adicional de DataBar del código de barras reconocido BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Almacena datos especiales del código de barras DataMatrix reconocido |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Especifique el tipo de código de barras a leer. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Almacena datos especiales del código de barras DotCode reconocido |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Almacena datos especiales del **GS1 Composite Bar** reconocido |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Almacena información adicional de MaxiCode del código de barras reconocido |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Tipo de decodificación compuesta. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | Tipo de decodificación compuesta. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Almacena datos especiales del código de barras 1D reconocido, como texto del código y suma de verificación separados |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Almacena información de metadatos MacroPdf417 del código de barras reconocido |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings permite reconocer códigos de barras con aumento de rendimiento mediante multihilos |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Almacena información de QR Structured Append del código de barras reconocido |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Almacena un conjunto de cuatro Point que representan una región Quadrangle |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Representa la excepción de interrupción del reconocimiento que se lanza al exceder el tiempo de espera durante el reconocimiento con BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Tipo de decodificación única. |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Interfaz pública para la decodificación del Campo de Información del Cliente que se utiliza en la simbología AustraliaPost. |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Define el tipo de interpretación (C\_TABLE o N\_TABLE) de la información del cliente para el BarCode AustralianPost. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Especifique el tamaño de la imagen escalada |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
