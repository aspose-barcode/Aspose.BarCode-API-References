---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "El espacio de nombres aspose.barcode ofrece clases y enumeraciones para crear, personalizar y decodificar una amplia variedad de tipos de códigos de barras en Node.js vía Java."
type: docs
weight: 10
url: /es/nodejs/aspose.barcode/
---
Utilice estos tipos para configurar ajustes de generación de códigos de barras como el formato de direcciones, especificaciones regionales y parámetros avanzados para Aztec y otras simbologías. El espacio de nombres incluye asistentes para construir textos de código extendidos y manejar normas postales especializadas.

## Clases

| Clase | Descripción |
| --- | --- |
| [Address](./address/) | Dirección del acreedor o deudor. Puede establecer la calle, número, código postal y localidad (tipo dirección estructurada) o |
| [AlternativeScheme](./alternativescheme/) | Instrucciones del esquema de pago alternativo |
| [AustraliaPostSettings](./australiapostsettings/) | Parámetros de decodificación de AustraliaPost. Contiene parámetros que influyen en los datos reconocidos de la simbología AustraliaPost |
| [AustralianPostParameters](./australianpostparameters/) | Parámetros del código de barras AustralianPost. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Generador de texto de código extendido para códigos de barras Aztec para el modo ExtendedCodetext de AztecEncodeMode. Utilice la propiedad TwoDDisplayText |
| [AztecExtendedParameters](./aztecextendedparameters/) | Almacena datos especiales del código de barras Aztec reconocido. Este ejemplo muestra cómo obtener los valores sin procesar de Aztec; let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Parámetros de Aztec. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Almacena parámetros extendidos del código de barras reconocido |
| [BarCodeReader](./barcodereader/) | BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras, y luego puede ejecutar la operación ReadBarCodes |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Representa la región del código de barras reconocido y el ángulo del código de barras |
| [BarCodeResult](./barcoderesult/) | Almacena datos del código de barras reconocido como el tipo SingleDecodeType, `string` codetext, BarCodeRegionParameters region y otros p |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator para la generación de imágenes de códigos de barras en el backend. simbologías compatibles: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | Parámetros de generación de códigos de barras. |
| [BarcodeSettings](./barcodesettings/) | Los principales parámetros de decodificación de BarCode. Contiene parámetros que influyen en los datos reconocidos. |
| [BaseGenerationParameters](./basegenerationparameters/) | Parámetros de generación de imágenes de códigos de barras. |
| [BorderParameters](./borderparameters/) | Parámetros del borde de la imagen del código de barras |
| [CMYKColor](./cmykcolor/) | Clase para color CMYK. Una instancia nula significa que CMYK no se usa y se utiliza el color RGB predeterminado. |
| [CaptionParameters](./captionparameters/) | Parámetros de leyenda. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Almacena información adicional de Codabar del código de barras reconocido |
| [CodabarParameters](./codabarparameters/) | Parámetros de Codabar. |
| [CodablockParameters](./codablockparameters/) | Parámetros de Codablock. |
| [Code128DataPortion](./code128dataportion/) | Contiene los datos del subtipo para el código de barras tipo Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | Almacena datos especiales del código de barras Code128 reconocido. Representa la región del código de barras reconocido y el ángulo del código de barras. |
| [Code128Parameters](./code128parameters/) | Parámetros de Code128. |
| [Code16KParameters](./code16kparameters/) | Parámetros de Code16K. |
| [CodetextParameters](./codetextparameters/) | Parámetros de Codetext. |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator para la generación de imágenes de códigos de barras complejos en el backend (p. ej., SwissQR). |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader decodifica el codetext al tipo de código de barras complejo especificado. |
| [CouponParameters](./couponparameters/) | Parámetros de cupón. Utilizado para UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarExtendedParameters](./databarextendedparameters/) | Almacena información adicional de DataBar del código de barras reconocido |
| [DataBarParameters](./databarparameters/) | Parámetros de Databar. |
| [DataElement](./dataelement/) | Representa un campo de datos específico de la jurisdicción utilizado en documentos, por ejemplo ElementID = \"ZVA\" con Valor = \"01\". |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Generador de codetext extendido para códigos de barras 2D DataMatrix para el modo ExtendedCodetext de DataMatrixEncodeMode //Código extendido |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Almacena datos especiales del código de barras DataMatrix reconocido. Este ejemplo muestra cómo obtener los valores sin procesar de DataMatrix; let generator = |
| [DataMatrixParameters](./datamatrixparameters/) | Parámetros de DataMatrix. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Generador de codetext extendido para códigos de barras 2D DotCode para el modo ExtendedCodetext de DotCodeEncodeMode |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Almacena datos especiales del código de barras DotCode reconocido. Este ejemplo muestra cómo obtener los valores sin procesar de DotCode |
| [DotCodeParameters](./dotcodeparameters/) | Parámetros de DotCode. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Clase auxiliar para la generación automática de codetexto del Extended Codetext Mode |
| [FontUnit](./fontunit/) | Define un formato particular para el texto, incluyendo la familia de fuentes, el tamaño y los atributos de estilo donde el tamaño está en la propiedad Unit value. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Almacena datos especiales del código de barras reconocido `GS1 Composite Bar ` |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | Parámetros de GS1 Composite bar. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios y secundarios. Esta muestra |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Clase base para codificar y decodificar el texto incrustado en el código HIBC LIC. Esta muestra muestra cómo decodificar HIBC LI |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios. Esta muestra muestra cómo |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos secundarios. |
| [HIBCPASCodetext](./hibcpascodetext/) | Clase para codificar y decodificar el texto incrustado en el código HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord/) | Clase para almacenar el registro HIBC PAS. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Generador de codetexto extendido para Han Xin Code para el Modo Extendido de HanXinEncodeMode //Extended codetext mode //create cod |
| [HanXinParameters](./hanxinparameters/) | Parámetros de Han Xin. |
| [HslaColor](./hslacolor/) | Clase para representar el color HSLA (Hue, Saturation, Lightness, Alpha) |
| [IComplexCodetext](./icomplexcodetext/) | Interfaz para codetexto complejo usado con ComplexBarcodeGenerator. |
| [ITFParameters](./itfparameters/) | Parámetros de ITF. |
| [ImageParameters](./imageparameters/) | Parámetros de imagen. |
| [License](./license/) | Proporciona métodos para licenciar el componente. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Clase para codificar y decodificar el texto incrustado en el código Royal Mail 2D Mailmark. |
| [MailmarkCodetext](./mailmarkcodetext/) | Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados. |
| [MandatoryFields](./mandatoryfields/) | Elementos obligatorios (campos) de la tarjeta |
| [MaxiCodeCodetext](./maxicodecodetext/) | Clase base para codificar y decodificar el texto incrustado en el código MaxiCode. Esta muestra muestra cómo decodificar MaxiCod sin procesar |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Clase para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Clase para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 3. Esta muestra muestra cómo codificar y |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Generador de codetexto extendido para códigos de barras MaxiCode para el Modo ExtendedCodetext de MaxiCodeEncodeMode Use TwoDDisplayText pr |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Almacena información adicional de MaxiCode del código de barras reconocido |
| [MaxiCodeParameters](./maxicodeparameters/) | Parámetros de MaxiCode. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Clase para codificar y decodificar el texto de código MaxiCode para los modos 4, 5 y 6. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Clase para codificar y decodificar el texto de código MaxiCode para los modos 4, 5 y 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Clase para codificar y decodificar el segundo mensaje estándar para el código de barras MaxiCode. |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | Clase para codificar y decodificar el segundo mensaje estándar para el código de barras MaxiCode. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Clase base para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2 y 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Clase para codificar y decodificar el segundo mensaje estructurado para el código de barras MaxiCode. |
| [OneDExtendedParameters](./onedextendedparameters/) | Almacena datos especiales del código de barras 1D reconocido, como texto de código separado y suma de verificación. |
| [OptionalFields](./optionalfields/) | Elementos opcionales (campos) de la tarjeta |
| [Padding](./padding/) | Parámetros de rellenos. |
| [PatchCodeParameters](./patchcodeparameters/) | Parámetros de PatchCode. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Almacena información de metadatos MacroPdf417 del código de barras reconocido |
| [Pdf417Parameters](./pdf417parameters/) | Parámetros de PDF417. Contiene parámetros de PDF417, MacroPDF417, MicroPDF417 y GS1MicroPdf417. MacroPDF417 requiere dos fie |
| [PdfParameters](./pdfparameters/) | Wrapper de parámetros PDF. Espera una instancia subyacente `mwObject` que proporcione los métodos getter/setter correspondientes |
| [PostalParameters](./postalparameters/) | Parámetros postales. Usado para Postnet, Planet. |
| [PrimaryData](./primarydata/) | Clase para almacenar los datos primarios HIBC LIC. |
| [QRExtendedParameters](./qrextendedparameters/) | Almacena información de QR Structured Append del código de barras reconocido |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Generador de texto de código extendido para códigos QR 2D en modo ExtendedCodetext de QREncodeMode. Use la propiedad Display2DText de B |
| [QrParameters](./qrparameters/) | Parámetros QR. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | Parámetros de QR structured append. |
| [Quadrangle](./quadrangle/) | Almacena un conjunto de cuatro Points que representan una región de cuadrilátero. |
| [QualitySettings](./qualitysettings/) | QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante em |
| [RecognitionAbortedException](./recognitionabortedexception/) | Representa la excepción de aborto de reconocimiento que se lanza al exceder el tiempo de espera durante el reconocimiento con BarCodeReader. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Clase para almacenar datos secundarios y adicionales HIBC LIC. |
| [SubfileProperties](./subfileproperties/) | Las propiedades del subarchivo USA DL, desplazamiento y longitud se establecen automáticamente. |
| [SupplementParameters](./supplementparameters/) | Parámetros suplementarios. Usado para Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SvgParameters](./svgparameters/) | Parámetros SVG. |
| [SwissQRBill](./swissqrbill/) | Datos de factura SwissQR |
| [SwissQRCodetext](./swissqrcodetext/) | Clase para codificar y decodificar el texto incrustado en el código SwissQR. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Clase para codificar y decodificar el texto incrustado en el código PDF417 de la licencia de conducir de EE. UU. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Clase para campos específicos de jurisdicción para USA DL |
| [Unit](./unit/) | Especifica el valor de tamaño en diferentes unidades (Pixel, Inches, etc.). |
