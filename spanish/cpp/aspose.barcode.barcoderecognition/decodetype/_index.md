---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType class"
linktitle: "DecodeType"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType class. Especifique el tipo de código de barras a leer en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


Especifique el tipo de código de barras a leer.

```cpp
class DecodeType
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | Obtiene una matriz que representa AllSupportedTypes |
| static [GetNames](./getnames/)() | Recupera una matriz con los nombres de los tipos de decodificación. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | Determina si el [BaseDecodeType](../basedecodetype/) especificado contiene alguna simbología de código de barras 1D |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | Determina si el [BaseDecodeType](../basedecodetype/) especificado contiene alguna simbología de código de barras 2D |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | Determina si el [BaseDecodeType](../basedecodetype/) especificado contiene alguna simbología de código de barras postal |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Convierte la representación en cadena de un [SingleDecodeType](../singledecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Especifica los conjuntos de escaneo por barcodeTypes |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Convierte la representación en cadena de un [SingleDecodeType](../singledecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Convierte la representación de cadena de un [MultiDecodeType](../multidecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | Especifica que los datos se comprobarán con todas las simbologías disponibles |
| static [AustralianPosteParcel](./australianposteparcel/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Australian Post Domestic eParcel Barcode** |
| static [AustraliaPost](./australiapost/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Australia Post** |
| static [Aztec](./aztec/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Aztec** |
| static [Codabar](./codabar/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CODABAR** |
| static [CodablockF](./codablockf/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CodablockF** |
| static [Code11](./code11/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CODE 11** |
| static [Code128](./code128/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CODE 128** |
| static [Code16K](./code16k/) | Especifica que los datos deben decodificarse con la especificación de código de barras **SCode16K** |
| static [Code32](./code32/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Code32** |
| static [Code39](./code39/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Code 39** conjunto de caracteres básico: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Code 39** conjunto de caracteres ASCII completo: ISO/IEC 16388 |
| static [Code93](./code93/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CODE 93** |
| static [CompactPdf417](./compactpdf417/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CompactPdf417** (Pdf417Truncated) |
| static [DatabarExpanded](./databarexpanded/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar expanded** |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar expanded stacked** |
| static [DatabarLimited](./databarlimited/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar limited** |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar omni-directional** |
| static [DatabarStacked](./databarstacked/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar stacked** |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar stacked omni-directional** |
| static [DatabarTruncated](./databartruncated/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar truncated** |
| static [DataLogic2of5](./datalogic2of5/) | Especifica que los datos deben decodificarse con **DataLogic 2 of 5** especificación de código de barras |
| static [DataMatrix](./datamatrix/) | Especifica que los datos deben decodificarse con **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** simbología de código de barras |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Especifica que los datos deben decodificarse con **DeutschePost Ident code** especificación de código de barras |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Especifica que los datos deben decodificarse con **DeutschePost Leit code** especificación de código de barras |
| static [DotCode](./dotcode/) | Especifica que los datos deben decodificarse con **DotCode** especificación de código de barras |
| static [DutchKIX](./dutchkix/) | Especifica que los datos deben decodificarse con **DotCode** especificación de código de barras |
| static [EAN13](./ean13/) | Especifica que los datos deben decodificarse con **EAN-13** especificación de código de barras |
| static [EAN14](./ean14/) | Especifica que los datos deben decodificarse con **EAN14** especificación de código de barras |
| static [EAN8](./ean8/) | Especifica que los datos deben decodificarse con **EAN-8** especificación de código de barras |
| static [GS1Aztec](./gs1aztec/) | Especifica que los datos deben decodificarse con **GS1 Aztec** especificación de código de barras |
| static [GS1Code128](./gs1code128/) | Especifica que los datos deben decodificarse con **GS1 CODE 128** especificación de código de barras |
| static [GS1CompositeBar](./gs1compositebar/) | Especifica que los datos deben decodificarse con **GS1 Composite Bar** especificación de código de barras |
| static [GS1DataMatrix](./gs1datamatrix/) | Especifica que los datos deben decodificarse con **GS1DataMatrix** simbología de código de barras |
| static [GS1DotCode](./gs1dotcode/) | Especifica que los datos deben decodificarse con **GS1 DotCode** especificación de código de barras |
| static [GS1HanXin](./gs1hanxin/) | Especifica que los datos deben decodificarse con **GS1 Han Xin Code** especificación de código de barras |
| static [GS1MicroPdf417](./gs1micropdf417/) | Especifica que los datos deben decodificarse con **MicroPdf417** especificación de código de barras |
| static [GS1QR](./gs1qr/) | Especifica que los datos deben decodificarse con **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** especificación de código de barras |
| static [HanXin](./hanxin/) | Especifica que los datos deben decodificarse con **Han Xin Code** especificación de código de barras |
| static [HIBCAztecLIC](./hibcazteclic/) | Especifica que los datos deben decodificarse con **HIBC LIC Aztec** especificación de código de barras |
| static [HIBCAztecPAS](./hibcaztecpas/) | Especifica que los datos deben decodificarse con **HIBC PAS Aztec** especificación de código de barras |
| static [HIBCCode128LIC](./hibccode128lic/) | Especifica que los datos deben decodificarse con **HIBC LIC Code128** especificación de código de barras |
| static [HIBCCode128PAS](./hibccode128pas/) | Especifica que los datos deben decodificarse con **HIBC PAS Code128** especificación de código de barras |
| static [HIBCCode39LIC](./hibccode39lic/) | Especifica que los datos deben decodificarse con **HIBC LIC Code39** especificación de código de barras |
| static [HIBCCode39PAS](./hibccode39pas/) | Especifica que los datos deben decodificarse con **HIBC PAS Code39** especificación de código de barras |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Especifica que los datos deben decodificarse con **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** especificación de código de barras |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Especifica que los datos deben decodificarse con **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** especificación de código de barras |
| static [HIBCQRLIC](./hibcqrlic/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [HIBCQRPAS](./hibcqrpas/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [IATA2of5](./iata2of5/) | Especifica que los datos deben decodificarse con la especificación de código de barras **IATA 2 of 5**. IATA (International Air Transport Association) utiliza este código de barras para la gestión de carga aérea. |
| static [Interleaved2of5](./interleaved2of5/) | Especifica que los datos deben decodificarse con la especificación de código de barras **INTERLEAVED 2 of 5** |
| static [ISBN](./isbn/) | Especifica que los datos deben decodificarse con la especificación de código de barras **ISBN** |
| static [ISMN](./ismn/) | Especifica que los datos deben decodificarse con la especificación de código de barras **ISMN** |
| static [ISSN](./issn/) | Especifica que los datos deben decodificarse con la especificación de código de barras **ISSN** |
| static [ItalianPost25](./italianpost25/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Italian Post 25** |
| static [ITF14](./itf14/) | Especifica que los datos deben decodificarse con la especificación de código de barras **ITF14** |
| static [ITF6](./itf6/) | Especifica que los datos deben decodificarse con la especificación de código de barras **ITF6** |
| static [JapanPost](./japanpost/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Japan Post** |
| static [MacroPdf417](./macropdf417/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MacroPdf417** |
| static [Mailmark](./mailmark/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Royal Mail Mailmark**. |
| static [Matrix2of5](./matrix2of5/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Matrix 2 of 5** |
| static [MaxiCode](./maxicode/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MaxiCode** |
| static [MicrE13B](./micre13b/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MICR E-13B** |
| static [MicroPdf417](./micropdf417/) | Especifica que los datos deben decodificarse con **MicroPdf417** especificación de código de barras |
| static [MicroQR](./microqr/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MicroQR Code** |
| static [MostCommonTypes](./mostcommontypes/) | Especifica que los datos se comprobarán con las simbologías más utilizadas |
| static [MSI](./msi/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MSI Plessey** |
| static [None](./none/) | Tipo de decodificación no especificado. |
| static [OneCode](./onecode/) | Especifica que los datos deben decodificarse con la especificación de código de barras USPS **OneCode** |
| static [OPC](./opc/) | Especifica que los datos deben decodificarse con la especificación de código de barras **OPC** |
| static [PatchCode](./patchcode/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Patch code**. La simbología de código de barras se utiliza para escaneo automatizado |
| static [Pdf417](./pdf417/) | Especifica que los datos deben decodificarse con la simbología de código de barras **Pdf417** |
| static [Pharmacode](./pharmacode/) | Especifica que los datos deben decodificarse con el código de barras **Pharmacode**. Esta simbología también se conoce como Pharmaceutical Binary Code |
| static [Planet](./planet/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Planet** |
| static [PostalTypes](./postaltypes/) | Especifica que los datos se comprobarán con todas las simbologías de código de barras **1.5D Postal**, como **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Postnet** |
| static [PZN](./pzn/) | Especifica que los datos deben decodificarse con la especificación de código de barras **PZN**. Esta simbología también se conoce como Pharma Zentral Nummer. Se admiten PZN7 y PZN8. |
| static [QR](./qr/) | Especifica que los datos deben decodificarse con la especificación de código de barras **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** |
| static [RectMicroQR](./rectmicroqr/) | Especifica que los datos deben decodificarse con la especificación de código de barras **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | Especifica que los datos deben decodificarse con la especificación de código de barras **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) se utiliza para el proceso automatizado de clasificación de correo en el Reino Unido. |
| static [SCC14](./scc14/) | Especifica que los datos deben decodificarse con la especificación de código de barras **SCC14** |
| static [SSCC18](./sscc18/) | Especifica que los datos deben decodificarse con la especificación de código de barras **SSCC18** |
| static [Standard2of5](./standard2of5/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Standard 2 of 5** |
| static [Supplement](./supplement/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Supplement(EAN2, EAN5)** |
| static [SwissPostParcel](./swisspostparcel/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Swiss Post Parcel Barcode** |
| static [Types1D](./types1d/) | Especifica que los datos se comprobarán con todas las simbologías de código de barras **1D** |
| static [Types2D](./types2d/) | Especifica que los datos se comprobarán con todas las simbologías de código de barras **2D** |
| static [UPCA](./upca/) | Especifica que los datos deben decodificarse con la especificación de código de barras **UPC-A** |
| static [UPCE](./upce/) | Especifica que los datos deben decodificarse con la especificación de código de barras **UPC-E** |
| static [VIN](./vin/) | Especifica que los datos deben decodificarse con la especificación de código de barras **VIN** (Vehicle Identification Number) |
## Observaciones


Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
