---
title: "Espacio de nombres Aspose::BarCode::BarCodeRecognition"
linktitle: "Aspose::BarCode::BarCodeRecognition"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar el espacio de nombres Aspose::BarCode::BarCodeRecognition en C++."
type: docs
weight: 200
url: /es/cpp/aspose.barcode.barcoderecognition/
---



## Clases

| Clase | Descripción |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Interfaz pública para la decodificación del campo de información del cliente que se utiliza en la simbología AustraliaPost. La implementación debe ser proporcionada por el usuario. |
| [AustraliaPostSettings](./australiapostsettings/) | Parámetros de decodificación de AustraliaPost. Contiene parámetros que influyen en los datos reconocidos de la simbología AustraliaPost. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Almacena datos especiales del código de barras Aztec reconocido |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Almacena parámetros extendidos del código de barras reconocido |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/) encapsula una imagen que puede contener uno o varios códigos de barras, y luego puede ejecutar la operación ReadBarCodes para detectar códigos de barras. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Representa la región del código de barras reconocido y el ángulo del código de barras |
| [BarCodeResult](./barcoderesult/) | Almacena datos del código de barras reconocido como tipo [SingleDecodeType](./singledecodetype/), texto de código **System::String**, región [BarCodeRegionParameters](./barcoderegionparameters/) y otros parámetros |
| [BarcodeSettings](./barcodesettings/) | Los principales parámetros de decodificación de [BarCode](../aspose.barcode/). Contiene parámetros que influyen en los datos reconocidos. |
| [BaseDecodeType](./basedecodetype/) | Clase base para [MultiDecodeType](./multidecodetype/) y [SingleDecodeType](./singledecodetype/). |
| [BaseExtendedParameters](./baseextendedparameters/) | Clase básica para almacenar parámetros extendidos del código de barras reconocido |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Almacena información adicional de Codabar del código de barras reconocido |
| [Code128DataPortion](./code128dataportion/) | Contiene los datos del subtipo para el código de barras tipo Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | Almacena datos especiales del código de barras Code128 reconocido |
| [DataBarExtendedParameters](./databarextendedparameters/) | Almacena información adicional de DataBar del código de barras reconocido |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Almacena datos especiales del código de barras [DataMatrix](../aspose.barcode.barcoderecognition.datamatrix/) reconocido |
| [DecodeType](./decodetype/) | Especifique el tipo de código de barras a leer. |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | Excepción general lanzada por [BarCodeReader](./barcodereader/), heredada de BarCodeException |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | Representa la excepción de abortar reconocimiento que se lanza al exceder el tiempo de espera durante el reconocimiento con [BarCodeReader](./barcodereader/). |
| [Details_RecognitionEngineException](./details_recognitionengineexception/) |  |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Almacena datos especiales del código de barras DotCode reconocido |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Almacena datos especiales del código de barras **GS1 Composite Bar** reconocido |
| [Iso15416Quality](./iso15416quality/) | Almacena las calificaciones de calidad de códigos de barras calculadas según la norma ISO/IEC 15416 para códigos de barras 1D. |
| [IsoSymbolQuality](./isosymbolquality/) | Almacena los resultados de la evaluación de la calidad del símbolo del código de barras según las normas ISO/IEC. |
| [LuminanceFrame](./luminanceframe/) | Representa un fotograma de imagen en escala de grises de 8 bits. Cada píxel se representa con un byte que contiene su valor de luminancia. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Almacena información adicional de MaxiCode del código de barras reconocido. |
| [MultiDecodeType](./multidecodetype/) | Tipo de decodificación compuesta. |
| [OneDExtendedParameters](./onedextendedparameters/) | Almacena datos especiales de códigos de barras 1D reconocidos, como el texto del código separado y la suma de verificación. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Almacena información de metadatos MacroPdf417 del código de barras reconocido. |
| [QRExtendedParameters](./qrextendedparameters/) | Almacena información de Structured Append de [QR](../aspose.barcode.barcoderecognition.qr/) del código de barras reconocido. |
| [Quadrangle](./quadrangle/) | Almacena un conjunto de cuatro [Point](../)s que representan una región de [Quadrangle](./quadrangle/). |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/) permite configurar manualmente la calidad y velocidad del reconocimiento. Puede configurar rápidamente [QualitySettings](./qualitysettings/) con los presets integrados: HighPerformance, NormalQuality, HighQuality, MaxQuality o puede configurar manualmente opciones separadas. El valor predeterminado de [QualitySettings](./qualitysettings/) es NormalQuality. |
| [SingleDecodeType](./singledecodetype/) | Tipo de decodificación único. Consulte el tipo de decodificación para obtener una instancia. |
## Enums

| Enumeración | Descripción |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | Contiene tipos del subconjunto Code128. |
| [BarCodeConfidence](./barcodeconfidence/) | Contiene el nivel de confianza del reconocimiento. |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionEngineException](./recognitionengineexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |
