---
title: DecodeType
second_title: Referencia de API de Aspose.BarCode para .NET
description: Especifique el tipo de código de barras a leer.
type: docs
weight: 190
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
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray) { get; } | Obtiene una matriz que representa AllSupportedTypes |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames)() | Recupera una matriz de los nombres de los tipos de decodificación. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d)(BaseDecodeType) | Determina si el especificado[`BaseDecodeType`](../basedecodetype) contiene cualquier simbología de código de barras 1D |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d)(BaseDecodeType) | Determina si el especificado[`BaseDecodeType`](../basedecodetype) contiene cualquier simbología de código de barras 2D |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal)(BaseDecodeType) | Determina si el especificado[`BaseDecodeType`](../basedecodetype) contiene cualquier simbología de código de barras Postal |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse)(string, out SingleDecodeType) | Convierte la representación de cadena de un SingleDecodeType en su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets)(params BaseDecodeType[]) | Especificar conjuntos de escaneo por tipo de código de barras |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse)(string, out MultyDecodeType) | Convierte la representación de cadena de un MultyDecodeType en su instancia. Un valor de retorno indica si la conversión se realizó correctamente o falló. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse_1)(string, out SingleDecodeType) | Convierte la representación de cadena de un SingleDecodeType en su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes) | Especifica que los datos se verificarán con todas las simbologías disponibles |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel) | Especifica que los datos deben decodificarse con **Código de barras eParcel del correo nacional australiano** especificación de código de barras |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost) | Especifica que los datos deben decodificarse con **Correo de Australia** especificación de código de barras |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec) | Especifica que los datos deben decodificarse con **azteca** especificación de código de barras |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar) | Especifica que los datos deben decodificarse con **CODABAR** especificación de código de barras |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf) | Especifica que los datos deben decodificarse con **CodablockF** especificación de código de barras |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11) | Especifica que los datos deben decodificarse con **CÓDIGO 11** especificación de código de barras |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128) | Especifica que los datos deben decodificarse con **CÓDIGO 128** especificación de código de barras |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k) | Especifica que los datos deben decodificarse con **Código SC16K** especificación de código de barras |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32) | Especifica que los datos deben decodificarse con **código32** especificación en blanco |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended) | Especifica que los datos deben decodificarse con **CÓDIGO extendido 39** especificación de código de barras |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard) | Especifica que los datos deben decodificarse con **CÓDIGO estándar 39** especificación de código de barras |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended) | Especifica que los datos deben decodificarse con **CÓDIGO extendido 93** especificación de código de barras |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard) | Especifica que los datos deben decodificarse con **CÓDIGO estándar 93** especificación de código de barras |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417) | Especifica que los datos deben decodificarse con **CompactPdf417** (Pdf417Truncado) especificación de código de barras |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded) | Especifica que los datos deben decodificarse con **Barra de datos GS1 ampliada** especificación de código de barras |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked) | Especifica que los datos deben decodificarse con **GS1 Databar expandido apilado** especificación de código de barras |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited) | Especifica que los datos deben decodificarse con **Barra de datos GS1 limitada** especificación de código de barras |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional) | Especifica que los datos deben decodificarse con **GS1 Databar omnidireccional** especificación de código de barras |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked) | Especifica que los datos deben decodificarse con **Barra de datos GS1 apilada** especificación de código de barras |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional) | Especifica que los datos deben decodificarse con **GS1 Databar apilado omnidireccional** especificación de código de barras |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated) | Especifica que los datos deben decodificarse con **Barra de datos GS1 truncada** especificación de código de barras |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5) | Especifica que los datos deben decodificarse con **DataLogic 2 de 5** especificación en blanco |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix) | Especifica que los datos deben decodificarse con **Matriz de datos** simbología de código de barras |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode) | Especifica que los datos deben decodificarse con **Código de identificación de Deutsche Post** especificación de código de barras |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode) | Especifica que los datos deben decodificarse con **Código Leit de Deutsche Post** especificación de código de barras |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode) | Especifica que los datos deben decodificarse con **código de punto** especificación en blanco |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix) | Especifica que los datos deben decodificarse con **código de punto** especificación en blanco |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13) | Especifica que los datos deben decodificarse con **EAN-13** especificación de código de barras |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14) | Especifica que los datos deben decodificarse con **EAN14** especificación de código de barras |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8) | Especifica que los datos deben decodificarse con **EAN-8** especificación de código de barras |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128) | Especifica que los datos deben decodificarse con **CÓDIGO GS1 128** especificación de código de barras |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix) | Especifica que los datos deben decodificarse con **Matriz de datos GS1** simbología de código de barras |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr) | Especifica que los datos deben decodificarse con **QR GS1** especificación de código de barras |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5) | Especifica que los datos deben decodificarse con **IATA 2 de 5** Especificación de código de barras. IATA (Asociación Internacional de Transporte Aéreo) utiliza este código de barras para la gestión de la carga aérea. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5) | Especifica que los datos deben decodificarse con **INTERLEVADO 2 de 5** especificación de código de barras |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn) | Especifica que los datos deben decodificarse con **ISBN** especificación de código de barras |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn) | Especifica que los datos deben decodificarse con **ISMN** especificación de código de barras |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn) | Especifica que los datos deben decodificarse con **ISSN** especificación de código de barras |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25) | Especifica que los datos deben decodificarse con **Correo italiano 25** especificación de código de barras |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14) | Especifica que los datos deben decodificarse con **ITF14** especificación de código de barras |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6) | Especifica que los datos deben decodificarse con **ITF6** especificación de código de barras |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417) | Especifica que los datos deben decodificarse con **MacroPdf417** especificación de código de barras |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark) | Especifica que los datos deben decodificarse con **Marca de correo real** especificación de código de barras. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5) | Especifica que los datos deben decodificarse con **Matriz 2 de 5** especificación de código de barras |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode) | Especifica que los datos deben decodificarse con **maxicódigo** especificación de código de barras |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b) | Especifica que los datos deben decodificarse con **MICR E-13B** especificación en blanco |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417) | Especifica que los datos deben decodificarse con **MicroPdf417** especificación de código de barras |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr) | Especifica que los datos deben decodificarse con **Código MicroQR** especificación de código de barras |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes) | Especifica que los datos se comprobarán con las simbologías más utilizadas |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi) | Especifica que los datos deben decodificarse con **MSI Plessey** especificación de código de barras |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none) | Tipo de decodificación no especificado. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode) | Especifica que los datos deben decodificarse con USPS **Código único** especificación de código de barras |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc) | Especifica que los datos deben decodificarse con **OPC** especificación de código de barras |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode) | Especifica que los datos deben decodificarse con **Código de parche** Especificación de código de barras. La simbología de código de barras se utiliza para el escaneo automatizado |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417) | Especifica que los datos deben decodificarse con **Pdf417** simbología de código de barras |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode) | Especifica que los datos deben decodificarse con **Farmacódigo** código de barras. Esta simbología también se conoce como Código binario farmacéutico |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet) | Especifica que los datos deben decodificarse con **Planeta** especificación de código de barras |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes) | Especifica que los datos se verificarán con todos **postal 1.5D** simbologías de códigos de barras, como **Planet, Postnet, Australia Post, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet) | Especifica que los datos deben decodificarse con **posnet** especificación de código de barras |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn) | Especifica que los datos deben decodificarse con **PZN**Especificación de código de barras. Esta simbología también se conoce como Pharma Zentral Nummer |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr) | Especifica que los datos deben decodificarse con **Código QR** especificación de código de barras |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc) | Especifica que los datos deben decodificarse con **RM4SCC** Especificación de código de barras. RM4SCC (Código de cliente de 4 estados de Royal Mail) se utiliza para el proceso de clasificación de correo automatizado en el Reino Unido. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14) | Especifica que los datos deben decodificarse con **SCC14** especificación de código de barras |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18) | Especifica que los datos deben decodificarse con **SSCC18** especificación de código de barras |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5) | Especifica que los datos deben decodificarse con **Estándar 2 de 5** especificación de código de barras |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement) | Especifica que los datos deben decodificarse con **Suplemento (EAN2, EAN5)** especificación de código de barras |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel) | Especifica que los datos deben decodificarse con **Código de barras de paquete postal suizo** especificación de código de barras |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d) | Especifica que los datos se verificarán con todos **1D** simbologías de código de barras |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d) | Especifica que los datos se verificarán con todos **2D** simbologías de código de barras |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca) | Especifica que los datos deben decodificarse con **UPC-A** especificación de código de barras |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce) | Especifica que los datos deben decodificarse con **UPC-E** especificación de código de barras |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin) | Especifica que los datos deben decodificarse con **VIN** (Número de identificación del vehículo) especificación de código de barras |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ver también

* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
