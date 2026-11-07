---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType classe"
linktitle: "DecodeType"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType classe. Specifica il tipo di codice a barre da leggere in C++."
type: docs
weight: 1600
url: /it/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


Specifica il tipo di codice a barre da leggere.

```cpp
class DecodeType
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | Ottiene un array che rappresenta AllSupportedTypes |
| static [GetNames](./getnames/)() | Recupera un array dei nomi dei tipi di decodifica. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | Determina se il [BaseDecodeType](../basedecodetype/) specificato contiene qualche simbologia di codice a barre 1D |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | Determina se il [BaseDecodeType](../basedecodetype/) specificato contiene qualche simbologia di codice a barre 2D |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | Determina se il [BaseDecodeType](../basedecodetype/) specificato contiene qualche simbologia di codice a barre postale |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converte la rappresentazione stringa di un [SingleDecodeType](../singledecodetype/) nella sua istanza. Un valore restituito indica se la conversione è riuscita o meno. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Specifica i set di scansione per barcodeTypes |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converte la rappresentazione stringa di un [SingleDecodeType](../singledecodetype/) nella sua istanza. Un valore restituito indica se la conversione è riuscita o meno. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converte la rappresentazione stringa di un [MultiDecodeType](../multidecodetype/) nella sua istanza. Un valore restituito indica se la conversione è riuscita o meno. |
## Campi

| Campo | Descrizione |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | Specifica che i dati saranno controllati con tutte le simbologie disponibili |
| static [AustralianPosteParcel](./australianposteparcel/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Australian Post Domestic eParcel Barcode** |
| static [AustraliaPost](./australiapost/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Australia Post** |
| static [Aztec](./aztec/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Aztec** |
| static [Codabar](./codabar/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **CODABAR** |
| static [CodablockF](./codablockf/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **CodablockF** |
| static [Code11](./code11/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **CODE 11** |
| static [Code128](./code128/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **CODE 128** |
| static [Code16K](./code16k/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **SCode16K** |
| static [Code32](./code32/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Code32** |
| static [Code39](./code39/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Code 39** charset di base: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Code 39** charset ASCII completo: ISO/IEC 16388 |
| static [Code93](./code93/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **CODE 93** |
| static [CompactPdf417](./compactpdf417/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **CompactPdf417** (Pdf417Truncated) |
| static [DatabarExpanded](./databarexpanded/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 Databar expanded** |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 Databar expanded stacked** |
| static [DatabarLimited](./databarlimited/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 Databar limited** |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 Databar omni-directional** |
| static [DatabarStacked](./databarstacked/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 Databar stacked** |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 Databar stacked omni-directional** |
| static [DatabarTruncated](./databartruncated/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 Databar truncated** |
| static [DataLogic2of5](./datalogic2of5/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **DataLogic 2 of 5** |
| static [DataMatrix](./datamatrix/) | Specifica che i dati devono essere decodificati con la simbologia del codice a barre **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **DeutschePost Ident code** |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **DeutschePost Leit code** |
| static [DotCode](./dotcode/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **DotCode** |
| static [DutchKIX](./dutchkix/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **DotCode** |
| static [EAN13](./ean13/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **EAN-13** |
| static [EAN14](./ean14/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **EAN14** |
| static [EAN8](./ean8/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **EAN-8** |
| static [GS1Aztec](./gs1aztec/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 Aztec** |
| static [GS1Code128](./gs1code128/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 CODE 128** |
| static [GS1CompositeBar](./gs1compositebar/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 Composite Bar** |
| static [GS1DataMatrix](./gs1datamatrix/) | Specifica che i dati devono essere decodificati con la simbologia del codice a barre **GS1DataMatrix** |
| static [GS1DotCode](./gs1dotcode/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 DotCode** |
| static [GS1HanXin](./gs1hanxin/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 Han Xin Code** |
| static [GS1MicroPdf417](./gs1micropdf417/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MicroPdf417** |
| static [GS1QR](./gs1qr/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [HanXin](./hanxin/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Han Xin Code** |
| static [HIBCAztecLIC](./hibcazteclic/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **HIBC LIC Aztec** |
| static [HIBCAztecPAS](./hibcaztecpas/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **HIBC PAS Aztec** |
| static [HIBCCode128LIC](./hibccode128lic/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **HIBC LIC Code128** |
| static [HIBCCode128PAS](./hibccode128pas/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **HIBC PAS Code128** |
| static [HIBCCode39LIC](./hibccode39lic/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **HIBC LIC Code39** |
| static [HIBCCode39PAS](./hibccode39pas/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **HIBC PAS Code39** |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** |
| static [HIBCQRLIC](./hibcqrlic/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [HIBCQRPAS](./hibcqrpas/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [IATA2of5](./iata2of5/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **IATA 2 of 5**. IATA (International Air Transport Association) utilizza questo codice a barre per la gestione del carico aereo. |
| static [Interleaved2of5](./interleaved2of5/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **INTERLEAVED 2 of 5** |
| static [ISBN](./isbn/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **ISBN** |
| static [ISMN](./ismn/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **ISMN** |
| static [ISSN](./issn/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **ISSN** |
| static [ItalianPost25](./italianpost25/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Italian Post 25** |
| static [ITF14](./itf14/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **ITF14** |
| static [ITF6](./itf6/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **ITF6** |
| static [JapanPost](./japanpost/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Japan Post** |
| static [MacroPdf417](./macropdf417/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MacroPdf417** |
| static [Mailmark](./mailmark/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Royal Mail Mailmark**. |
| static [Matrix2of5](./matrix2of5/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Matrix 2 of 5** |
| static [MaxiCode](./maxicode/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MaxiCode** |
| static [MicrE13B](./micre13b/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MICR E-13B** |
| static [MicroPdf417](./micropdf417/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MicroPdf417** |
| static [MicroQR](./microqr/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MicroQR Code** |
| static [MostCommonTypes](./mostcommontypes/) | Specifica che i dati saranno controllati con le simbologie più comunemente utilizzate |
| static [MSI](./msi/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MSI Plessey** |
| static [None](./none/) | Tipo di decodifica non specificato. |
| static [OneCode](./onecode/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre USPS **OneCode** |
| static [OPC](./opc/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **OPC** |
| static [PatchCode](./patchcode/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Patch code**. La simbologia del codice a barre è utilizzata per la scansione automatica |
| static [Pdf417](./pdf417/) | Specifica che i dati devono essere decodificati con la simbologia del codice a barre **Pdf417** |
| static [Pharmacode](./pharmacode/) | Specifica che i dati devono essere decodificati con il codice a barre **Pharmacode**. Questa simbologia è anche nota come Pharmaceutical Binary Code |
| static [Planet](./planet/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Planet** |
| static [PostalTypes](./postaltypes/) | Specifica che i dati saranno verificati con tutte le simbologie di codice a barre **1.5D Postal**, come **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Postnet** |
| static [PZN](./pzn/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **PZN**. Questa simbologia è anche nota come Pharma Zentral Nummer. PZN7 e PZN8 sono supportati. |
| static [QR](./qr/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** |
| static [RectMicroQR](./rectmicroqr/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) è utilizzato per il processo di smistamento automatico della posta nel Regno Unito. |
| static [SCC14](./scc14/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **SCC14** |
| static [SSCC18](./sscc18/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **SSCC18** |
| static [Standard2of5](./standard2of5/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Standard 2 of 5** |
| static [Supplement](./supplement/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Supplement(EAN2, EAN5)** |
| static [SwissPostParcel](./swisspostparcel/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Swiss Post Parcel Barcode** |
| static [Types1D](./types1d/) | Specifica che i dati saranno verificati con tutte le simbologie di codice a barre **1D** |
| static [Types2D](./types2d/) | Specifica che i dati saranno verificati con tutte le simbologie di codice a barre **2D** |
| static [UPCA](./upca/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **UPC-A** |
| static [UPCE](./upce/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **UPC-E** |
| static [VIN](./vin/) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **VIN** (Vehicle Identification Number) |
## Osservazioni


Questo esempio mostra come rilevare i codici a barre Code39 e Code128.
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

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
