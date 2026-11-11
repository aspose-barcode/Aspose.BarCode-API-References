---
title: "Clase DecodeType"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.DecodeType. Especifique el tipo de código de barras a leer"
type: docs
weight: 230
url: /es/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Especifique el tipo de código de barras a leer.

```csharp
public static class DecodeType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | Obtiene una matriz que representa AllSupportedTypes |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | Recupera una matriz con los nombres de los tipos de decodificación. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | Determina si el [`BaseDecodeType`](../basedecodetype/) especificado contiene alguna simbología de código de barras 1D |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | Determina si el [`BaseDecodeType`](../basedecodetype/) especificado contiene alguna simbología de código de barras 2D |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | Determina si el [`BaseDecodeType`](../basedecodetype/) especificado contiene alguna simbología de código de barras postal |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | Especifique los conjuntos de escaneo por barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultiDecodeType) | Convierte la representación en cadena de un MultiDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | Especifica que los datos se verificarán con todas las simbologías disponibles |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Australian Post Domestic eParcel Barcode** |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Australia Post** |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Aztec** |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CODABAR** |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CodablockF** |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CODE 11** |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CODE 128** |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | Especifica que los datos deben decodificarse con la especificación de código de barras **SCode16K** |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Code32** |
| static readonly [Code39](../../aspose.barcode.barcoderecognition/decodetype/code39/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Code 39** de conjunto de caracteres básico: ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.barcoderecognition/decodetype/code39fullascii/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Code 39** de conjunto de caracteres ASCII completo: ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.barcoderecognition/decodetype/code93/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CODE 93** |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | Especifica que los datos deben decodificarse con la especificación de código de barras **CompactPdf417** (Pdf417Truncated) |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar expanded** |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar expanded stacked** |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar limited** |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar omni-directional** |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar stacked** |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar stacked omni-directional** |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Databar truncated** |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | Especifica que los datos deben decodificarse con la especificación de código de barras **DataLogic 2 of 5** |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | Especifica que los datos deben decodificarse con la simbología de código de barras **DataMatrix** |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | Especifica que los datos deben decodificarse con la especificación de código de barras **DeutschePost Ident code** |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | Especifica que los datos deben decodificarse con la especificación de código de barras **DeutschePost Leit code** |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | Especifica que los datos deben decodificarse con la especificación de código de barras **DotCode** |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | Especifica que los datos deben decodificarse con la especificación de código de barras **DotCode** |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | Especifica que los datos deben decodificarse con la especificación de código de barras **EAN-13** |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | Especifica que los datos deben decodificarse con la especificación de código de barras **EAN14** |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | Especifica que los datos deben decodificarse con la especificación de código de barras **EAN-8** |
| static readonly [GS1Aztec](../../aspose.barcode.barcoderecognition/decodetype/gs1aztec/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Aztec** |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 CODE 128** |
| static readonly [GS1CompositeBar](../../aspose.barcode.barcoderecognition/decodetype/gs1compositebar/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Composite Bar** |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | Especifica que los datos deben decodificarse con la simbología de código de barras **GS1DataMatrix** |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 DotCode** |
| static readonly [GS1HanXin](../../aspose.barcode.barcoderecognition/decodetype/gs1hanxin/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 Han Xin Code** |
| static readonly [GS1MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/gs1micropdf417/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MicroPdf417** |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | Especifica que los datos deben decodificarse con la especificación de código de barras **GS1 QR** |
| static readonly [HanXin](../../aspose.barcode.barcoderecognition/decodetype/hanxin/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Han Xin Code**. |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC LIC Aztec**. |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC PAS Aztec**. |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC LIC Code128**. |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC PAS Code128**. |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC LIC Code39**. |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC PAS Code39**. |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC LIC DataMatrix**. |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC PAS DataMatrix**. |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC LIC QR**. |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | Especifica que los datos deben decodificarse con la especificación de código de barras **HIBC PAS QR**. |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | Especifica que los datos deben decodificarse con la especificación de código de barras **IATA 2 of 5**. IATA (Asociación Internacional de Transporte Aéreo) utiliza este código de barras para la gestión de carga aérea. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | Especifica que los datos deben decodificarse con la especificación de código de barras **INTERLEAVED 2 of 5**. |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | Especifica que los datos deben decodificarse con la especificación de código de barras **ISBN**. |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | Especifica que los datos deben decodificarse con la especificación de código de barras **ISMN**. |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | Especifica que los datos deben decodificarse con la especificación de código de barras **ISSN**. |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Italian Post 25**. |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | Especifica que los datos deben decodificarse con la especificación de código de barras **ITF14**. |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | Especifica que los datos deben decodificarse con la especificación de código de barras **ITF6**. |
| static readonly [JapanPost](../../aspose.barcode.barcoderecognition/decodetype/japanpost/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Japan Post**. |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MacroPdf417**. |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Royal Mail Mailmark**. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Matrix 2 of 5**. |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MaxiCode**. |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MICR E-13B**. |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MicroPdf417** |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MicroQR Code** |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | Especifica que los datos se comprobarán con las simbologías más utilizadas |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | Especifica que los datos deben decodificarse con la especificación de código de barras **MSI Plessey** |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | Tipo de decodificación no especificado. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | Especifica que los datos deben decodificarse con la especificación de código de barras USPS **OneCode** |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | Especifica que los datos deben decodificarse con la especificación de código de barras **OPC** |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Patch code**. La simbología de código de barras se utiliza para escaneo automatizado |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | Especifica que los datos deben decodificarse con la simbología de código de barras **Pdf417** |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | Especifica que los datos deben decodificarse con el código de barras **Pharmacode**. Esta simbología también se conoce como Pharmaceutical Binary Code |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Planet** |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | Especifica que los datos se comprobarán con todas las simbologías de código de barras **1.5D Postal**, como **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Postnet** |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | Especifica que los datos deben decodificarse con la especificación de código de barras **PZN**. Esta simbología también se conoce como Pharma Zentral Nummer. Se admiten PZN7 y PZN8. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | Especifica que los datos deben decodificarse con la especificación de código de barras **QR Code** |
| static readonly [RectMicroQR](../../aspose.barcode.barcoderecognition/decodetype/rectmicroqr/) | Especifica que los datos deben decodificarse con la especificación de código de barras **RectMicroQR (rMQR) Code** |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | Especifica que los datos deben decodificarse con la especificación de código de barras **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) se utiliza para el proceso automatizado de clasificación de correo en el Reino Unido. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | Especifica que los datos deben decodificarse con la especificación de código de barras **SCC14** |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | Especifica que los datos deben decodificarse con la especificación de código de barras **SSCC18** |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Standard 2 of 5** |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Supplement(EAN2, EAN5)** |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | Especifica que los datos deben decodificarse con la especificación de código de barras **Swiss Post Parcel Barcode** |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | Especifica que los datos se comprobarán con todas las simbologías de código de barras **1D** |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | Especifica que los datos se comprobarán con todas las simbologías de código de barras **2D** |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | Especifica que los datos deben decodificarse con la especificación de código de barras **UPC-A** |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | Especifica que los datos deben decodificarse con la especificación de código de barras **UPC-E** |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | Especifica que los datos deben decodificarse con la especificación de código de barras **VIN** (Vehicle Identification Number) |

## Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
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

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


