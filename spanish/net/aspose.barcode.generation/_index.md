---
title: Aspose.BarCode.Generation
second_title: Referencia de API de Aspose.BarCode para .NET
description: El Aspose.BarCode.Generación que contiene clases generales para la implementación de funciones de generación de BarCode.
type: docs
weight: 50
url: /es/net/aspose.barcode.generation/
---
El **Aspose.BarCode.Generación** que contiene clases generales para la implementación de funciones de generación de BarCode.

## Clases

| Clase | Descripción |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters) | Parámetros de código de barras de AustralianPost. |
| [AztecParameters](./aztecparameters) | Parámetros aztecas. |
| [BarcodeGenerator](./barcodegenerator) | BarcodeGenerator para la generación de imágenes de código de barras backend. |
| [BarcodeParameters](./barcodeparameters) | Parámetros de generación de código de barras. |
| [BaseEncodeType](./baseencodetype) | Clase base para SymbologyEncodeType. |
| [BaseGenerationParameters](./basegenerationparameters) | Parámetros de generación de imagen de código de barras. |
| [BorderParameters](./borderparameters) | Parámetros del borde de la imagen del código de barras |
| [CaptionParameters](./captionparameters) | Parámetros de título. |
| [CodabarParameters](./codabarparameters) | Parámetros Codabar. |
| [CodablockParameters](./codablockparameters) | Parámetros Codablock. |
| [Code16KParameters](./code16kparameters) | Codigo16K parametros. |
| [CodetextParameters](./codetextparameters) | Parámetros de texto en código. |
| [CouponParameters](./couponparameters) | Parámetros del cupón. Usado para UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarParameters](./databarparameters) | Parámetros de la barra de datos. |
| [DataMatrixParameters](./datamatrixparameters) | Parámetros DataMatrix. |
| [DotCodeParameters](./dotcodeparameters) | Parámetros DotCode. |
| [EncodeTypes](./encodetypes) | Especifica el tipo de código de barras a codificar. |
| [ExtCodetextBuilder](./extcodetextbuilder) | Clase auxiliar para la generación automática de texto en código del modo de texto en código extendido |
| [FontUnit](./fontunit) | Define un formato particular para el texto, incluida la fuente, el tamaño y los atributos de estilo donde el tamaño en la propiedad Valor de la unidad. |
| [GS1CompositeBarParameters](./gs1compositebarparameters) | Parámetros de barra compuesta GS1. |
| [ITFParameters](./itfparameters) | Parámetros ITF. |
| [MaxiCodeParameters](./maxicodeparameters) | Parámetros MaxiCode. |
| [Padding](./padding) | Parámetros de relleno. |
| [PatchCodeParameters](./patchcodeparameters) | Parámetros de código de parche. |
| [Pdf417Parameters](./pdf417parameters) | Parámetros de PDF417. Contiene parámetros PDF417, MacroPDF417 y MicroPDF417. MacroPDF417 requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. MicroPDF417 en el modo Anexo estructurado (igual que el modo MacroPDF417) requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. |
| [PostalParameters](./postalparameters) | Parámetros postales. Usado para Postnet, Planet. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder) | Generador de texto de código extendido para códigos de barras QR 2D para el modo de texto de código extendido de QrEncodeMode |
| [QrParameters](./qrparameters) | Parámetros QR. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters) | Parámetros anexos estructurados QR. |
| [SupplementParameters](./supplementparameters) | Parámetros de suplemento. Usado para Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SymbologyEncodeType](./symbologyencodetype) | Tipo de codificación de simbología. Ver EncodeTypes para obtener instancia. |
| [Unit](./unit) | Especifica el valor del tamaño en diferentes unidades (píxeles, pulgadas, etc.). |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [AutoSizeMode](./autosizemode) | Especifica los diferentes tipos de modos de dimensionamiento automático. |
| [AztecSymbolMode](./aztecsymbolmode) | Especifica el modo de símbolo azteca. |
| [BarcodeClassifications](./barcodeclassifications) | Clasificación de simbología |
| [BarCodeImageFormat](./barcodeimageformat) | Especifica el formato de archivo de la imagen. |
| [BorderDashStyle](./borderdashstyle) | Especifica el estilo de las líneas discontinuas del borde. |
| [CodabarChecksumMode](./codabarchecksummode) | Especifica el algoritmo de suma de comprobación para Codabar |
| [CodabarSymbol](./codabarsymbol) | Especifica el símbolo de inicio o parada de la especificación del código de barras Codabar. |
| [Code128Emulation](./code128emulation) | Códigos de función para la emulación del Código 128. Aplicado solo para MicroPDF417. Ignorado para códigos de barras PDF417 y MacroPDF417. |
| [CodeLocation](./codelocation) | Ubicación del texto en código |
| [DataMatrixEccType](./datamatrixecctype) | Especifique el tipo de ECC a codificar. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Modo de codificación del codificador DataMatrix, predeterminado en Auto |
| [ECIEncodings](./eciencodings) | Identificadores de interpretación de canal extendido. Se usa para informar al lector de código de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual consiste en todas las codificaciones de juego de caracteres conocidas. Actualmente, se usa solo para código de barras QR 2D. |
| [EnableChecksum](./enablechecksum) | Habilite la suma de comprobación durante la generación de códigos de barras 1D. |
| [FontMode](./fontmode) | Modo de tamaño de fuente. |
| [ITF14BorderType](./itf14bordertype) | Tipo de borde ITF14 de código de barras |
| [MacroCharacter](./macrocharacter) | Los valores de los caracteres de macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. El carácter de macro 05 se traduce como "[)&gt;\u001E05\u001D" como encabezado de datos decodificados y "\u001E\u0004" como avance de datos decodificados. 06 Macro craracter se traduce como "[)&gt;\u001E06\u001D" como encabezado de datos decodificados y "\u001E\u0004" como avance de datos decodificados. |
| [PatchFormat](./patchformat) | Formato de código de parche. Elija PatchOnly para generar un código de parche único. Utilice el formato de página para generar una página de parches con PatchCodes como borders |
| [Pdf417CompactionMode](./pdf417compactionmode) | Pdf417 modo de compactación de código de barras |
| [Pdf417ErrorLevel](./pdf417errorlevel) | nivel de corrección de errores del código de barras pdf417, del nivel 0 al nivel 9, el nivel 0 significa que no hay corrección de errores, el nivel 9 significa la mejor corrección de errores |
| [QREncodeMode](./qrencodemode) | Modo de codificación para códigos de barras QR. Se recomienda usar Auto con CodeTextEncoding = Encoding.UTF8 para símbolos o dígitos latinos y Utf8BOM para símbolos Unicode. |
| [QREncodeType](./qrencodetype) | Modo selector QR / MicroQR. Seleccione ForceQR para símbolos QR estándar, Auto para MicroQR. ForceMicroQR se usa para generar símbolos MicroQR fuertes si es posible. |
| [QRErrorLevel](./qrerrorlevel) | Nivel de corrección de errores Reed-Solomon. De menor a mayor: NivelL, NivelM, NivelQ, NivelH. |
| [QRVersion](./qrversion) | Versión de QR Code. De Version1 a Version40 para código QR y de M1 a M4 para MicroQr. |
| [TextAlignment](./textalignment) | Alineación de texto. |
| [TwoDComponentType](./twodcomponenttype) | Tipo de componente 2D |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
