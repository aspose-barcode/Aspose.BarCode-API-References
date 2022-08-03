---
title: DecodeType
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Specificare il tipo di codice a barre da leggere.
type: docs
weight: 190
url: /it/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Specificare il tipo di codice a barre da leggere.

```csharp
public static class DecodeType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray) { get; } | Ottiene un array che rappresenta AllSupportedTypes |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames)() | Recupera un array dei nomi dei tipi di decodifica. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d)(BaseDecodeType) | Determina se è specificato[`BaseDecodeType`](../basedecodetype) contiene qualsiasi simbologia di codici a barre 1D |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d)(BaseDecodeType) | Determina se è specificato[`BaseDecodeType`](../basedecodetype) contiene qualsiasi simbologia di codici a barre 2D |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal)(BaseDecodeType) | Determina se è specificato[`BaseDecodeType`](../basedecodetype) contiene qualsiasi simbologia del codice a barre postale |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse)(string, out SingleDecodeType) | Converte la rappresentazione di stringa di un SingleDecodeType nella relativa istanza. Un valore restituito indica se la conversione è riuscita o meno. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets)(params BaseDecodeType[]) | Specifica i set di scansione per barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse)(string, out MultyDecodeType) | Converte la rappresentazione di stringa di un MultyDecodeType nella relativa istanza. Un valore restituito indica se la conversione è riuscita o meno. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse_1)(string, out SingleDecodeType) | Converte la rappresentazione di stringa di un SingleDecodeType nella relativa istanza. Un valore restituito indica se la conversione è riuscita o meno. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes) | Specifica che i dati verranno controllati con tutte le simbologie disponibili |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel) | Specifica con cui i dati devono essere decodificati **Codice a barre eParcel nazionale australiano** specifica del codice a barre |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost) | Specifica con cui i dati devono essere decodificati **Posta australiana** specifica del codice a barre |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec) | Specifica con cui i dati devono essere decodificati **azteco** specifica del codice a barre |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar) | Specifica con cui i dati devono essere decodificati **CODABAR** specifica del codice a barre |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf) | Specifica con cui i dati devono essere decodificati **CodablockF** specifica del codice a barre |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11) | Specifica con cui i dati devono essere decodificati **CODICE 11** specifica del codice a barre |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128) | Specifica con cui i dati devono essere decodificati **CODICE 128** specifica del codice a barre |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k) | Specifica con cui i dati devono essere decodificati **SCode16K** specifica del codice a barre |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32) | Specifica con cui i dati devono essere decodificati **Codice32** specifica vuota |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended) | Specifica con cui i dati devono essere decodificati **CODICE 39 esteso** specifica del codice a barre |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard) | Specifica con cui i dati devono essere decodificati **Codice standard 39** specifica del codice a barre |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended) | Specifica con cui i dati devono essere decodificati **CODICE 93 esteso** specifica del codice a barre |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard) | Specifica con cui i dati devono essere decodificati **Codice standard 93** specifica del codice a barre |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417) | Specifica con cui i dati devono essere decodificati **PDF compatto417** (Pdf417 Troncato) specifica del codice a barre |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded) | Specifica con cui i dati devono essere decodificati **GS1 Databar ampliata** specifica del codice a barre |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked) | Specifica con cui i dati devono essere decodificati **GS1 Databar espansa impilata** specifica del codice a barre |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited) | Specifica con cui i dati devono essere decodificati **GS1 Databar limitato** specifica del codice a barre |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional) | Specifica con cui i dati devono essere decodificati **GS1 Databar omnidirezionale** specifica del codice a barre |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked) | Specifica con cui i dati devono essere decodificati **GS1 Databar impilata** specifica del codice a barre |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional) | Specifica con cui i dati devono essere decodificati **GS1 Databar impilato omnidirezionale** specifica del codice a barre |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated) | Specifica con cui i dati devono essere decodificati **GS1 Databar troncata** specifica del codice a barre |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5) | Specifica con cui i dati devono essere decodificati **DataLogic 2 di 5** specifica vuota |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix) | Specifica con cui i dati devono essere decodificati **Data Matrix** simbologia del codice a barre |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode) | Specifica con cui i dati devono essere decodificati **Codice identificativo DeutschePost** specifica del codice a barre |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode) | Specifica con cui i dati devono essere decodificati **Codice Leit DeutschePost** specifica del codice a barre |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode) | Specifica con cui i dati devono essere decodificati **codice punto** specifica vuota |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix) | Specifica con cui i dati devono essere decodificati **codice punto** specifica vuota |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13) | Specifica con cui i dati devono essere decodificati **EAN-13** specifica del codice a barre |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14) | Specifica con cui i dati devono essere decodificati **EAN14** specifica del codice a barre |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8) | Specifica con cui i dati devono essere decodificati **EAN-8** specifica del codice a barre |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128) | Specifica con cui i dati devono essere decodificati **GS1 CODICE 128** specifica del codice a barre |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix) | Specifica con cui i dati devono essere decodificati **matrice di dati GS1** simbologia del codice a barre |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr) | Specifica con cui i dati devono essere decodificati **GS1 QR** specifica del codice a barre |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5) | Specifica con cui i dati devono essere decodificati **IATA 2 di 5** specifica del codice a barre. IATA (International Air Transport Association) utilizza questo codice a barre per la gestione delle merci aviotrasportate. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5) | Specifica con cui i dati devono essere decodificati **INTERFOGLIATO 2 di 5** specifica del codice a barre |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn) | Specifica con cui i dati devono essere decodificati **ISBN** specifica del codice a barre |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn) | Specifica con cui i dati devono essere decodificati **ISMN** specifica del codice a barre |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn) | Specifica con cui i dati devono essere decodificati **ISSN** specifica del codice a barre |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25) | Specifica con cui i dati devono essere decodificati **Poste Italiane 25** specifica del codice a barre |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14) | Specifica con cui i dati devono essere decodificati **ITF14** specifica del codice a barre |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6) | Specifica con cui i dati devono essere decodificati **ITF6** specifica del codice a barre |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417) | Specifica con cui i dati devono essere decodificati **MacroPDF417** specifica del codice a barre |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark) | Specifica con cui i dati devono essere decodificati **Timbro postale di Royal Mail** specifica del codice a barre. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5) | Specifica con cui i dati devono essere decodificati **Matrice 2 di 5** specifica del codice a barre |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode) | Specifica con cui i dati devono essere decodificati **MaxiCodice** specifica del codice a barre |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b) | Specifica con cui i dati devono essere decodificati **MICR E-13B** specifica vuota |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417) | Specifica con cui i dati devono essere decodificati **MicroPdf417** specifica del codice a barre |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr) | Specifica con cui i dati devono essere decodificati **Codice MicroQR** specifica del codice a barre |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes) | Specifica che i dati verranno controllati con le simbologie più comunemente utilizzate |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi) | Specifica con cui i dati devono essere decodificati **MSI Plessey** specifica del codice a barre |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none) | Tipo di decodifica non specificato. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode) | Specifica che i dati devono essere decodificati con USPS **Un codice** specifica del codice a barre |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc) | Specifica con cui i dati devono essere decodificati **OPC** specifica del codice a barre |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode) | Specifica con cui i dati devono essere decodificati **Codice patch** specifica del codice a barre. La simbologia del codice a barre viene utilizzata per la scansione automatizzata |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417) | Specifica con cui i dati devono essere decodificati **Pdf417** simbologia del codice a barre |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode) | Specifica con cui i dati devono essere decodificati **Codice Farmaceutico** codice a barre. Questa simbologia è anche conosciuta come Codice Binario Farmaceutico |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet) | Specifica con cui i dati devono essere decodificati **Pianeta** specifica del codice a barre |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes) | Specifica che i dati verranno controllati con tutti **1.5D postale** simbologie di codici a barre, come **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet) | Specifica con cui i dati devono essere decodificati **Postnet** specifica del codice a barre |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn) | Specifica con cui i dati devono essere decodificati **PZN**specifica del codice a barre. Questa simbologia è anche conosciuta come Pharma Zentral Nummer |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr) | Specifica con cui i dati devono essere decodificati **QR Code** specifica del codice a barre |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc) | Specifica con cui i dati devono essere decodificati **RM4SCC** specifica del codice a barre. RM4SCC (Royal Mail 4-state Customer Code) viene utilizzato per il processo di smistamento automatico della posta nel Regno Unito. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14) | Specifica con cui i dati devono essere decodificati **SCC14** specifica del codice a barre |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18) | Specifica con cui i dati devono essere decodificati **SSCC18** specifica del codice a barre |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5) | Specifica con cui i dati devono essere decodificati **Standard 2 di 5** specifica del codice a barre |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement) | Specifica con cui i dati devono essere decodificati **Supplemento(EAN2, EAN5)** specifica del codice a barre |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel) | Specifica con cui i dati devono essere decodificati **Codice a barre del pacco della Posta Svizzera** specifica del codice a barre |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d) | Specifica che i dati verranno controllati con tutti **1D** simbologie di codici a barre |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d) | Specifica che i dati verranno controllati con tutti **2D** simbologie di codici a barre |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca) | Specifica con cui i dati devono essere decodificati **UPC-A** specifica del codice a barre |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce) | Specifica con cui i dati devono essere decodificati **UPC-E** specifica del codice a barre |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin) | Specifica con cui i dati devono essere decodificati **VIN** (Numero di identificazione del veicolo) specifica del codice a barre |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
