---
title: "Aspose.BarCode.BarCodeRecognition"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "El Aspose.BarCode.BarCodeRecognition contiene herramientas para el reconocimiento de códigos de barras 1D/2D."
type: docs
weight: 20
url: /es/net/aspose.barcode.barcoderecognition/
---
El **Aspose.BarCode.BarCodeRecognition** contiene herramientas para el reconocimiento de códigos de barras 1D/2D.

## Clases

| Clase | Descripción |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | Parámetros de decodificación de AustraliaPost. Contiene parámetros que influyen en los datos reconocidos de la simbología AustraliaPost. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Almacena datos especiales del código de barras Aztec reconocido. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Almacena parámetros extendidos del código de barras reconocido. |
| [BarCodeReader](./barcodereader/) | BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras, y luego puede ejecutar la operación ReadBarCodes para detectar códigos de barras. |
| [BarCodeRecognitionException](./barcoderecognitionexception/) | Excepción general lanzada por BarCodeReader, heredada de BarCodeException. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Representa la región del código de barras reconocido y el ángulo del código de barras. |
| [BarCodeResult](./barcoderesult/) | Almacena datos del código de barras reconocido como tipo [`SingleDecodeType`](../aspose.barcode.barcoderecognition/singledecodetype/), String codetext, región [`BarCodeRegionParameters`](../aspose.barcode.barcoderecognition/barcoderegionparameters/) y otros parámetros. |
| [BarcodeSettings](./barcodesettings/) | Los principales parámetros de decodificación de BarCode. Contiene parámetros que influyen en los datos reconocidos. |
| [BaseDecodeType](./basedecodetype/) | Clase base para MultiDecodeType y SingleDecodeType. |
| [BaseExtendedParameters](./baseextendedparameters/) | Clase básica para los parámetros extendidos del almacenamiento del código de barras reconocido. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Almacena información adicional de Codabar del código de barras reconocido. |
| [Code128DataPortion](./code128dataportion/) | Contiene los datos del subtipo para el código de barras tipo Code128. |
| [Code128ExtendedParameters](./code128extendedparameters/) | Almacena datos especiales del código de barras Code128 reconocido. |
| [DataBarExtendedParameters](./databarextendedparameters/) | Almacena información adicional de DataBar del código de barras reconocido. |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Almacena datos especiales del código de barras DataMatrix reconocido. |
| [DecodeType](./decodetype/) | Especifique el tipo de código de barras a leer. |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Almacena datos especiales del código de barras DotCode reconocido. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Almacena datos especiales del código de barras **GS1 Composite Bar** reconocido |
| [Iso15416Quality](./iso15416quality/) | Almacena los grados de calidad del código de barras calculados según la norma ISO/IEC 15416 para códigos de barras 1D. |
| [IsoSymbolQuality](./isosymbolquality/) | Almacena los resultados de la evaluación de la calidad del símbolo del código de barras según las normas ISO/IEC. |
| [LuminanceFrame](./luminanceframe/) | Representa un cuadro de imagen en escala de grises de 8 bits. Cada píxel se representa con un byte que contiene su valor de luminancia. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Almacena información adicional de MaxiCode del código de barras reconocido |
| [MultiDecodeType](./multidecodetype/) | Tipo de decodificación compuesto. |
| [OneDExtendedParameters](./onedextendedparameters/) | Almacena datos especiales del código de barras 1D reconocido, como texto de código separado y suma de verificación |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Almacena información de metadatos MacroPdf417 del código de barras reconocido |
| [QRExtendedParameters](./qrextendedparameters/) | Almacena información de Structured Append de QR del código de barras reconocido |
| [Quadrangle](./quadrangle/) | Almacena un conjunto de cuatro puntos que representan una región [`Quadrangle`](../aspose.barcode.barcoderecognition/quadrangle/). |
| [QualitySettings](./qualitysettings/) | QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puedes configurar rápidamente QualitySettings con los preajustes integrados: HighPerformance, NormalQuality, HighQuality, MaxQuality, o puedes configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality. |
| [RecognitionAbortedException](./recognitionabortedexception/) | Representa la excepción de interrupción del reconocimiento que se lanza cuando se supera el tiempo de espera durante el reconocimiento con BarCodeReader. |
| [SingleDecodeType](./singledecodetype/) | Tipo de decodificación único. Consulte el tipo de decodificación para obtener una instancia. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Interfaz pública para la decodificación del Campo de Información del Cliente que se utiliza en la simbología AustraliaPost. La implementación debe ser proporcionada por el usuario. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | Contiene el nivel de confianza del reconocimiento |
| [BarcodeQualityMode](./barcodequalitymode/) | Modo que permite a los métodos reconocer elementos de código de barras con la calidad seleccionada. Un elemento de código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento. |
| [ChecksumValidation](./checksumvalidation/) | Habilita la validación de suma de verificación durante el reconocimiento para códigos de barras 1D y postales. |
| [Code128SubType](./code128subtype/) | Contiene tipos del subconjunto Code128 |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color. |
| [DeconvolutionMode](./deconvolutionmode/) | Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente, la deconvolución es una función que puede restaurar una imagen degradada (convolucionada) por cualquier función natural como el desenfoque, al obtener la imagen con una cámara. Como no podemos detectar la función que corrompe la imagen, debemos comprobar las funciones más conocidas, como sharpen o la morfología matemática. |
| [InverseImageMode](./inverseimagemode/) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). |
| [XDimensionMode](./xdimensionmode/) | Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra. |


