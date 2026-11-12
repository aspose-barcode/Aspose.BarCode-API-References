---
title: "Global"
linktitle: "Global"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "El espacio de nombres Global agrupa enumeraciones centrales y clases de utilidad utilizadas en Aspose.BarCode para Node.js vía Java."
type: docs
weight: 20
url: /es/nodejs/global/
---
El espacio de nombres Global proporciona una colección de enumeraciones fundamentales y tipos auxiliares que definen propiedades de códigos de barras como modos de codificación, tamaños de símbolos, niveles de confianza y formatos de imagen. Estas definiciones se hacen referencia en toda la API Aspose.BarCode para configurar e interpretar la generación y el reconocimiento de códigos de barras.

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [AddressType](./addresstype/) | Tipo de dirección |
| [AutoSizeMode](./autosizemode/) | Especifica los diferentes tipos de modos de dimensionado automático. El valor predeterminado es AutoSizeMode.NONE. |
| [AztecEncodeMode](./aztecencodemode/) | Modo de codificación para códigos de barras Aztec. |
| [AztecSymbolMode](./aztecsymbolmode/) | Especifica el modo de símbolo Aztec. |
| [BarCodeConfidence](./barcodeconfidence/) | Contiene el nivel de confianza del reconocimiento |
| [BarCodeImageFormat](./barcodeimageformat/) | Especifica el formato de archivo de la imagen. |
| [BarcodeClassifications](./barcodeclassifications/) | BarcodeClassifications EncodeTypes classification |
| [BarcodeQualityMode](./barcodequalitymode/) | Modo que permite a los métodos reconocer elementos de código de barras con la calidad seleccionada. Elemento de código de barras con calidad inferior r |
| [BorderDashStyle](./borderdashstyle/) | Especifica el estilo de líneas de borde punteadas. |
| [ChecksumValidation](./checksumvalidation/) | Habilitar la validación de suma de verificación durante el reconocimiento de códigos de barras 1D. Por defecto se trata como Sí para simbologías que deben cont |
| [CodabarChecksumMode](./codabarchecksummode/) | Especifica el algoritmo de suma de verificación para Codabar |
| [CodabarSymbol](./codabarsymbol/) | Especifica el símbolo de inicio o fin de la especificación del código de barras Codabar. |
| [Code128EncodeMode](./code128encodemode/) | Modo de codificación para códigos de barras Code128. Especificación `Code  128`. Este código demuestra cómo generar code 128 con diffe |
| [Code128SubType](./code128subtype/) | Contiene tipos del subconjunto Code128 |
| [CodeLocation](./codelocation/) | Ubicación de Codetext |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color. Este ejemplo muestra cómo usar Co |
| [CustomerInformationInterpretingType](./customerinformationinterpretingtype/) | Define el tipo de interpretación (C_TABLE o N_TABLE) de la información del cliente para el código de barras AustralianPost. |
| [DataMatrixEccType](./datamatrixecctype/) | Especifique el tipo de ECC a codificar. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | Modo de codificación del codificador DataMatrix, por defecto Auto. Este ejemplo muestra cómo hacer codetext en Modo Extendido. //Modo Auto l |
| [DataMatrixVersion](./datamatrixversion/) | Especifique el tipo de ECC a codificar. |
| [DecodeType](./decodetype/) | Especifique el tipo de código de barras a leer. |
| [DeconvolutionMode](./deconvolutionmode/) | Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente la deconvolución es una función |
| [DotCodeEncodeMode](./dotcodeencodemode/) | Modo de codificación para códigos de barras DotCode. |
| [ECIEncodings](./eciencodings/) | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para |
| [EnableChecksum](./enablechecksum/) | Habilitar suma de verificación durante la generación para códigos de barras 1D. Por defecto se trata como Sí para simbologías que deben contener suma de verificación |
| [EncodeTypes](./encodetypes/) | Especifica el tipo de código de barras a codificar. |
| [FontMode](./fontmode/) | Modo de tamaño de fuente. |
| [FontStyle](./fontstyle/) | Clasificación de FontStyle |
| [GraphicsUnit](./graphicsunit/) | Especifica la unidad de medida para los datos proporcionados. |
| [HIBCLICDateFormat](./hibclicdateformat/) | Especifica los diferentes tipos de formatos de fecha para HIBC LIC. |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | Tipos de ubicación de datos HIBC PAS. |
| [HIBCPASDataType](./hibcpasdatatype/) | Tipos de datos del registro HIBC PAS. |
| [HanXinEncodeMode](./hanxinencodemode/) | Modo de codificación Han Xin Code. Se recomienda usar Auto con caracteres ASCII / chinos o Unicode para caracteres Unicode |
| [HanXinErrorLevel](./hanxinerrorlevel/) | Nivel de corrección de errores Reed-Solomon. De bajo a alto: L1, L2, L3, L4. |
| [HanXinVersion](./hanxinversion/) | Versión de Han Xin Code. Desde Version01 - 23 x 23 módulos hasta Version84 - 189 x 189 módulos, aumentando en pasos de 2 módulos |
| [ITF14BorderType](./itf14bordertype/) | Tipo de borde del código de barras ITF14 |
| [InverseImageMode](./inverseimagemode/) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). Este ejemplo |
| [MacroCharacter](./macrocharacter/) | Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. El carácter macro 05 se traduce |
| [Mailmark2DType](./mailmark2dtype/) | Tipo de Mailmark 2D define el tamaño del código de barras Data Matrix |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | Modo de codificación para códigos de barras MaxiCode. |
| [MaxiCodeMode](./maxicodemode/) | Modo de codificación para códigos de barras MaxiCode. |
| [MicroQRVersion](./microqrversion/) | Versión de MicroQR Code. Desde M1 hasta M4. |
| [PatchFormat](./patchformat/) | Formato PatchCode. Elija PatchOnly para generar un solo PatchCode. Use el formato de página para generar una página Patch con PatchCodes |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Modo de compresión del código de barras Pdf417 |
| [Pdf417EncodeMode](./pdf417encodemode/) | Modo de codificación del código de barras Pdf417 |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | Nivel de corrección de errores del código de barras pdf417, de nivel 0 a nivel 9, el nivel 0 significa sin corrección de errores, el nivel 9 es el mejor |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. Aplicado solo para Macro PD |
| [QREncodeMode](./qrencodemode/) | Modo de codificación para códigos QR. Ejemplo de cómo usar la codificación ECI generator = new BarcodeGenerator(EncodeTypes.QR, \"12345TE |
| [QREncodeType](./qrencodetype/) | Modo selector QR / MicroQR. Seleccione FORCE_QR para símbolos QR estándar, AUTO para MicroQR. FORCE_MICRO_QR se usa para fuerte |
| [QRErrorLevel](./qrerrorlevel/) | Nivel de corrección de errores Reed-Solomon. De bajo a alto: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. |
| [QRVersion](./qrversion/) | Versión del código QR. De Version1 a Version40 para código QR y de M1 a M4 para MicroQr. |
| [QrBillStandardVersion](./qrbillstandardversion/) | Versión estándar de factura SwissQR |
| [QrExtCompactionMode](./qrextcompactionmode/) | Especifica el modo de compresión QR para el texto de código agregado por QrExtCodetextBuilder. |
| [RectMicroQRVersion](./rectmicroqrversion/) | Versión del código RectMicroQR. De la versión R7x43 a la versión R17x139. |
| [SvgColorMode](./svgcolormode/) | Modos posibles para rellenar color en archivo svg, RGB es el predeterminado y compatible con SVG 1.1. RGBA, HSL, HSLA están permitidos en SVG. |
| [TextAlignment](./textalignment/) | Alineación de texto. |
