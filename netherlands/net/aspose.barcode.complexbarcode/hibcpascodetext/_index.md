---
title: "Klasse HIBCPASCodetext"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.HIBCPASCodetext klasse. Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC PAS‑code"
type: docs
weight: 600
url: /nl/net/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class

Klasse voor het coderen en decoderen van de in de HIBC PAS-code ingebedde tekst.

```csharp
public class HIBCPASCodetext : IComplexCodetext
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [HIBCPASCodetext](hibcpascodetext/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/barcodetype/) { get; set; } | Haalt op of stelt barcode‑type in. HIBC PAS codetext kan worden gecodeerd met HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS en HIBCQRPAS‑coderingstypen. Standaardwaarde: HIBCCode39PAS. |
| [DataLocation](../../aspose.barcode.complexbarcode/hibcpascodetext/datalocation/) { get; set; } | Identificeert datalocatie. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord_1)(HIBCPASRecord) | Voegt nieuw record toe |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord)(HIBCPASDataType, string) | Voegt nieuw record toe |
| [Clear](../../aspose.barcode.complexbarcode/hibcpascodetext/clear/)() | Leegt de lijst met records |
| override [Equals](../../aspose.barcode.complexbarcode/hibcpascodetext/equals/)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `HIBCPASCodetext`-waarde. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/getbarcodetype/)() | Haalt het barcode-type op. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcpascodetext/getconstructedcodetext/)() | Construeert codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcpascodetext/gethashcode/)() | Retourneert de hashcode voor deze instantie. |
| [GetRecords](../../aspose.barcode.complexbarcode/hibcpascodetext/getrecords/)() | Haalt lijst met records op |
| [InitFromString](../../aspose.barcode.complexbarcode/hibcpascodetext/initfromstring/)(string) | Initialiseert de instantie vanuit geconstrueerde codetext. |

## Voorbeelden

Dit voorbeeld toont hoe HIBC PAS te coderen en decoderen met behulp van HIBCPASCodetext.

```csharp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText; 
		HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
		Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

### Zie ook

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


