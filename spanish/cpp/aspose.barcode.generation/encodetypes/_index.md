---
title: "Aspose::BarCode::Generation::EncodeTypes class"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::Generation::EncodeTypes class. Especifica el tipo de código de barras a codificar en C++."
type: docs
weight: 2300
url: /es/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


Especifica el tipo de código de barras a codificar.

```cpp
class EncodeTypes
```

## Métodos

| Método | Descripción |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | Especifica que los datos se verificarán con todas las simbologías disponibles. |
| static [GetNames](./getnames/)() | Recupera una matriz con los nombres de los tipos de codificación. |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Convierte la representación de cadena de un [BaseEncodeType](../baseencodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Convierte la representación de cadena de un [BaseEncodeType](../baseencodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | Especifica que los datos deben codificarse con la especificación de código de barras **Australian Post Domestic eParcel Barcode** |
| static [AustraliaPost](./australiapost/) | Representa al cliente de Australia Post [BarCode](../../aspose.barcode/) |
| static [Aztec](./aztec/) | Especifica que los datos deben codificarse con la especificación de código de barras **Aztec** |
| static [Codabar](./codabar/) | Especifica que los datos deben codificarse con **CODABAR** especificación de código de barras |
| static [CodablockF](./codablockf/) | Especifica que los datos deben codificarse con **Codablock-F** especificación de código de barras. |
| static [Code11](./code11/) | Especifica que los datos deben codificarse con **CODE 11** especificación de código de barras |
| static [Code128](./code128/) | Especifica que los datos deben codificarse con **CODE 128** especificación de código de barras |
| static [Code16K](./code16k/) | Representa el código de barras Code 16K. |
| static [Code32](./code32/) | Especifica que los datos deben codificarse con **Code32** especificación de código de barras |
| static [Code39](./code39/) | Especifica que los datos deben codificarse con **Code 39** especificación de código de barras de conjunto de caracteres básico: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Especifica que los datos deben codificarse con **Code 39** especificación de código de barras de conjunto de caracteres ASCII completo: ISO/IEC 16388 |
| static [Code93](./code93/) | Especifica que los datos deben codificarse con **CODE 93** especificación de código de barras |
| static [DatabarExpanded](./databarexpanded/) | Representa el código de barras GS1 Databar expandido. |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Representa el código de barras GS1 Databar expandido apilado. |
| static [DatabarLimited](./databarlimited/) | Representa el código de barras GS1 Databar limitado. |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Especifica que los datos deben codificarse con **GS1 Databar omni-directional** especificación de código de barras. |
| static [DatabarStacked](./databarstacked/) | Representa el código de barras GS1 Databar apilado. |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Representa el código de barras GS1 Databar apilado omni-direccional. |
| static [DatabarTruncated](./databartruncated/) | Especifica que los datos deben codificarse con **GS1 Databar truncated** especificación de código de barras. |
| static [DataLogic2of5](./datalogic2of5/) | Especifica que los datos deben codificarse con **DataLogic 2 of 5** especificación de código de barras |
| static [DataMatrix](./datamatrix/) | Simbolismo de código de barras 2D DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Representa el código de barras Deutsch Post, este simbolismo también se conoce como Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Representa el código de barras Deutsch Post Leitcode, también conocido como German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| static [DotCode](./dotcode/) | Especifica que los datos deben codificarse con **DotCode** especificación de código de barras |
| static [DutchKIX](./dutchkix/) | Especifica que los datos deben codificarse con **Dutch KIX** especificación de código de barras |
| static [EAN13](./ean13/) | Especifica que los datos deben codificarse con **EAN-13** especificación de código de barras |
| static [EAN14](./ean14/) | Especifica que los datos deben codificarse con **EAN14** especificación de código de barras |
| static [EAN8](./ean8/) | Especifica que los datos deben codificarse con **EAN-8** especificación de código de barras |
| static [GS1Aztec](./gs1aztec/) | Especifica que los datos deben codificarse con la especificación de código de barras **GS1 Aztec**. El codetext debe contener paréntesis para AI. |
| static [GS1CodablockF](./gs1codablockf/) | Especifica que los datos deben codificarse con la especificación de código de barras **GS1 Codablock-F**. El codetext debe contener paréntesis para AI. |
| static [GS1Code128](./gs1code128/) | Especifica que los datos deben codificarse con la especificación de código de barras **GS1 Code 128**. El codetext debe contener paréntesis para AI. |
| static [GS1CompositeBar](./gs1compositebar/) | Especifica que los datos deben codificarse con la especificación de código de barras **GS1 Composite Bar**. El codetext debe contener paréntesis para AI. El codetext 1D y el codetext 2D deben separarse con el símbolo '/' |
| static [GS1DataMatrix](./gs1datamatrix/) | Simbología de código de barras 2D DataMatrix con formato de cadena GS1 |
| static [GS1DotCode](./gs1dotcode/) | Especifica que los datos deben codificarse con la especificación de código de barras **GS1 DotCode**. El codetext debe contener paréntesis para AI. |
| static [GS1HanXin](./gs1hanxin/) | Simbología de código de barras 2D HanXin con formato de cadena GS1 |
| static [GS1MicroPdf417](./gs1micropdf417/) | Especifica que los datos deben codificarse con la especificación de código de barras **GS1MicroPdf417** |
| static [GS1QR](./gs1qr/) | Simbología de código de barras 2D QR con formato de cadena GS1 |
| static [HanXin](./hanxin/) | Especifica que los datos deben codificarse con la especificación de código de barras **Han Xin** |
| static [HIBCAztecLIC](./hibcazteclic/) | Especifica que los datos deben codificarse con la especificación de código de barras **HIBC LIC Aztec**. |
| static [HIBCAztecPAS](./hibcaztecpas/) | Especifica que los datos deben codificarse con la especificación de código de barras **HIBC PAS Aztec**. |
| static [HIBCCode128LIC](./hibccode128lic/) | Especifica que los datos deben codificarse con la especificación de código de barras **HIBC LIC Code128**. |
| static [HIBCCode128PAS](./hibccode128pas/) | Especifica que los datos deben codificarse con la especificación de código de barras **HIBC PAS Code128**. |
| static [HIBCCode39LIC](./hibccode39lic/) | Especifica que los datos deben codificarse con la especificación de código de barras **HIBC LIC Code39**. |
| static [HIBCCode39PAS](./hibccode39pas/) | Especifica que los datos deben codificarse con la especificación de código de barras **HIBC PAS Code39**. |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Especifica que los datos deben codificarse con la especificación de código de barras **HIBC LIC DataMatrix**. |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Especifica que los datos deben codificarse con la especificación de código de barras **HIBC PAS DataMatrix**. |
| static [HIBCQRLIC](./hibcqrlic/) | Especifica que los datos deben codificarse con la especificación de código de barras **HIBC LIC QR**. |
| static [HIBCQRPAS](./hibcqrpas/) | Especifica que los datos deben codificarse con la especificación de código de barras **HIBC PAS QR**. |
| static [IATA2of5](./iata2of5/) | Representa el código de barras IATA 2 de 5. IATA (International Air Transport Association) utiliza este código de barras para la gestión de carga aérea. |
| static [Interleaved2of5](./interleaved2of5/) | Especifica que los datos deben codificarse con la especificación de código de barras **INTERLEAVED 2 of 5** |
| static [ISBN](./isbn/) | Especifica que los datos deben codificarse con la especificación de código de barras **ISBN** |
| static [ISMN](./ismn/) | Especifica que los datos deben codificarse con la especificación de código de barras **ISMN** |
| static [ISSN](./issn/) | Especifica que los datos deben codificarse con la especificación de código de barras **ISSN** |
| static [ItalianPost25](./italianpost25/) | Representa el código de barras Italian Post 25. |
| static [ITF14](./itf14/) | Especifica que los datos deben codificarse con la especificación de código de barras **ITF14** |
| static [ITF6](./itf6/) | Representa el código de barras ITF-6. |
| static [JapanPost](./japanpost/) | Representa Japan Post [BarCode](../../aspose.barcode/) |
| static [MacroPdf417](./macropdf417/) | Especifica que los datos deben codificarse con la especificación de código de barras **MacroPdf417** |
| static [Mailmark](./mailmark/) | Representa el código de barras Royal Mail Mailmark. |
| static [Matrix2of5](./matrix2of5/) | Representa Matrix 2 of 5 [BarCode](../../aspose.barcode/) |
| static [MaxiCode](./maxicode/) | Especifica que los datos deben codificarse con la especificación de código de barras **MaxiCode** |
| static [MicroPdf417](./micropdf417/) | Especifica que los datos deben codificarse con la especificación de código de barras **MicroPdf417** |
| static [MicroQR](./microqr/) | Especifica que los datos deben codificarse con la especificación de código de barras **MicroQR Code** |
| static [MSI](./msi/) | Especifica que los datos deben codificarse con la especificación de código de barras **MSI Plessey** |
| static [None](./none/) | Tipo de codificación no especificado. |
| static [OneCode](./onecode/) | Especifica que los datos deben codificarse con la especificación de código de barras USPS **OneCode** |
| static [OPC](./opc/) | Representa el código de barras OPC (Optical Product Code), también conocido como VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| static [PatchCode](./patchcode/) | Representa el código de barras Patch code |
| static [Pdf417](./pdf417/) | Especifica que los datos deben codificarse con la especificación de código de barras **Pdf417** |
| static [Pharmacode](./pharmacode/) | Representa el código de barras Pharmacode. |
| static [Planet](./planet/) | Especifica que los datos deben codificarse con la especificación de código de barras **Planet** |
| static [Postnet](./postnet/) | Especifica que los datos deben codificarse con la especificación de código de barras **Postnet** |
| static [PZN](./pzn/) | Representa el código de barras PZN. Esta simbología también se conoce como Pharmacy central number, Pharmazentralnummer. Se admiten PZN7 y PZN8. PZN7 se genera a partir de 6 o menos dígitos, como "123456". PZN8 se genera a partir de 7 o más dígitos, como "1234567". El último dígito de checksum proporcionado se ignora y es generado por el motor del código de barras. |
| static [QR](./qr/) | Especifica que los datos deben codificarse con la especificación de código de barras **QR Code** |
| static [RectMicroQR](./rectmicroqr/) | Especifica que los datos deben codificarse con la especificación de código de barras **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | Representa el código de barras RM4SCC. RM4SCC (Royal Mail 4-state Customer Code) se utiliza para el proceso automatizado de clasificación de correo en el Reino Unido. |
| static [SCC14](./scc14/) | Especifica que los datos deben codificarse con la especificación de código de barras **SCC14** |
| static [SingaporePost](./singaporepost/) | Especifica que los datos deben codificarse con la especificación de código de barras **Singapore Post Barcode** |
| static [SSCC18](./sscc18/) | Especifica que los datos deben codificarse con la especificación de código de barras **SSCC18** |
| static [Standard2of5](./standard2of5/) | Especifica que los datos deben codificarse con la especificación de código de barras **Standard 2 of 5** |
| static [SwissPostParcel](./swisspostparcel/) | Especifica que los datos deben codificarse con la especificación de código de barras **Swiss Post Parcel Barcode**. Tipos compatibles: Correo nacional, Correo internacional, Servicios adicionales (nuevo) |
| static [UPCA](./upca/) | Especifica que los datos deben codificarse con la especificación de código de barras **UPC-A** |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | Especifica que los datos deben codificarse con la especificación de código de barras **UPC coupon with GS1-128 Extended Code**. Un ejemplo de la cadena de entrada: BarcodeGenerator.Codetext = "514141100906(8102)03", donde la parte UPCA es "514141100906", la parte GS1Code128 es (8102)03. |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | Especifica que los datos deben codificarse con la especificación de código de barras **UPC coupon with GS1 DataBar addition**. Un ejemplo de la cadena de entrada: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", donde la parte UPCA es "514141100906", la parte Databar es "(8110)106141416543213500110000310123196000". Para cambiar el título, use Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static [UPCE](./upce/) | Especifica que los datos deben codificarse con la especificación de código de barras **UPC-E** |
| static [VIN](./vin/) | Representa el código de barras VIN (Vehicle Identification Number). |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
